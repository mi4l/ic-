[[⇦ Home]](../../README.md)
[[⇦ Career]](../README.md)
[[⇦ Frontend]](./README.md)
_____

# The Entry-Level Web Dev Study Guide
This study guide will hopefully help point you in the right direction when it comes to:
- Figuring out what to study
- Determining growth areas

Let's take a quick look at a mishmash of qualifications from various entry-level positions.  I've gathered these from various job postings from companies like Accenture, Facebook, Deloitte Digital, and smaller start-ups.  

* In-depth knowledge of JavaScript, CSS, HTML, and front-end languages
* In-depth knowledge of Node.js
* Knowledge of REACT tools including React.js, Webpack, Enzyme, Redux, and Flux
* Any AWS experience and knowledge of microservices a bonus
* Experience with user interface design
* Knowledge of performance testing frameworks including Mocha and Jest
* Experience with browser-based debugging and performance testing software
* Excellent troubleshooting skills
* Good project management skills
* Appreciation for UI / UX
* Mobile-first responsive design
* Experience integrating JSON data sources and APIs
* Experience with front-end build tools like, Grunt/Gulp, webpack, CodeKit etc
* A background of writing and deploying code, including experience with version control systems such as GIT & Github
* A snazzy-ass portfolio showcasing your fledgling work
* Working knowledge of Adobe Creative Suite
* Understanding of good Information Architecture
* Willingness to write about web stuff, cool things you’ve figured out, and promotion of your projects
* Ability to thrive in a team environment and behave all human like
* An appreciate for how to communicate constructively with people from non-technical background
* Desire to make projects awesome, regardless of your contribution
* Flexibility and an eagerness to learn the latest approaches & emerging best practices
* Ability to express your ideas constructively within a team framework
* Coachable and willing to learn
* Also willing to teach
* Ability to make designs better
* Appreciation for writing modular, Object-oriented code
* Understanding of team coding & documentation standards
* Solutions driven approach to technical problems
* 1 or more years of experience with Object Oriented JavaScript Frameworks (Prototype JS, MooTools, Dojo, etc.)
* 1 or more years of experience developing applications with HTML/CSS/JS
* Experience with performance debugging and benchmarking
* Experience writing code for UI components
* Bachelor’s degree in Computer Science, Computer Engineering, or related technical discipline (or equivalent experience)
* Capable of maintaining a uniform user experience across multiple devices and browser types
* Ability to rapidly prototype and adjust in response to customer feedback
* Understands how to optimize the delivery of code and assets (e.g., images, fonts) to a browser or device (e.g., lazy loading assets, using CDNs, caching, compression, etc.).
* Strong problem solving and troubleshooting skills.
* Solid coding practices including peer code reviews, unit testing, and a preference for agile development.

The point of showing all of these examples is essentially to say that positions typically ask for a lot on the surface but it only boils down to a couple of important requirements.

## What are the actual requirements?
First and foremost -- years of experience and education rarely/never matter, especially for an entry level position.  Don't be deterred by "needs 2 years of experience" or "must have a bach/masters in computer science".  Companies rarely actually care about that -- it's basically boilerplate that recruiters list out.  Entry-level, associate, junior, and maybe frontend developer positions are all good positions to apply for.  If you're ever unsure, just ask me.

Now for the real requirements:

- Proficiency with basic web technologies (HTML, CSS, JS)
- Experience with Node.js
- Library experience (React, Angular, Vue, Svelte)
- Experience with build tooling (Webpack, Gulp, Grunt, Parcel, Rollup, etc)
- Coachable/willing to learn
- Have some understanding of web performance
- Have some projecct management experience
- Be able to debug web FE issues
- Some very light web security

## What do these requirements mean?
Each of these can be broken down into much simpler groups of subtasks.

### Proficiency with basic web technologies (HTML, CSS, JS)
This is more like a basic proficiency with these technologies.  

#### HTML
- Understand semantic HTML and why it's important
- Understand web accessibility to some degree
- Async/defer for scripts

#### CSS
Be proficient enough at explaining:
- `position` and all of its options
- `display` and all of its options
- `flex` and its options and tertiary APIs
- `grid`
- `float` not sure if they'll ask this anymore but it's worth knowing

#### JS
This is a bit more in-depth but these topics are easy to find information about online.

#### Fundamentals
- control flow (if/else, switch)
- objects, Object constructor (Object.keys, Object.values)
- truthiness
- loops (while, for, for in, for of, do while)
- arrays, Array constructor (Array.from, Array.prototype.map, etc)
- functions and function constructor methods (Function.bind, .call, .apply)
- classes
- hoisting
- execution context
- other data types (Set, Map, WeakMap, Symbol)

##### DOM
- DOM selectors (`getElememtById`, `querySelector`, `querySelecorAll`, etc)
- Document fragments
- Safely updating the DOM
- DOM performance
- Event bubbling/capturing

#### Async
- Promise
- try/catch
- How to make requests/get responses

### Experience with Node.js
Node's powerful.  You can make all sorts of stuff with this from scripts to servers to native apps and much more.  You'll basically want to be able to:

- Make a simple express.js server
- Use build tools
- Use some common APIs (path, fs)

### Library experience (React, Angular, Vue, Svelte)
For this I'd want to know someone had some experience with one of these, and most likely I'd want it to be React.  In the case of React:

- Understanding how props work
- How to make components
- React hooks
- React component lifecycle methods
- React context

There's a lot more to React but for an entry level I'd probably only ask about these topics.

### Experience with build tooling (Webpack, Gulp, Grunt, Parcel, Rollup, etc)
This basically means experience using a JS compiler.  Any of these works, Webpack is easily the most valuable for work.  Parcel's a good one to learn since it's so simple and good for personal projects.

### Coachable/willing to learn
This is basically an ego check.  You don't know much and should be ok with that and willing to learn.  This does not by any means you should let someone patronize you or give others license to be condescending.

### Have some understanding of web performance
Understand:

- How scripts execute in the DOM
- How many resources can be fetched at once 
- Critical path
- Time to first (byte, interactive, paint)

### Have some projecct management experience
This really comes down to being organized and tackling projects one piece at a time rather than being completely scattered brained.

### Be able to debug web FE issues
- Using the network tab
- Understanding when to log and when to use a debugger/breakpoint
- Understanding what error messages mean

### Some very light web security
- XSS attacks
- CSRF
- Script injection

## How to study
This is exhaustive.  You by no means need to know all of this before your first job, but the more you know the better you'll perform during the interview process as well as at work.  Let's go step-by-step.

### Proficiency with basic web technologies (HTML, CSS, JS)

#### HTML
HTML seems simple.  You can make it work easily, but a lot is required to be _good_ at it. **This section will mostly require rote memorization -- make some flash cards.**

At a high level, understanding semantic HTML is the most important HTML-based skill to learn.  Given the ubiquity of presentation libraries in the industry at the moment, you'll find yourself working with HTML by proxy of JavaScript.  This means that you won't be utilizing your understanding the document head or how to defer scripts except in rare instances.

I'd start by studying and understanding [MDN's HTML element reference](https://developer.mozilla.org/en-US/docs/Web/HTML/Element).  You don't have to remember all of these, you'll really only use a few outside of rare occurrences, but I'd specifically endeavor to understand the following:

- `h` tag hierarchy
- the `section` element
- determining when to use lists and when to use `ol` vs `ul`
  - ordered list does not mean it has numbers, it just means it has order -- should sorted collections be an ol?  It's worth understand how to talk about these kinds of philosophical semantics
- when to use an `a` tag vs. a `button` (does it cause a navigation event? no? it's a button)
- not to make non-interactive elements clickable (it's common to see `div` and `td` elements with click handlers -- this is possibly but it is not valid HTML [according to the spec](https://html.spec.whatwg.org/))
- general understanding of the less often used elements (basically anything in the elements list you're unfamiliar with)

Next, I'd look into accessibility.  Accessibility has been around for awhile but it's becoming a skill more companies are looking for.  Plus, making applications accessible to all is the moral thing to do.  When it comes to accessibility I'd learn:

- How to hide elements to a sighted user but not to a screenreader
- How to use labels and associated text inputs (`label` and `input` tags)
- ARIA -- this is a huge topic

I'd go a step further and watch some video courses and do some reading on the subject.

- [Web Accessibility V2](https://frontendmasters.com/courses/accessibility-v2/) -- FEM is my favorite FE video course site, highly recommend a subscription
- [Web Accessibility](https://developers.google.com/web/fundamentals/accessibility) from Google

Finally, I think it's still important to understand what `async` and `defer` do when it comes to the `script` tag as well as some SEO stuff.  Out of all questions available about HTML, this will probably be the one that comes up during an interview.

- `async` and `defer`
- [JSON-LD](https://json-ld.org/)
- [Structured data schemas](https://schema.org/)

Don't go too deeply in JSON-LD and schemas, just know the gist and that they exist.  Remember that HTML is really about remembering stuff.

#### CSS
CSS is mostly simple, but there're some concepts that are core to understanding it and debugging/implementing UIs.  Each of these need to be studied by implementing them and messing with them.

- `position` (absolute, relative, fixed, static, sticky) [MDN](https://developer.mozilla.org/en-US/docs/Web/CSS/position)
- `display` (none, block, inline, inline-block, flex, inline-flex, grid, inline-grid, flow-root) [MDN](https://developer.mozilla.org/en-US/docs/Web/CSS/display)
- `float`

Also endeavor to understand [pseudo elements](https://developer.mozilla.org/en-US/docs/Web/CSS/Pseudo-elements) and [pseudo classes](https://developer.mozilla.org/en-US/docs/Web/CSS/Pseudo-classes).  Pseudo elements specifically help you minimize the amount of HTML elements in the DOM -- you won't nee dto provide as many elements strictly for style reasons.

- `:nth-child`
- `:hover`, `:focus`, `:active`
- `::after`, `::before`

CSS variables, backgrounds, animations, etc, are all worth understanding as well, but  aren't as immediately necessary as the topics above.

#### JS
Improving with JavaScript takes memorization, implementation practice, and a thoughtful approach to understanding how to read code.

##### Reading Code
Reading code is far and away one of the most important skills you'll learn.  You should be able to read line-by-line, expression-by-expression and understand exactly what data you're dealing with at each step of the way.

Say you have a function that receives an argument and accesses some deeply nested data.  Note that this example is extremely contrived, but will hopefully express the importance of this skill.

```js
function accessDeeplyNestedData(data) {
  return data[0].meta.getMetaData()[0].header.title;
}

accessDeeplyNestedData([
  { meta: {
    getMetaData() {
      return [
        {
          header: {
            title: 'Hello world'
          }
        }
      ]
    }
  }}
]);
```

It's important to be able to understand what data is being handled at each step of the way.  Let's try that.

```js
// data[0].meta.getMetaData()[0].header.title
console.log(data); // array
console.log(data[0]); // object
console.log(data[0].meta); // object
console.log(data[0].meta.getMetaData); // function
console.log(data[0].meta.getMetaData()); // array
console.log(data[0].meta.getMetaData()[0]); // object
console.log(data[0].meta.getMetaData()[0].header); // object
console.log(data[0].meta.getMetaData()[0].header.header); // string
```

Why does this help?  Here's a real world example from [Webpack]().  This particular snippet is part of webpack's boilerplate that allows modules to be imported/exported in an environment that doesn't natively support imports/exports.

```js
function jsonpScriptSrc(chunkId) {
  return __webpack_require__.p + "" + ({}[chunkId]||chunkId) + ".js"
}
```

This is nutty looking code.  `__webpack_require__` is a massively complex variable that's in scope.  Breaking this done every action at a time:

`function jsonpScriptSrc(chunkId) {` function with a parameter of `chunkId` -- so far we don't know much about the chunkId type, but if this code is mildly self-documenting we can assume it's either a string or a number given the substring `Id`.


`__webpack_require__.p` access property `p` which seems to be of type `string` given the concatenation.

`({}[chunkId]||chunkId)` an expression that first checks for the chunkId on an empty object, which, unless an object prototype has been updated to include a property mirroring the chunkId, should always return `undefined`.  Then, if falsy, the `||` will offer up the `chunkId` as is.

Finally, Webpack concatenates `.js` to the `chunkId`.  

In practice, this line of code creates a string that's passed in as a `src` argument to a `<script />` tag.  `__webpack_require__.p` could be something like `app.bundle`, with `chunkId` matching an id of some sort (`app.bundle.1ab13e`), and then `.js` finally being concatenated with the bundle source string (`app.bundle.1ab13e.js`).

A lot's going on in that single line of code, but learning how to read and think about each step along the way will greatly help you better understand JavaScript and code in general.

##### Fundamentals
The bread and butter.  Let's get right into it.

###### Control Flow (if/else, switch)
These are pretty straightforward.  Try to minimize control flow in general.  Control flow creates branching paths in code, which means more complexity and more things to support.  Generally it's good to use control flow at a high level since that leaves each branching path in a pretty linear state.

For example, if you have a million if/else statements in your app as you're rendering components or validating data, it's much harder to test and change in the future.  If you have a single if/else or switch near the top level of your app, your testing scenarios are simple and you won't have to work very hard to add another path later, which in the real world could be a new feature.

Some quick tips:

Remember that a return exits a function, so an if/else where the `else` returns doesn't actually need an `else`.  Extremely contrived example:

```js
// This function uses an unnecessary return
function isOdd(num) {
  if (num % 2 === 0) {
    return false;
  }

  else {
    return true;
  }
}

// It should be
function isOdd(num) {
  if (num % 2 === 0) {
    return false;
  }

  return true;
}

// or even better, no control flow at all
function isOdd(num) {
  return !!(num % 2);
}
```

Switches are a little different and essentially act as a switch board.  Cases can be stacked to all lead to the same handler:

```js
switch (action.type) {
  case 'SOME_ACTION_TYPE':
  case 'SOME_OTHER_ACTION_TYPE':
    return handleAction(action);
  // ...
}
```

In this case, if `action.type` is equal to `SOME_ACTION_TYPE` or `SOME_OTHER_ACTION_TYPE`, it'll fire `handleAction` with `action` as the argument.  The `action.type` equality check will cascade until it finds a match, or the `default` case.

A trick one can do to make a `switch` act a bit more like an `if/else` is to use `switch (true)` and then provide expressions in the cases.

```js
function whatIsX(x) {
  switch (true) {
    case (x === 1):
      return 'x is 1';
    case (x === 3):
      return 'x is 3';
    default:
      return 'x is not 1 or 3';
  }
}

whatIsX(1); // x is 1
whatIsX(3); // x is 3
whatIsX(2); // x is not 1 or 3
```

###### objects, Object constructor (Object.keys, Object.values)
Objects are great for storing data.  You can create objects to represent real world data or you can use objects as a look-up table.  

- remember how to access values in an object
- understand how to use an object to store values when working with algorithms

For example, say you need to create a function that lets you know if a string has duplicate characters.  

```js
function hasDuplicateCharacters(string) {
  const characterMap = {};

  for (let i = 0; i < string.length; i++) {
    if (string[i] in characterMap) {
      return true;
    }

    characterMap[string[i]] = true;
  }
}
```

There're many ways to determine whether or not a string has duplicate characters, but in this instance we've used a map to quickly (O1) check to see if we've seen a value before.

The `Object` (capital "O") constructor also offers very helpful static methods.  `Object.keys` and `Object.values` are particularly helpful to understand, but [the more you understand about the constructor](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object), the better.

###### truthiness
###### loops (while, for, for in, for of, do while)
###### arrays, Array constructor (Array.from, Array.prototype.map, etc)
###### functions and function constructor methods (Function.bind, .call, .apply)
###### classes
###### hoisting
###### execution context



### Experience with Node.js


### Library experience (React, Angular, Vue, Svelte)


### Experience with build tooling (Webpack, Gulp, Grunt, Parcel, Rollup, etc)


### Coachable/willing to learn


### Have some understanding of web performance


### Have some projecct management experience


### Be able to debug web FE issues


### Some very light web security





## Resources
Resources from above but all in one place.

- [Web performance basics](https://developer.mozilla.org/en-US/docs/Learn/Performance/What_is_web_performance)
- [HTML Element Reference](https://developer.mozilla.org/en-US/docs/Web/HTML/Element)
- [HTML Spec](https://html.spec.whatwg.org/)
- [Web Accessibility](https://developers.google.com/web/fundamentals/accessibility)
- [Web Accessibility V2](https://frontendmasters.com/courses/accessibility-v2/)
- [JSON-LD](https://json-ld.org/)
- [Structured data schemas](https://schema.org/)
- [CSS Position](https://developer.mozilla.org/en-US/docs/Web/CSS/position)
- [CSS Display](https://developer.mozilla.org/en-US/docs/Web/CSS/display)
- [Pseudo Elements](https://developer.mozilla.org/en-US/docs/Web/CSS/Pseudo-elements)
- [Pseudo Classes](https://developer.mozilla.org/en-US/docs/Web/CSS/Pseudo-classes)
- [Object Constructor](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object)