---
id: jxswcinuc8vfxgvgrth8ysj
title: reverseLoops-1
desc: ''
updated: 1648091277643
created: 1648091277643
---

tags: [code.js.reverseLoop]

```javascript
function reverseSentence(sentence) {
  let arr = sentence.split(' ');
  let reverse = [];
  for (let i = arr.length - 1; i >= 0; i--) {
    let currWord = arr[i];
    reverse.push(currWord);
  }
  return reverse.joing(' ')
}
console.log(reverseSentence('I am pretty hungry')); // 'hungry pretty am I'
console.log(reverseSentence('follow the yellow brick road')); // 'road brick yellow the follow'

```
