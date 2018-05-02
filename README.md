# Handy JS Snippets for javascript (react, typescript, etc)

Some often used shortcuts by the team.

## Available shortcuts

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

- `jester`

Quickly scaffold out test describe block with `it` statement.
You may TAB through this code to traverse describe, it, and `//test`.

```javascript
describe('', () => {
  it('should...', ()=> {
    // test
  });
});
```

## Installation

- Toggle the command palette (⌘ ⇧ p) and start typing `vsix`. 
- Select the command  `Extensions: Install from VSIX`. 
- Choose the location of the .vsix file.
- Allow the window to reload

## Contributing

Please do! PR's would be good, but I doubt anyone will ever read/see this, anyway.