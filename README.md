= sqlmap =

sqlmap is an open source penetration testing tool that automates the process of detecting and exploiting SQL injection flaws and taking over of database servers. It comes with a powerful detection engine, many niche features for the ultimate penetration tester and a broad range of switches lasting from database fingerprinting, over data fetching from the database, to accessing the underlying file system and executing commands on the operating system via out-of-band connections.

![Screenshot](https://raw.github.com/wiki/sqlmapproject/sqlmap/images/sqlmap_screenshot.png)

== Installing ==

You can download the latest tarball by clicking [here](https://github.com/sqlmapproject/sqlmap/tarball/master) or latest zipball by clicking  [here](https://github.com/sqlmapproject/sqlmap/zipball/master).

Preferably, you can download sqlmap by cloning the [Git](https://github.com/sqlmapproject/sqlmap) repository:

    git clone https://github.com/sqlmapproject/sqlmap.git sqlmap-dev

sqlmap works out of the box with [Python](http://www.python.org/download/) version '''2.6.x''' and '''2.7.x''' on any platform.

== Usage ==

To get a list of basic options and switches use:

    python sqlmap.py -h

To get a list of all options and switches use:

    python sqlmap.py -hh

You can find a sample run [here](https://gist.github.com/stamparm/5335217).
To get an overview of sqlmap capabilities, list of supported features and description of all options and switches, along with examples, you are advised to consult the [user's manual](https://github.com/sqlmapproject/sqlmap/wiki).

== Links ==

* Homepage: http://sqlmap.org
* Download: [.tar.gz](https://github.com/sqlmapproject/sqlmap/tarball/master) or [.zip](https://github.com/sqlmapproject/sqlmap/zipball/master)
* Commits RSS feed: https://github.com/sqlmapproject/sqlmap/commits/master.atom
* Issue tracker: https://github.com/sqlmapproject/sqlmap/issues
* User's manual: https://github.com/sqlmapproject/sqlmap/wiki
* Frequently Asked Questions (FAQ): https://github.com/sqlmapproject/sqlmap/wiki/FAQ
* Mailing list subscription: https://lists.sourceforge.net/lists/listinfo/sqlmap-users
* Mailing list RSS feed: http://rss.gmane.org/messages/complete/gmane.comp.security.sqlmap
* Mailing list archive: http://news.gmane.org/gmane.comp.security.sqlmap
* Twitter: [@sqlmap](https://twitter.com/sqlmap)
* Demos: [#1](http://www.youtube.com/user/inquisb/videos) and [#2](http://www.youtube.com/user/stamparm/videos)
