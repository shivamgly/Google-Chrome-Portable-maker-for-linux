# Google Chrome Portable Maker (GCPM) For Linux


GCPM is a tool for making Chrome portable. So, that Chrome can be moved anywhere easily and can be used privately. You can also install more than one Chrome in a Linux system, and their history would not clash.

### Usage 

GCPM requires dpkg-deb (dpkg-deb comes preinstalled in almost every linux OS). 

`Step (1)`: Download GCPM. from here https://raw.githubusercontent.com/shivamgoyal15/Google-Chrome-Portable-maker-for-linux/master/GCPM

`Step (2)`: Download latest Chrome *.deb package from https://www.google.com/chrome/ 

`Step (3)`: Give execution permission to GCPM. By Right clicking and going onto its properties and then clicking on "Allow executing file as program". Or you can do this by executing below command in the directory where GCPM exist.  

```sh
$ chmod +x GCPM
```
`Step (4)`: Now move both GCPM file and the Chrome package ( let it be `google-chrome-stable_current_amd64.deb` ) to same folder.

`Step (5)`: Now launch terminal from the directory where these two files are placed and execute GCPM with the Chrome package as argument.
```sh
$ ./GCPM google-chrome-stable_current_amd64.deb
```
`Step (6)`: GCPM will ask you for password enter password for `sudo`. (The authentication is only required because chrome sandbox must be owned by root)

`After completion you can launch chrome form ChromePortableGCPM folder.`
