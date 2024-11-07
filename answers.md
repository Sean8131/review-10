# React Review 1

## Answer 1 Create a Simple Component

```js
const Welcome = <h1>Welcome to React!</h1>
```

## Answer 2 Create a Bigger Component

```js
const HelloWorld = <p>Hello</p><p>section</p><p>World</p>
```

## Answer 3 Create an Image Component

```js
import React from 'react';
import picture from '../assets/images/profile-picture.jpg';

function ProfilePicture() {
  return (
    <img src={picture} alt='The users profile picture' />
  );
}

export default ProfilePicture;

```

## Answer 4 Create a Component that Uses Variables

```js
const name = "John Doe";
const age = "30";

// Write your code here
```

## Answer 5 Is the Code Correct? Components

It should return an h1 that says "Apples" and then a three numbered bullet points that each say "1. Green Apple"

The code should render, but the list won't make much sense.

## Answer 6 Export a Component

```js
// Modify the code below

const TableOfContents = () => {
  return (
    <div>
      <h2>Table of Contents</h2>
      <ul>
        <li>Introduction to Biking</li>
        <li>Chapter 1: Choosing the Right Bike</li>
        <li>Chapter 2: Essential Bike Gear</li>
        <li>Chapter 3: Basic Riding Techniques</li>
        <li>Chapter 4: Maintaining Your Bike</li>
        <li>Conclusion: Enjoying Your Ride</li>
      </ul>
    </div>
  );
  export default TableOfContents;
};
```

## Answer 7 Import a Component

```js
import React from 'react';
import Profile from './Profile.js';
```

## Answer 8 Is the Code Correct? JSX

It should return an h2 element that says "Shopping List", followed by a bullet point, and then three numbered bullet points that say "Apples" "Bananas" and "Oranges"

## Answer 9 Fix the JSX Bugs

```js

function Bio = () => {
  return (
    <div className="intro">
      <h1>Welcome to my website!</h1>
    </div>
    <p className="summary">
      You can find my thoughts here.
      <br></br>
      <b>And <i>pictures</b></i> of scientists!
    </p>
  );
}
```

## Answer 10 Create a Component with a Prop

```js
import React from 'react';

function Greeting(name) {
  return (
    <p>Hello {name}</p>
  );
}

export default Greeting;

```

## Answer 11 Pass a Prop to a Component

```js
import React from 'react';

const App = () => {

function Greeting(name) {
  return (
    <p>Hello {name}</p>
  );
}

export default Greeting;
};
```

## Answer 12 Bain's talk

In an interview (and life), it's important to have energy, be curious, and ask questions. 

