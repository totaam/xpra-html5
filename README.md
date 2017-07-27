# Xpra HTML5 client

This repository is a clone of the xpra HTML5 client found here:
[xpra.org](https://xpra.org/trac/wiki/Clients/HTML5).
You can also browser the source [here](https://xpra.org/trac/browser/xpra/trunk/src/html5)
through xpra's tracker which has the advantage of showing links for commits and tickets.

Feel free to submit pull requests here, or through xpra's
[bug tracker](http://xpra.org/trac/wiki/ReportingBugs)

To use it, you will need an xpra server, which you can start with:
```
xpra start --bind-tcp=0.0.0.0:10000
```
Then you can just point your browser to port 10000.
For using the latest code in this repository, you will need
to point your browser to the new code instead of the version
shipped with xpra: you can overwrite the xpra version with this lastest code,
or deploy this version to a different web server.

There is also an online version of the current version of the HTML5 client available here:
[current HTML5 client](http://xpra.org/html5/connect.html) (the server not supplied!).

For more information on using xpra, see [xpra usage](https://xpra.org/trac/wiki/Usage)
