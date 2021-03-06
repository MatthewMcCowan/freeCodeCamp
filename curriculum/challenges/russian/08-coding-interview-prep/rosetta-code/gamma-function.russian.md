---
title: Gamma function
id: 5a23c84252665b21eecc7e76
challengeType: 5
videoUrl: ''
localeTitle: Гамма-функция
---

## Description
<section id="description"> Внедрите один алгоритм (или более) для вычисления функции <a href="https://en.wikipedia.org/wiki/Gamma function">Gamma</a> ($ \ Gamma $) (только в реальном поле). Гамма-функция может быть определена как: <div style="padding-left: 4em;"> <big><big>$ \ Gamma (x) = \ displaystyle \ int_0 ^ \ infty t ^ {x-1} e ^ {- t} dt $</big></big> </div></section>

## Instructions
<section id="instructions">
</section>

## Tests
<section id='tests'>

```yml
tests:
  - text: <code>gamma</code> должна быть функцией.
    testString: 'assert(typeof gamma=="function","<code>gamma</code> should be a function.")'
  - text: '<code>gamma(&quot;+tests[0]+&quot;)</code> должно возвращать число.'
    testString: 'assert(typeof gamma(tests[0])=="number","<code>gamma("+tests[0]+")</code> should return a number.")'
  - text: '<code>gamma(&quot;+tests[0]+&quot;)</code> должен возвращать <code>&quot;+results[0]+&quot;</code> .'
    testString: 'assert.equal(gamma(tests[0]),results[0],"<code>gamma("+tests[0]+")</code> should return <code>"+results[0]+"</code>.")'
  - text: '<code>gamma(&quot;+tests[1]+&quot;)</code> должны возвращать <code>&quot;+results[1]+&quot;</code> .'
    testString: 'assert.equal(gamma(tests[1]),results[1],"<code>gamma("+tests[1]+")</code> should return <code>"+results[1]+"</code>.")'
  - text: '<code>gamma(&quot;+tests[2]+&quot;)</code> должен возвращать <code>&quot;+results[2]+&quot;</code> .'
    testString: 'assert.equal(gamma(tests[2]),results[2],"<code>gamma("+tests[2]+")</code> should return <code>"+results[2]+"</code>.")'
  - text: '<code>gamma(&quot;+tests[3]+&quot;)</code> должны возвращать <code>&quot;+results[3]+&quot;</code> .'
    testString: 'assert.equal(gamma(tests[3]),results[3],"<code>gamma("+tests[3]+")</code> should return <code>"+results[3]+"</code>.")'
  - text: '<code>gamma(&quot;+tests[4]+&quot;)</code> должны возвращать <code>&quot;+results[4]+&quot;</code> .'
    testString: 'assert.equal(gamma(tests[4]),results[4],"<code>gamma("+tests[4]+")</code> should return <code>"+results[4]+"</code>.")'

```

</section>

## Challenge Seed
<section id='challengeSeed'>

<div id='js-seed'>

```js
function gamma (x) {
  // Good luck!
}

```

</div>


### After Test
<div id='js-teardown'>

```js
console.info('after the test');
```

</div>

</section>

## Solution
<section id='solution'>

```js
// solution required
```
</section>
