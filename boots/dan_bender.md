Phase 2 Day 1 

| Coders Mindset | Testing & TDD | Debugging   | Ruby Webapps | ActiveRecord | HTML & CSS   |
| -------------- | ------------- | ---------   | ------------ | ------------ | ----------   |
|  :punch:		 | :cold_sweat:	 | :punch:	   |:raised_hand: | :raised_hand:| :heart:		|


Today, I learnt how to integreate Rspec into Sinatra (http://net.tutsplus.com/tutorials/ruby/how-to-integrate-rspec-into-a-sinatra-app/). However, up until now I have not done any Rspec and so I need to do an actual tutorial on the syntax etc. of Rspec.


Also, I learnt basics of how to deal with Forks and Merges in GitHub.


Corders Mindset: 
I am improving every day, but still lots of ways to go.

Testing & TDD: 
So far still no actual clue. Will do the tuts now and hope to get a better understanding then.

Debugging: 
So much to learn but am improving every day. 

Ruby Webapps: 
Not much I know here. I have done the Singing with Sinatra tutorial (parts 1 and 2) but that's about it.

Active Record: 
Feeling okay so far.

HTML & CSS: 
Love.


____________________________________________________________________


Phase 2 Day 2

| Coders Mindset | Testing & TDD | Debugging   | Ruby Webapps | ActiveRecord | HTML & CSS   |
| -------------- | ------------- | ---------   | ------------ | ------------ | ----------   |
|  :punch:		 | :bow:		 | :clap:	   |:raised_hand: | :raised_hand:| :heart:		|


Today, I spent a lot of time with Rspec tutorials. They helped me, "the fog is sloooowly lifting".
We built a note-taking app and deployed it to Heroku and built our release one from scratch. Did not get it on Heroku unfortunately, need to look into Heroku and Postgres.


Corders Mindset: 
I am improving every day, but still lots of ways to go.

Testing & TDD: 
Getting an idea of the Syntax of Rspec. Obviously, I can see the reasons for using it. Sometimes difficult to decide WHAT to test for.

Debugging: 
Today, I felt like I did a pretty good job at debugging (except Heroku).

Ruby Webapps: 
Built and deployed the note-taking app (morning challenge). Team Schnitzel 

Active Record: 
Feeling okay so far.

HTML & CSS: 
Love. We took the time to apply some markup and styles to our release 1!


____________________________________________________________________


Phase 2 Day 3

| Coders Mindset | Testing & TDD | Debugging   | Ruby Webapps | ActiveRecord | HTML & CSS   |
| -------------- | ------------- | ---------   | ------------ | ------------ | ----------   |
|  :punch:		 | :bow:		 | :clap:	   | :bow: 		  | :raised_hand:| :heart:		|


Never use require_relative in config.ru.
Never use require_relative in config.ru.
Never use require_relative in config.ru.
Never use require_relative in config.ru.
Never use require_relative in config.ru.
Never use require_relative in config.ru.
Never use require_relative in config.ru.
Never use require_relative in config.ru.
Never use require_relative in config.ru.
Never use require_relative in config.ru.
Never use require_relative in config.ru.
Never use require_relative in config.ru.
Never use require_relative in config.ru.
Never use require_relative in config.ru.
Never use require_relative in config.ru.
Use require instead.

This _relative made us – Team Schnitzel – rewrite the first release of our app. Twice. 

require './our_app'
run Sinatra::Application
# `run` is a method that tells the rack server
# to dispatch HTTP Requests to the rack specified.


Also, Heroku runs on Postgresql, so why not use PG in development too? We did that in our latest rewrite and it worked nicely. 

Release 01 is simple, but we sure as hell learned a looot.


____________________________________________________________________


Phase 2 Day 4

| Coders Mindset | Testing & TDD | Debugging   | Ruby Webapps | ActiveRecord | HTML & CSS   |
| -------------- | ------------- | ---------   | ------------ | ------------ | ----------   |
|  :punch:		 | :clap:		 | :clap:	   | :bow: 		  | :raised_hand:| :heart:		|


Today, I fell for TDD. We tdd'ed our way through the beginnings of http://en.wikipedia.org/wiki/Conway's_Game_of_Life, switched pairing partners a bunch of times, deleted everything we had written and started from scratch. Awesome. 

Team Schnitzel implemented TDD, too. Sick.

Evening lecture by @quackingduck was inspiring as hell:

"Write programs that do one thing and do it well. Write programs to work together." 
– Unix philosophy

