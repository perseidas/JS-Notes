| Title  | JS-ObjectOriented           |
|--------|-----------------------------|
| Author | @perseidas                  |
| Status | DRAFT                       |
| Date   | 2017-03-01                  |

**NOTE:** `DRAFT` status is while finishing a course.
At that time this draft would be moved to `COMPLETED`.

---

## 1. Scopes

For single programs running the whole code, we can consider these to have the 'global scope'.

Lexical scoping refers to determining a variable's scope based solely on its position within the textual corpus of code.

A new lexical scope is created each time you create a function definition.

```javascript
var hero = aHero(); // global scope
var newSaga = function() {
   // lexical scope
}
```
> Recall then to always make variables with the keyword `var` declared in the scope we want these variables to live on.

### Lexical scopes vs. In-memory scopes

In-memory scopes are the ones created when running the code (line by line) and are not the same as lexical scopes.

> For each lexical scope there may be many in-memory scopes created during execution, or there may be none (in-memory data stores)

<font color="red">This is some text!</font>

1. Make some notes about JS learning
2. Allow for future referencing.
    * These will most likely be represented by code snippets.

## 2. Closures

continue here...

