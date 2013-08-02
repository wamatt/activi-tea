# activi-tea

a simple demo app based off clound foundrie's node-express-boilerplate. A work in progress.

### Features include:

* Bundling [socket.io](http://socket.io/) and integrating with the [express](https://github.com/visionmedia/express) session store so data can be shared
* Providing premade hooks to [authenticate](https://github.com/bnoguchi/everyauth) users via facebook/twitter/github
* An [assetmanager](https://github.com/mape/connect-assetmanager/) that concatenates/mangles/compresses your CSS/JS assets to be as small and fast to deliver as possible, as well as cache busting using MD5 hashes
* Auto updates of the browser (inline/refresh) as soon as CSS/JS/template-files are changed in order to remove all those annoying “save, tab, refresh” repetitions
* [Notifications](http://notifo.com/) to your computer/mobile phone on certain user actions
* Sane defaults in regards to productions/development environments
* Logs errors to [Airbrakeapp.com](http://airbrakeapp.com/pages/home) in order to track any errors users are encountering
* Auto matching of urls to templates without having to define a specific route (such as, visiting /file-name/ tries to serve file-name.ejs and fallbacks to index.ejs - this is helpful for quick static info pages)

#License

Copyright (c) 2012 Matt Tagg

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the 'Software'), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED 'AS IS', WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

