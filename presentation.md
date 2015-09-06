# Javascript World Domination ?

---

# Dentist
# Nurse
# Developer

---

# Software developer is the #3rd Best Job 2015

> The U.S News top 3 Best Jobs

---

# Not surprised

## Just proud to read

---

# 11

---

# 1999

---

## rue montgallet
## Windows 98

---

# Segmentation Fault

> WTF !!??!

---

# coding === knitting

---

# Give me a R&D intership

> No !

---

# Airbus
## 9 Years

---

# C# and .NET

---

# Application in browser

> WTF !!??!

---

# C → C++ → Java
# Ruby → PHP → JavaScript

---

# I wanna be a Project Manager

---

# Coding for Money

---

# 92 Bond Street

---

## Android Apps
## Affiliation
## Bots
## Leboncoin...

---

# Synthesio

---

## Captain

## Best Practices Evangelist
## Happiness Coder and Bugs tracker

---

# Success stories

---

## Facebook
## Google
## Airbnb
## Blablacar
## Slack...

---

# Artis(t)an

---

# Forget the guy with a pen in his shirt pocket.

---

# Web Application Archirectures

---

## JS World domination
## Modern Front-End tools
## Archirectures
## API Rest

---

# Github

> https://github.com/92bondstreet/web-application-architectures

---

# Ready for a job

> Node.js !== programming language

---

# JavaScript Ecosystem

---

# uncopyrighted

> Make a milion dollars if you want

---

# Web

---

# Post Facebook wall

---

# Car itinerary
## Google Maps

---

# The root ?
# The resolver ?

---

# 40 %

> 3 billions in 2014

---

# Device consumer

---

# Internet connection

---

# Open a browser

## with a specific website address

---

# Google search

---

# Send a message
### Gmail
### Facebook
### Twitter
### Instagram

---

# Buy the last bestseller
## on Amazon

---

# 10

---

# 1. The surfer

---

# 2. The Cloud?

> Internet is not {a, in, the} cloud

---

# 2. The wire

---

## Server directly connected to Internet.

---

## address IP

name | IP
---- | --
google.fr | 216.58.208.227
github.com | 192.30.252.130
leboncoin.fr | 193.164.197.82
esilv.fr | 194.254.135.68

---

## bla bla bla... TCP/IP

---

# 3. The Rules

## Internet talk

---

# 4. The Client

## Not directly

---

# 5. The Provider

## Free \o/

---

# 6. The DNS

---

## Dictionnary

---

## OS
## Browser Cache

---

# 7. The resolver

---

## Where is (G)Root?

---

# 8. The Message

---

# 9. The Packet

---

## Split !

---

# 10. The router

---

## Le petit poucet

---

# Application

## App

---

# Desktop

---

# Software

## program

---

# Browser

---

# Full interactive experience

---

# New software ?

---

# SAAS

> Software As A Service

---

# Web Site

---

# Static

---

# Passive eXperience

---

# Resident WWW

---

# Active
# Interaction

---

# Single task

---

# Data anywhere

---

## my or not devices

---

# Application up to date

---

# Everywhere

---

# PC, MAC ?

## It does not matter

---

# My or not browser

---

# Safe

---

# Les 3 frères

---

# Browser

---

## Minimalist

```html
<!DOCTYPE html>
<html>
  <head>
  </head>
  <body>
  </body>
</html>
```

---

# DOM TREE

---

```html
<html>
  <head>
  </head>
  <body>
    <p>How browser works</p>
    <div>
      <span>with DOM and CSS tree</span>
    </div>
  </body>
</html>
```

---

## `<html>` - HTMLHtmlElement
## `<body>` - HTMLBodyElement
## `<p>` - HTMLParagraphElement
## `<div>` - HTMLDivElement
## `<span>` - HTMLSpanElement

---

# Render Tree

> Render tree = Dom Tree + Style Structure

---

# Layout

## Size
## Position

---

# Painting

---

# HTML

---

# Doctype

## Start with a proper doctype declaration for browsers


```html
<!DOCTYPE html>
```

---

# Encoding

## Use UTF-8 for internationalization

```html
<meta charset="utf-8">
```

---

# Indentation

## Indent nested and child elements

```html
<div class="tweet">
	<a href="path/to/somewhere">
</div>
```

---

# Naming

## Name class and id with meaning

```html
<div class="top light" id="tweet-list">
```

---

# Lower case

## Lower case for tag and attribute

```html
<div class="top" id="header" attribute="value">
```

---

# Close tag

## Comment to indicate closing elements

```html
</div> <!-- Facebook post list -->
```

---

# Double quotes

## Double quotes on attributes value

```html
<img src="path.png" alt="Logo">
```

---

# Reducing markup

## Simple DOM design: less is more in markups using

```html
<!-- Not so great -->
<span class="avatar">
	<img src="...">
</span >

<!-- Better -->
<img class="avatar" src="...">
```

---

# CSS

---

# Selectors

---

## Right to left and broad as possible.

```css
a.nav {
  color: blue;
}
```

---

# Blocks

---

## Use multi-line blocks and combination

```css
.someDiv {
  background: red;
  padding: 2em;
  border: 1px solid black;
}

h1, h2, h3 {
  font-family: tahoma;
  color: #333
}
```

---

# Comments

## Use comments to denote groups.

```css
/* Here's how you comment CSS */
```

---

# Whitespace

## Put before and after each style block.

```css
a.nav {
  color: red;
}

.some-class {
  background: @purple;
}
```

---

# Naming conventions

---

## Use meaningful class and id names

```css
.link.first {
  color: red;
}
```

---

# Reset

## Consistent in all browsers.

```css
<link rel="stylesheet" type="text/css" href="reset.css" />
```

---

# Structure

## a Top-down Structure.

```css
/* Generic classes */
Style goes here...

/* Header */
Style goes here...

/* Content */
Style goes here...
```

---

# Multiple classes

## Add multiple classes to an element.

```css
div class="box right"></div>
```

---

# Shorthand

## Combine styles in one line.

```css
#box {
  margin: 8px 7px 0px 5px; // top, right, bottom, and left values, respectively.
}
```

---

# Alphabetize your Properties

---

## Improved readability

```css
#cotton-candy {
  color: #fff;
  float: left;
  font-weight:bold;
  height: 200px;
  margin: 0;
  padding: 0;
  width: 150px;
}
```

---

# Generic classes

---

## Create generic classes to readability

```css
.left {
  float:left
}

.right {
  float:right
}
```

---

# Use Multiple Stylesheets

---

## Make smaller and css multiple files.

```css
<link rel="stylesheet" type="text/css" href="reset.css"/>
<link rel="stylesheet" type="text/css" href="style.css"/>
<link rel="stylesheet" type="text/css" href="widget.css"/>
```

---

# Javascript

> The World's Most Used Programming Language

---

# Web app programming objective

---

## Flexible
## scalable
## reusable
## maintenable
## readable

---

# * able

---

# Programming language

> `Java`, `.Net`, `PHP`, `Ruby`, `Python`, `Go`...etc.

---

# JavaScript is over

---

# Every browsers support it

----

# browser and a text editor

----

# No need SDK or Framework

---

# Everything could be done

---

# 1995

> by Brendan Eich (Netscape former)

---

## LiveScript
## JavaScript

---

# Java !== JavaScript

---

# Ecma International

---

# Last major - 6th

## ES6
## ECMAScript 2015

> (After 6 years of stability for ES5).

---

# Doctor

---

# Save ? No. Refresh !

---

# SPA

> Single Page Application

---

## together but independently

> Gmail.

---

# client + {CMS, APP} + API + firewall + Datastore  

---

# in 1 Tweet

---

# Nearly everything in JavaScript is an object, including functions.

---

# OO

> JavaScript is an object oriented dynamic language with types and operators, standard built-in objects, and methods.

---

# The types

---

## Number
## String
## Boolean
## *Symbol (new in ES6)*
## Object
## null
## undefined

---

## Function
## Array
## Date
## RegExp

---

# Number

> double-precision 64-bit format IEEE 754 values

---

# + - / * % ** ++ -- +=

---

# built-in Number objects

---

# Math

```js
Math.sin(3.5);
```

---

# parse *

---

```js
parseInt("33 years old")
```

---

# Infinity and NaN

```js
isFinite(1/0); // false
isFinite(-Infinity); // false
isFinite(NaN); // false
```

---

# String

> Strings are sequences of Unicode characters (16-bit number).

---

```js
'Javascript on the rock.'
```

---

# Give me the length

```js
'Javascript on the rock.'.length; // 23
```

---

# Yes. String is object too.

```js
'Javascript on the rock.'.replace('Javascript, Yassine');
// Yassine on the rock.

'js'.toUpperCase();
// 'JS'
```

---

# Boolean

> The famous `true` and `false`

---

## with `&&`, `||` and `!` operators.

---

# Variables

## `var` keyword
### `let` and `const` for ES6

---

```js
var school;
var course = 'Web App Architectures';
```

---

# null

> Declared value with a deliberate non-value.

---

```js
var school = null;
```

---

# undefined

> Nothing has been assigned.

---

```js
var school;
```

# Control Structures.

> The same as `C` with conditional statement and loop.

---

# Conditional statement

---

## The traditional `if`

```js
var mercato = 'om';

if (job === 'psg'){
  return 'di-maria';
} else if (job === 'om'){
  return 'bye bye bielsa';
} else {
  return 'martial wtf !!?';
}
```

---

##  `&&`, `||` and ternary operator:

```js
var name = school && school.getName();

var name = school.getName() || 'esilv';

var who = school.getName() === 'esilv' ? 'engineering' : 'management';
```

---

# The traditional `switch`

> `switch` statement can be used with number or string

---

```js
switch(action) {
  case 'render':
    renderHeader();
    break;
  case 'update':
    updateContent();
    break;
  default:
    renderEverything();
}
```

---

```js
switch(id) {
  case 1:
    renderHeader();
    break;
  case 2:
    updateContent();
    break;
  default:
    renderEverything();
}
```

---

# Loops

```js
for (var i = 0; i < 5; i++) {
  // excute 5 times
}
```

---

# Objects

---

# Object is a simple unordered collection of name-value pairs.

---

## The more basic way

```js
var myObj = {};
```

---

# property (and methods)

```js
var mySchool = {'name': esilv};
```

---

```js
var mySchool = {
  'name': 'esilv',
  'details': {
    'town': 'La défense',
    'creation': '1995'
  }
};
```

---

# Getter

```js
var name = mySchool.name;
var town = mySchool.details.town;
var date = mySchool.['details'].['creation'];
```

---

# Setter

```js
mySchool.['details'].['creation'] = 'mid 1995';
mySchool.name = 'emlv';
```

---

# Arrays

---

# Arrays is an ordered collection with a property called `length`.

---

# Get / Set

> Each array items can be accessed with `[]`

---

# The more basic way

```js
var myArray = [];
```

---

# Can you fill it ?

---

```js
var languages = ['js', 'php', 'ruby'];
languages.length; // 3

languages = [
  {
    'name': 'php',
    'version': '5.6'
  },
  {
    'name': 'js',
    'version': '6'
  },
  'push everything in array'
]
```

---

# Pushup

```js
languages.push('python');
languages.push(10);
```

---

# for

```js
for (var index = 0, length = languages.length; index < length; index++) {
  // Do something with languages[index]
}
```

---

# functions

> Part of JavaScript core.

---

## The most simple function example

```js
function (x, y) {
  return x + y;
}
```

---

#  0 or more parameters

---

# many statement as you like.

---

```js
function whoAmI(firstName, lastName) {
  var iam = 'nobody';

  if(firstName === 'yassine') {
    iam = firstName + ' ' + lastName;
  }

  return iam;
}
```

---

# Dom selector

> Javascript is today, the only language to manipulate DOM directly in the browser.

---

# Events listener

---

# Render

---

# Interaction

---

# And jQuery ?

> Five main methods in VanillaJS

---

1. `getElementById(idValue)`

1. `getElementsByTagName(tagName)`

1. `getElementsByClassName(className)`

1. `querySelector(cssSelector)`

1. `querySelectorAll(cssSelector)`

> `jQuery` is (just) a (micro) library to help developers to manipulate DOM regardless of Browser.

---

# Create a DOM Element

```js
var link = document.createElement('a');
```

---

# Add a DOM Element

```js
var child = div.appendChild(span);
```

---

# Element style

```js
element.style.color = "#28aadc";
element.style.marginTop = "10px";
```

---

# Some getter and setter

```js
// HTML
var content = element.innerHTML;
element.innerHTML = '<div class="introduction"><p>My JS Tribute</p></div>'

// Class name
var className = element.className;
otherElement.className = 'left';
```

---

# Selector

```js
document.getElementById('introduction');
document.getElementsByTagName('div');
document.getElementsByClassName('.result');
document.querySelector('div.result');
document.querySelectorAll('div.result > li');
```

---

# Javascript

> The World's Most Misunderstood Programming Language

---

# OO Programming

> Abstraction to create models and objects.

---

## Each object can be viewed as an independent little machine with a distinct role or responsibility.

---

## OOP uses several techniques including modularity, polymorphism, and encapsulation.

---

## Class
## Object
## Property
## Constructor
## Polymorphism...

are well known  word in Java, C++, PHP. Also in JavaScript.

---

# Yes

## JavaScript is a object-oriented language.

---

# Precisely a prototype-based language.

---

# Based prototype programming

> Prototype-based programming is an OOP model that doesn't use classes but prototype.

---

# Prototype is the set of object properties.

---

# (Custom) Objects in Detail

---

# Where is my `class` ?

> JavaScript is a prototype-based language and contains no class statement

---

# Defining a class is as easy as defining a function.

```js
var Mention = function () {};
```

---

# Example with `Mention` Object

> `Mention` is the smallest unit to define a message on social network. It means a tweet is a mention, a post is tweet, an instagram post is a mention...

---

# Object vs Object

---

## What the difference between

```js
var mention = {};
```

and

```js
var Mention = function () {};
```

---

# Identity !

---

## The second object `Mention`: an OOP identify with properties and methods.

> The first notation object is a structure.

---

# Constructor

## new

---

```js
var pastMention = new Mention();
var nowMention = new Mention();
```

---

# Adding properties

```js
var Mention = function (author) {
  this.author = author;
};

var mention1 = new Mention('@github');
var mention2 = new Mention('@airbnb');

// Show the author properties of the objects
console.log('author 1 of mention is ' + mention1.author);
// logs "author 1 of mention is  @github"
console.log('author 2  of mention is ' + mention2.author);
// logs "author 1 of mention is @airbnb"
```

---

# Adding methods

```js
var Mention = function (author) {
  this.author = author;

  this.reply = function (from, message) {
    console.log(from + 'replies to ' + this.author )
  }
};
```

```js
var mention1 = new Mention('@github');
mention1.reply('@azzouty');
```

---

# Prototype

> The previous example with `prototype`.

---

```js
var Mention = function (author) {
  this.author = author;
};

Mention.prototype.content = '';

Mention.prototype.reply = function (from, message) {
  console.log(from + 'replies to ' + this.author );
}

Mention.prototype.print = function () {
  console.log(this.author + ' ' + this.content );
}
```

---

## inside the `prototype` property

```js
var Mention = function (author) {
  this.author = author;
  this.content = '';
};

Mention.prototype = {
  'reply': function () {},
  'print': function () {}
}
```

---

# My style

---

```js
var Mention = function Mention(options) {
  this.initialize(options);
}

var prototype = Mention.prototype;
```

---

```js
/**
 * Reply a message to the mention author
 *
 * @param {String} from - author
 * @param {String} message - message to send
 *
 * return {Mention}
 */
prototype.reply = function (fromn message) {
  console.log(from + 'replies to ' + this.author );
  return this;
}
```

---

```js
/**
 * Print and format the mention
 *
 * return {Mention}
 */
prototype.print = function () {
  return this;
}

var mention = new Mention('@github');

mentions.reply('azzouty', 'On the top').print();
```

---

# Inheritance

> Yes, you can create a new Object from an other version.

## `Object.create`

---

```js
var Tweet = function () {
  Mention.call(this); // Call the parent constructor
}

Tweet.prototype = Object.create(Mention.prototype);
Tweet.prototype.constructor = Tweet;
```

---

```js
var Post = function (author, content) {
  Mention.call(this, author, content); // Call the parent constructor
}

Post.prototype = Object.create(Mention.prototype);
Post.prototype.constructor = Post;
```

---

## update the prototype

```js
Tweet.prototype = {
  'numberOfRetweets': 0,
  'favorite': function () {}
}

Post.prototype = {
  'numberOfLikes': 0,
  'like': function () {}
}

var post = new Post('pulv', 'ESILV in top #30');
post.like();
```

---

# Enumerate properties

---

# in

> To find out if a property exists on an object (either as an inherited or an own property)

```js
var tweet = new Tweet();

console.log('author' in tweet); // true
console.log('numberOfRetweets' in tweet); // true
```

---

# hasOwnProperty

> To find out if a property exists on an object and only itself.

```js
var tweet = new Tweet();

console.log(tweet.hasOwnProperty('author')); // false
console.log(tweet.hasOwnProperty('numberOfRetweets')); // true
```

---

# Serialize

```js
var tweet = {
  'author': '@azzouty',
  'content': 'Markdown my new skill'
};

JSON.stringify(tweet);
// "{"author":"@azzouty","content":"Markdown my new skill"}"
```

---

# Deserialize

> `JSON.parse`.

---

# Functions in Detail

---

# function declaration

```js
function reply () {
  // ...
}
```

---

```js
reply(); // Sent

function reply () {
  console.log('Sent');
}
```

---

# function expression

```js
var reply = function () {
  // ...
}
```

---

```js
var TwitterApi = {
  'reply': function () {},
  'retweet': function () {},
  'favorite': function () {}
}
```

---

# Named function expression

```js
var reply = function reply () {
  // ...
}
```

---

# IIFE

```js
(funtion () {
  //... code to execute
})();
```

---

# bind, call, apply

> 911 ??

---

## want call a function with a certain context and/or later

---

```js
var reply = function (arg1, arg2) {
  var str = '<p>' + this.author + ' reply to ' + arg1 + ' with ' + arg2 + '</p>';
  document.body.innerHTML += str;
};

var context = {
  'author': '@substack'
};
```

---

# call

```js
reply.call(context, '@azzouty', 'I understand !');
```

---

# apply

```js
reply.apply(context, ['@azzouty', 'I understand !']);
```

---

# bind

```js
var boundFn = reply.bind(context, '@azzouty', 'I understand !');
boundFn();
```

---

# Closure
## Super power !

---

# Best practices

---

# DRY
## Don't repeat yourself

> Save same code in shared function.

---

# DOT
## Do One Thing

> One method, one thing (well)

---

# KISS
## Keep It Simple Stupid

> If it's *too clever*, come back to fundamentals.

---

# LIM
## Less Is More

> Write just enough code.

---

#  Guidelines

---

# Objects

> Use literal expression for object creation.

```js
var item = {};
```

---

#  Arrays

> Use the literal syntax for array creation and push items

```js
var items = [];
someStack.push('abracadabra');
```

---

# Strings

> Use single quotes `''` for strings

```js
var name = 'Synthesio';
```

---

# Functions

> Camel case and descriptive vocabulary

```js
function sendVerbatim(){};
function getBestPractices(){};
```

---

# Variables

> Always use it and one per line

```js
var company = 'Synthesio';
var item = 0;
var stack = [];
var bestTeam = 'PSG';
```

---

# Equality

> Use `===` and `!==`

```js
if (company === 'Synthesio') {
  ...
}

if (items.length !== 5) {
  ...
}
```

---

# Blocks

> Use braces even for one line

```js
if (test) {
  return false;
}
```

---

# Comments

> Use // for one line and above. Use /* * / for multilines

```js
// Comment to explain code
var type = this._type || default;

/*
* A multiline comment
* to describe functions for example
*/
```

---

# Whitespace

> Set tabs to 2 spaces and be economic

```js

function() {
∙∙var name;
}
```

---

# Semicolons

> Always use it

```js
var bestTeam = 'PSG';
```

---

# Modules

> Always use it to be avoid conflict and scope hits

```js
(
  function()
  {
    ...
  }
)();
```

---

# Inline

> Always use bracket and space in line condition

```js
var variable = (condition) ? then_value : else_value;
```

---

# JSDoc

> Use JSDoc annotations to describe functions

```js
/* Describe the goal function in one sentence
 *
 * @method myFunction
 *
 * @param  {String}   param1      What is the param1
 * @param  {Array}    param2      What is the param2
 * @return {Boolean}  value       What is the return
 */
 myFunction: function(param1, param2) {
   ....
   return value;
 }
```

---

# Early returns

> Early returns promote code readability

```js
// Bad:
function returnLate( value ) {
  var ret;

  if ( value ) {
    ret = "value";
  } else {
    ret = "other_value";
  }

  return ret;
}
```

---

```js
// Good:
function returnEarly( value ) {

  if ( value ) {
  	return "value";
  }

  return "other_value";
}
```

---

# UX, UI

> UX and UI are not buzzwords

---

# Developers
## control performance, SEO, time rendering, bug free, cross-browsing of a web application

---

# user engagement

> in a competitors world

---

# Prototyping

> version 0.0 of your product

---

## Has to work and looks beautiful

> low cost best practice

---

# Notorious big

> The power of *Make it big* gives users a maximum impact.

---

![big](https://d13yacurqjgara.cloudfront.net/users/14135/screenshots/840696/attachments/88215/main3.png)

---

![big](https://d13yacurqjgara.cloudfront.net/users/30252/screenshots/2220708/attachments/412840/Settings_HD.png)

---

# Breathe

---

## Flat color

## Space

---

![Lighten](https://d13yacurqjgara.cloudfront.net/users/13307/screenshots/864910/attachments/92273/Real_Pixels.jpg)

---

![lighten](https://d13yacurqjgara.cloudfront.net/users/399148/screenshots/2231789/attachments/415386/UniDash_FullPixel.png)

---

# Data First

> Providing quickly information to users.

---

![data](https://d13yacurqjgara.cloudfront.net/users/3587/screenshots/2227352/attachments/414148/Day067_-_Smart_Home.jpg)

---

![data](https://d13yacurqjgara.cloudfront.net/users/13825/screenshots/1895986/attachments/323201/real-pixels.png)

---

# Micro Interaction

> But how does it work ?

---

# Motion

---

![motion](https://d13yacurqjgara.cloudfront.net/users/124059/screenshots/976474/gif2.gif)

---

![motion](https://d13yacurqjgara.cloudfront.net/users/532215/screenshots/1796852/rdc_ldp_short-term_v2_animated2.gif)

---

![motion](https://d13yacurqjgara.cloudfront.net/users/3816/screenshots/1040703/stats-animated.gif)

---

# Form

> Boring forms are everywhere

---

![forms](https://d13yacurqjgara.cloudfront.net/users/6410/screenshots/1254439/form-animation-_gif_.gif)

---

![forms](https://d13yacurqjgara.cloudfront.net/users/14827/screenshots/986398/attachments/115047/share.png)

---

# Innovating scrolling

---

![scroll](https://d13yacurqjgara.cloudfront.net/users/25514/screenshots/2121350/delivery_card.gif)

---

![scroll](https://d13yacurqjgara.cloudfront.net/users/44323/screenshots/1340425/drb-coin-animation-2.gif)

---

# Dentist
# Nurse
# Developer

---

# Tools

---

# Artisan ?

## Yes, we are.

---

# once found you can work faster and more efficient

---

# Manifesto for Software Crafmanship

---

## well-crafted software.
## steadily adding value.
## a community of professionals.
## productive partnerships.

---

# Paper and Pen

---

## Take notes.
## Draw.
## Cross out.
## Organize.
## Plan your day.

---

# A good Editor

> A developer without editor is as a TV without colors: it doesn't make sense.

---

# Terminal

---

# Tmux

> Tmux enables from the same terminal screen to run a number of simultaneous and separate terminal instances.

---

# Browser

---

# Dotfiles, aliases and automation

---

# Agile

---

## Individuals and interactions.
## Working software.
## Customer collaboration.
## Responding to change.

---

# You

> Know yourself.

---

## Do something to change your life, your close family and friend, the world.

---

# Thank you
