# express-pagination
This is a super simple module to provide a pagination helper function in
your views.

## Using It
Add the module 'express-pagination' to your package.json and refresh
your dependencies via npm. 

Set it up in your app via:

```javascript
app.helpers(require('pagination'));

```

or 

```javascript
app.helpers({
  paginate:require('pagination').paginate
});

```

And use it from your view (given the following locals are defined).

!= paginate(count, resultsPerPage, currentPage)

## License 

(The MIT License)

Copyright (c) 2009-2011 Michael Rowden &lt;email adress&gt;

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
'Software'), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED 'AS IS', WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY
CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT,
TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE
SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
