# Open Source GitHub Pages CDN

An **extensive archive** of popular - and less popular - open source projects.

http://viewsource.github.com

## Why?
Why not.

Because this is a community driven resource - unlike the "big" CDNs - we can can add those little projects you love... and when we add a project we take the time to *properly* archive it as far back as possible... jquery v1.0.0 anyone?

## When?
Personally when I'm prototyping a demo on http://jsbin.com or http://jsfiddle.net and I need to pull in some common library or resource then these URLs are just dead simple to remember...

http://viewsource.github.com/jquery/1.6.2/jquery.js

## Small & Fast
GitHub Pages assets are gzip'ed... which can compress the response by as high as 70%!

**Response Headers**  
````
HTTP/1.1 200 OK
Server: nginx/1.0.4
Date: Sat, 16 Jul 2011 12:33:57 GMT
Content-Type: application/x-javascript
Last-Modified: Sat, 16 Jul 2011 12:08:22 GMT
Transfer-Encoding: chunked
Connection: keep-alive
Expires: Sun, 17 Jul 2011 12:33:57 GMT
Cache-Control: max-age=86400
Content-Encoding: gzip
```` 

## Use GitHub for file browsing the CDN
If you go to http://viewsource.github.com/jquery it will redirect you to GitHub to see what versions we've got archived in the CDN! If you navigate down to a specific file (e.g. "1.6.2/jquery.js" at  https://github.com/viewsource/viewsource.github.com/blob/gh-pages/jquery/1.6.2/jquery.js) you will see at the end of the `viewsource.github.com / jquery / 1.6.2 / jquery.js` path there is a little "copy to clipboard" icon. This will copy `jquery/1.6.2/jquery.js` to your clipboard... simply paste that onto the end of `http://viewsource.github.com/` and BAM you've got http://viewsource.github.com/jquery/1.6.2/jquery.js

## Consistent and predictable versioning
We "normalize" the version numbers and remove them from the filenames e.g. `jquery-1.6.js` is archived under `/jquery/1.6.0/jquery.js` - notice the extra `.0` in our folder, this makes switching between versions simple:

http://viewsource.github.com/jquery/1.5.2/jquery.js  
http://viewsource.github.com/jquery/1.6.0/jquery.js  
http://viewsource.github.com/jquery/1.6.1/jquery.js  
http://viewsource.github.com/jquery/1.6.2/jquery.js  

## Dynamic "lastest" versions
A dynamic "latest" version is supported for when you want to test against whatever the most recently released version is in the archive.

http://viewsource.github.com/jquery/latest/jquery.js

## Host your own!
Simply fork this project to host your own GitHub Pages CDN. You will need to fork and then do a commit and push to GitHub before they will setup your GitHub Pages hosting.

## Inspired by
[Github as a CDN - Cache your JavaScripts, Stylesheets, and Web Assets with Github Pages](http://viatropos.com/blog/github-as-a-cdn/)   

[Cached Commons - by Will Norris](http://willnorris.com/2010/10/cached-commons) - has some constructive criticism of http://cachedcommons.org and this approach to building an "Open CDN" on GitHub Pages.

[ScriptSrc.net/](http://scriptsrc.net/)

## Other CDNs
[CDN JS](http://www.cdnjs.com/)

[Google CDN](http://code.google.com/apis/libraries/devguide.html)

[Microsoft CDN](http://www.asp.net/ajaxlibrary/cdn.ashx)

[CachedCommons](http://cachedcommons.org)

