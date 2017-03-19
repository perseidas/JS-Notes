| Title  | JS notes                    |
|--------|-----------------------------|
| Author | @perseidas                  |
| Status | DRAFT                       |
| Date   | 2017-01-01                  |

**NOTE:** `DRAFT` status is while finishing a course.
At that time this draft would be moved to `COMPLETED`.

---

## 1. Purpose

1. Make some notes about JS learning
2. Allow for future referencing.
    * These will most likely be represented by code snippets.

## 2. Example

This is an example for writing JS code `app.js` for the JS course

Given:

```javascript
// knockout applyBinding
ko.applyBindings(new ViewModel());
```

and

```javascript
var ViewModel = function() {
  var self = this;

  this.catList = ko.observableArray([]);

  initialCats.forEach(function(catItem){
    self.catList.push( new Cat(catItem) );
  });

  this.currentCat = ko.observable( this.catList()[0] );

  this.incrementCounter = function() {
    self.currentCat().clickCount(self.currentCat().clickCount() + 1);
  };

  this.setCat = function(clickedCat) {
    self.currentCat(clickedCat);    
  }
}
```
## 3. Pensum

This is the list of Udacity courses I've taken to learn JS

### 1. Web development



