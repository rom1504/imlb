# imlb
Instant Messaging Logs Base : store and make available all your instant messages

## Problem

Each person use lot of instant messages tools to communicate with their contacts (facebook message, google hangout, wechat, irc, skype, ...). Most of these applications store logs in various format (simple text files, xml, sqlite3 db, ...) in various locations (various directories on your computer, on your phone, in the cloud,...) and with various metadata attached (time, place, people in the conversation, public/private,...).

Being able to access these logs again is often useful but it is not always easy to access them. For example being able to know what you said at what time is pretty hard in these conditions.

## Solution

A solution to this problem that this project want to put in place is importing all these logs in a central personal database and making the data easily available.

That means:
* building importers from the various logs source
* defining a good database schema to store all the information
* building visualizer and other aggregators tools to make the information available

## Related projects

* [PersonalKnowledgeBase](https://github.com/rom1504/PersonalKnowledgeBase) is a more general project that intends to store all the personal data around a person. It might be useful here for the understanding of who are people in a conversation.
