INTRO

Consolidated links from the Reddit megathread by Adam Lynch:

Please see this link: https://www.reddit.com/r/DataHoarder/comments/krx449/megathread_archiving_the_capitol_hill_riots/


CONTENT

Excel file: Lists all links in seperate sheets. Mainly used to filter, dedupe and archive the links.
Text files:
	parler_riots_links-wget.txt -> You can use this as the download list for wget to download the text and media files with wget.
	washington_riots-youtube-dl.txt -> You can use this as the download list for youtube-dl to download the media files.


NOTE

The washington_riots-youtube-dl is the list with all the links. However, you will get errors from youtube-dl
because youtube-dl won't recognize the page format of the parler links. It'll still download the images and videos in those messages.

Use the parler_riots_links-wget list with wget if you also want to download the pages, not only the media files.
