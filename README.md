just a dump of htmls

## how to run these htmls

double-clicking (`file://`) will work here but often will break stuff (like webcam, audio, canvas). htmls that require http will be in their own folder for deploy, these need to be served over http:

### option 1: quick local server
```sh
python3 -m http.server
```
then open http://localhost:8000 in your browser.

### option 2: free hosting
apps that need to be deployed are in folders.  
you can drag those folders onto [Netlify](https://www.netlify.com/) (or similar) and get an instant https:// link.
