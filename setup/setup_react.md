
 ## Set up React
 - 1) static HTML page and rendering the React and Babel
   - without webpack, babel, node.js
 ```
 <!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8" />

    <title>Hello React!</title>

    <script src="https://unpkg.com/react@16/umd/react.development.js"></script>
    <script src="https://unpkg.com/react-dom@16/umd/react-dom.development.js"></script>
    <script src="https://unpkg.com/babel-standalone@6.26.0/babel.js"></script>
  </head>

  <body>
    <div id="root"></div>

    <script type="text/babel">
      class App extends React.Component {
        render() {
          return <h1>Hello world!</h1>
        }
      }

      ReactDOM.render(<App />, document.getElementById('root'))
    </script>
  </body>
</html>
```
- 2) Create React App
  - ` npx create-react-app react-tutorial `
  - ` cd react-tutorial && npm start `
  - localhost:3000
  -
- 3) create own Webpack
