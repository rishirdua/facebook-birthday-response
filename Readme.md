Facebook Birthday Response
=========================
Python script that automatically thanks all users and like their birthday wishes on your timeline


Author
------
Rishi Dua <rishirdua@gmail.com>


How to use
------------
Configure parameters and run the script:
- bday: your birthday as in the following datetime(year, month, day[, hour[, minute[, second[, microsecond[, tzinfo]]]]])
- access_token: Generate one at https://developers.facebook.com/tools/explorer
- like: set true to like posts on your wall
- comment: set true to comment thank you
- message_set: the list of messages from which you want a random message to be selected
- use_filter: if false, replies to every message. Make it false if you are sure every wish posted on your wall is a birthday message
- bdaywords: keywords to respond to. Comment only on posts containing at least one of these words
- proxy settings: proxy settings if you are behind a proxy server


Contribute
----------
- Issue Tracker: https://github.com/rishirdua/facebook-birthday-response/
- Source Code: github.com/rishirdua/facebook-birthday-response
- Project page: http://rishirdua.github.io/facebook-birthday-response


Support
-------
If you are having issues, contact me directly.

License
-------
This project is licensed under the terms of the MIT license. See LICENCE.txt for details


Disclaimer
----------
I wrote this code for fun on my 22nd Birthday (25 August 2014). It was one of the best birthdays thanks to friends and every birthday wish means a lot. My blog has a post about it.

Credits
-------
Idea inspired from a post on quora: http://www.quora.com/What-are-the-best-Python-scripts-youve-ever-written
The code in that post uses FQL which is deprecated after v2.1. This implementation uses Facebook Graph API.
