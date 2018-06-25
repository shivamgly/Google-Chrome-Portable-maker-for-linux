# Google Chrome Portable Maker (GCPM) For Linux


GCPM is a tool for making Chrome portable. So, that Chrome can be moved anywhere easily and can be used privately. You can also install more than one Chrome in a Linux system, and their history would not clash.

### Usage 

GCPM requires dpkg-deb (dpkg-deb comes preinstalled in almost every linux OS). 

`Step (1)`: Download GCPM.

`Step (2)`: Download latest Chrome *.deb package from https://www.google.com/chrome/ 

`Step (3)`: Give execution permission to GCPM. By Right clicking and going onto its properties and then clicking on "Allow executing file as program". Or you can do this by executing below command in the directory where GCPM exist.  

```sh
$ exec +x GCPM
```
`Step (4)`: Now move both GCPM file and the Chrome package ( let it be `google-chrome-stable_current_amd64.deb` ) to same folder.

`Step (5)`: Now launch terminal from the directory where these two files are placed and execute GCPM with the Chrome package as argument.
```sh
$ ./GCPM google-chrome-stable_current_amd64.deb
```
`Step (6)`: GCPM will ask you for password enter password for `sudo`.
`After completion you can launch chrome form ChromePortableGCPM folder.`




[//]: # (These are reference links used in the body of this note and get stripped out when the markdown processor does its job. There is no need to format nicely because it shouldn't be seen. Thanks SO - http://stackoverflow.com/questions/4823468/store-comments-in-markdown-syntax)


   [dill]: <https://github.com/joemccann/dillinger>
   [git-repo-url]: <https://github.com/joemccann/dillinger.git>
   [john gruber]: <http://daringfireball.net>
   [df1]: <http://daringfireball.net/projects/markdown/>
   [markdown-it]: <https://github.com/markdown-it/markdown-it>
   [Ace Editor]: <http://ace.ajax.org>
   [node.js]: <http://nodejs.org>
   [Twitter Bootstrap]: <http://twitter.github.com/bootstrap/>
   [jQuery]: <http://jquery.com>
   [@tjholowaychuk]: <http://twitter.com/tjholowaychuk>
   [express]: <http://expressjs.com>
   [AngularJS]: <http://angularjs.org>
   [Gulp]: <http://gulpjs.com>

   [PlDb]: <https://github.com/joemccann/dillinger/tree/master/plugins/dropbox/README.md>
   [PlGh]: <https://github.com/joemccann/dillinger/tree/master/plugins/github/README.md>
   [PlGd]: <https://github.com/joemccann/dillinger/tree/master/plugins/googledrive/README.md>
   [PlOd]: <https://github.com/joemccann/dillinger/tree/master/plugins/onedrive/README.md>
   [PlMe]: <https://github.com/joemccann/dillinger/tree/master/plugins/medium/README.md>
   [PlGa]: <https://github.com/RahulHP/dillinger/blob/master/plugins/googleanalytics/README.md>
