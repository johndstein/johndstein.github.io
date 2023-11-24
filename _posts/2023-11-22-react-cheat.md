# Components

Components are JavaScript functions that return markup. [JSX](https://react.dev/learn/writing-markup-with-jsx) markup is common.

```
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

CSS styles are specified with `className` (rather than HTML `class`).

Use curly braces to reference the JavaScript in your JSX markup.

```
return (
  <h1>
    {user.name}
  </h1>
);
```

```
return (
  <img
    className="avatar"
    src={user.imageUrl}
  />
);
```

[https://react.dev/learn](https://react.dev/learn)

[https://transform.tools/html-to-jsx](https://transform.tools/html-to-jsx)

# Articles

Understanding re-rendering [https://www.joshwcomeau.com/react/why-react-re-renders/](https://www.joshwcomeau.com/react/why-react-re-renders/)

Solutions for prop drilling [https://blog.logrocket.com/solving-prop-drilling-react-apps/](https://blog.logrocket.com/solving-prop-drilling-react-apps/)

Good conceptual view [https://leewarrick.com/blog/a-guide-to-usestate-and-usereducer/](https://leewarrick.com/blog/a-guide-to-usestate-and-usereducer/)

