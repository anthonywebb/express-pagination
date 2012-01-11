# express-pagination
This is a super simple module to provide a pagination helper function in
your views.

Set it up in your app via:

```javascript
app.helpers(require('pagination');
```
or 
```javascript
app.helpers({
  paginate:require('pagination').paginate
});

```

And use it from your view (given the following locals are defined).

!= paginate(count, resultsPerPage, currentPage)

