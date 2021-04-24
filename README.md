# render-prop

## What is 'Render prop'?

The term `render prop` refers to a technique for **sharing code** between React componets using a **prop whose value is a function**.

## Implementation of function as a prop

- Defined function as a prop
  `<User render={(isLoggedIn) => (isLoggedIn ? "Mirage" : "Guest")} />`

- Calling function as a prop
  `return <div>{this.props.render(true)}</div>;`

## Sharing a functionality in components

- Counter.js has common functionality
- Two components ClickCounter.js and HoverCounter.js have shared common functionality from Counter.js
