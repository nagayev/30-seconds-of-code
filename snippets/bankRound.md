---
title: bankRound
tags: math,beginner
---

Bank rounding (to the nearest even number).

```js
const bankRound = (n) => {
 n=Math.trunc(n);
 if(n%2===0) return n;
 return n+1;
};
```

```js
bankRound(1.5); // 2
bankRound(2.5); // 2
```
