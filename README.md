META TV
=======

Hacky application for displaying news and stuff running on the monitors where we eat lunch.

Created by: Daniil Pinjuk and Andreas Linn

Setup

	http://nodejs.org/
	install meteor https://www.meteor.com/
	git clone https://github.com/sootn/Meta-TV.git
	cd Meta-TV/
	meteor install
	meteor run
	open http://localhost:3000
	
Log
---
To view log open http://localhost:3000/history.
Every action can be reverted.


Tags
----

To view slideshow filterd by a tag go to http://localhost:3000/tag/{{tag}} where {{tag}} is the tag you want to use.

Use '+' to separate multiple tags like so: http://localhost:3000/tag/{{tag1}}+{{tag2}}+{{tag3}}
