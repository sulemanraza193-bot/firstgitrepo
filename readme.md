# Learning with chai aur code

## install

```bash
  npm 
  ```
    npm install chai aur code
    ```
## run
```bash
  npm test
  ```
## test
```javascript
  const { expect } = require('chai');
  const { add } = require('./code');

  describe('add function', () => {
    it('should return the sum of two numbers', () => {
      expect(add(2, 3)).to.equal(5);
    });
  });
  ```

## code
```javascript
  function add(a, b) {
    return a + b;
  }

  module.exports = { add };
  ```
