# Web-Color-Conversions
All 140 Web Colors in C #defines. Includes the following pixel formats: 888,666,444 ; 565,555,1555 in addition to having an RGB and BGR version

You can find the .h files inside of the WebColors folder

List of pixel formats:
RGB:
	RGB888	: rrrr rrrr gggg gggg bbbb bbbb
	RGB666	:   rr rrrr gggg ggbb bbbb
	RGB444	: rrrr gggg bbbb
	RGB565	: rrrr rggg gggb bbbb
	RGB555	:  rrr rrgg gggb bbbb
	RGB1555	: grrr rrgg gggb bbbb
BGR:
	BGR888	: bbbb bbbb gggg gggg rrrr rrrr
	BGR666	:   bb bbbb gggg ggrr rrrr
	BGR444	: bbbb gggg rrrr
	BGR565	: bbbb bggg gggr rrrr
	BGR555	:  bbb bbgg gggr rrrr
	BGR1555	: gbbb bbgg gggr rrrr

You can check out the terrible code I used to generate the defines here:
https://replit.com/@ZERICO2005/Web-Color-Conversion#
