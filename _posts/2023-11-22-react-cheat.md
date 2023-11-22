# Components

Components are JavaScript functions that return markup. [JSX](https://react.dev/learn/writing-markup-with-jsx) markup is common.

```js
function AboutPage() {
  return (
    <>
      <h1 className="myFavClass">About</h1>
      <p>Hello there.<br />How do you do?</p>
    </>
  );
}
```

Component names start with a capital letter. HTML tags are lowercase.

CSS styles are specified with `className` (rather than HTML `class`). For example: `<img className="avatar" />`.

Use curly braces to reference the JavaScript in your JSX markup.

```js
return (
  <h1>
    {user.name}
  </h1>
);
```

```js
return (
  <img
    className="avatar"
    src={user.imageUrl}
  />
);
```

https://react.dev/learn

https://transform.tools/html-to-jsx
