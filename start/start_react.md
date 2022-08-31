## Prerequisites
- HTML & CSS
- JavaScript
- DOM
- ES6
- Node.js & npm

## Concepts
- Babel, Webpack, JSX, components, props, state, lifecycle

## React
- JavaScript library
  - not a framework
- open-source project created by Facebook
- build UI on the front end
- view layer off an MVC application
- components
  - custom, reusable, build quickly and efficiently 

### Babel
- a javaScript compiler letting us ES6+ in old browsers

### ReactDOM
- provides DOM-specific methods 
- render()
  - = createRoot
  - render DOM nodes
 
### JSX
- javascrip + XML     
` const heading = React.createElement('h1', {claassName:'site-heading'}, 'Hello, React!')`     
= 
` const headeing = <h1 className='site-heading'>Hello, React!</h1>`
- {} :curly braces      
-> variables, functions, properties     
  ```
  const name = 'JeongWu'
  const heading = <h1> Hello, {name} </h1>
  ```
  = `data-` attributes
### Component
#### Simple Component
```
const SimpleComponent = () => {
  ereturn <div>Example</div>
}
```
#### Class Component
```
class ClassComponent extends Component{
  render(){
    return <div>Exmpla</div>
  }
}
```

### Props
- properties
- pass existing data through to the child component
- component cannot change the props
- one way data flow

### State
- can update private data from a componett
- data to be saved and modified without being added to a database
- `this.setState()` : modify state
### virtual DOM
- fast and efficient way of syncing data with the actual DOM
