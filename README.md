# React Review 1

## Instructions

### 1. Create a Simple Component

Write the code for a component called `Welcome` that displays the text `<h1>Welcome to React!</h1>`

### 2. Create a Bigger Component

Write the code for a component called `HelloWorld` that displays `<p>Hello</p>`on one line and `<p>World</p>` on the next

### 3. Create an Image Component

Write the code for a component called `ProfilePicture`, it should:

1. Return an `<img/>` element
2. Set the value for the `src` attribute to `'../assets/images/profile-picture.jpg'`
3. Set the value of the `alt` attribute to `'The users profile picture'`

### 4. Create a Component that Uses Variables

Create a component, it should:

1. Return a `<p>` element with the value of the `name` variable
2. Return a `<p>` element with the value of the `age` variable

Ensure that you use the variables directly in your code, **not** the string values that they point to

```js
const name = "John Doe";
const age = "30";
```

### 5. Is the Code Correct? Components

Is the code example below written correctly?

If you think it is, explain what HTML you expect the `ShoppingList` component to render

If not, explain why you think it's not written correctly

```js
const apple = () => {
  return <li>Green Apple</li>;
};

const ShoppingList = () => {
  return (
    <section>
      <h1>Apples</h1>
      <apple />
      <apple />
      <apple />
    </section>
  );
};
```

### 6. Export a Component

Write the code that would export the `TableOfContents` component

### 7. Import a Component

Imagine you are writing code for a React project with a `components` directory.

Inside the `components` directory there are two files:

```
src
└── components
    ├── Profile.js
    └── Gallery.js
```

Inside `Gallery.js` write the code that would import the `Profile` component from `Profile.js`

### 8. Is the Code Correct? JSX

Is the code example below written correctly?

If you think it is, explain what HTML you expect the `ShoppingList` component to render

If not, explain why you think it's not written correctly

```js
const ShoppingList = () => {
  return (
    <h2>Shopping List</h2>
    <ul>
      <li>Apples</li>
      <li>Bananas</li>
      <li>Oranges</li>
    </ul>
  );
};
```

### 9. Fix the JSX Bugs

Fix the code below so that it doesn't break any JSX rules

There are 4 bugs in the code

```js
const Summary = () => {
  return (
    <div class="title">
      <h1>My Site!</h1>
    </div>
    <p class="description">
      You can find my thoughts here
      <br><br>
      <b>And <i>I</b></i> have plenty of them!
    </p>
  );
}
```

### 10. Create a Component with a Prop

Write the code to create a component called `Greeting`, it should:

1. Return a `<p>`
2. Receive a single prop called `name`
3. Render the word `Hello` followed by the value of the `name` prop

### 11. Pass a Prop to a Component

Copy the `Greeting` component you created in the previous question. Pass the `name` prop to your component with any string value you like

You will nest your `Greeting` component inside the provided `App` component

### 12. Bain Hollister

Name something you took away from Bain's chat this morning.
