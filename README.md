# Serverless Micro Frontend Architecture

A Journey for Beginning Serverless Micro-Frontend Architecture Powered by Vanilla Javascript ES6+.

Interesting Articles:
1. [Does ES6 make JavaScript frameworks obsolete?](https://stackoverflow.blog/2021/11/10/does-es6-make-javascript-frameworks-obsolete/)
2. [Framework Benchmark](https://krausest.github.io/js-framework-benchmark/current.html)

## Keep clean and clear with Easy Learning Curve
Guidelines :
1. Always Debug Using DevTools :
   ![image](https://github.com/vanillajskit/vanillajskit.github.io/assets/11188109/b728d0c1-f610-4baf-ac72-29688730fde1)
2. Always use Javascript ES6+ type=Module in your HTML
   ```html
   <script src="./app.js" type="module"></script>
   ```
3. Use [HTML 5](https://www.tutorialspoint.com/html5/index.htm) instead to simplified your script.
   Example using HTML5 event onclick, calling a function with name PostSignUp() in JS module.
   ```html
   <button class="button is-link is-light" type="submit" id="button" onclick="PostSignUp()">Submit</button>
   ```
   Declare your function in js module, so HTML5 can call the PostSignUp function.
   ```js
   import PostSignUp from "./postfunction.js";
   
   window.PostSignUp = PostSignUp;
   ```
5. Need NPM Package? Just use [skypack](https://www.skypack.dev/)
   ```html
   import confetti from 'https://cdn.skypack.dev/canvas-confetti';
   confetti();
   ```

## Cheat Sheet and Library

Library List :
1. [JSCroot](https://jscroot.github.io/)
2. [C-Craft](https://c-craftjs.github.io/)
