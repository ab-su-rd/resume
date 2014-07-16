# My Resume
Look at [resume.md](https://github.com/ab-su-rd/resume/blob/master/resume.md) for the markdown version.  

-	base css from: [kevin burke](http://kevinburke.bitbucket.org/markdowncss/)  
-	html generated with [pandoc](http://johnmacfarlane.net/pandoc/)  
	```bash
	pandoc -f markdown -t html5 -S -c resume.css resume.md > resume.html
	```
-	pdf generated via Chrome's print to pdf  

*not completely automated*  
css markup still needs to be added into generated html.
