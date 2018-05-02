# Handy JS Snippets for javascript (react, typescript, etc)

Some often used shortcuts by the team.

# console variants
- `log`

Cursor position is located at pipes. Nice for logging `thing: thing`.

```js
console.log('| :', |);
```

- `here`

Great for just marking which line number in which file you've placed this.

```javascript
console.log('***** Here! -> line #XXX in DIR/FILENAME *****');
```

- `tabl`

Console log table for a variable. 

```javascript
console.table()
```

# testing

- `jester`

Quickly scaffold out a test `describe` block with `it` statement.
You may TAB through this code to traverse describe, it, and `//test`.

```javascript
describe('', () => {
  it('should...', ()=> {
    // test
  });
});
```

## Contributing

Please do!