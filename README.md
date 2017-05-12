# casperscreen

A simple casperJS script that take screenshots from a given url in fullpage and at theses viewport sizes : 
[320,480],
[320,568],
[600,1024],
[1024,768],
[1280,800],
[1440,900]


## usage 

You need to have PhantomJS and CasperJS installed.

```
casperjs casperscreen.js url savedir
```

if savedir argument is omitted, screenshots will be saved in a folder based on url.
