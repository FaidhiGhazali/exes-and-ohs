# exes-and-ohs

### Check to see if a string has the same amount of 'x's and 'o's.
### The method must return a boolean and be case insensitive.
### The string can contain any char.

```
XO (str) {
  let arr = str.toLowerCase().split("")
  let x = 0
  let o = 0
  for (let i=0;i<arr.length;i++) {
    if (arr[i] === 'x') {
      x++
    } else if (arr[i] === 'o'){
      o++
    }
  }
  return x === o
}
```
