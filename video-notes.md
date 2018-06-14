REACT NOTES

How do you tell React to re-render?
this.setState


Class vs. Function (??)



====================================================================
PROPS


STATE
: plain js object that is used to record and react to user events
Each class based component that we define has its own state object
Whenever a components state is changed, the component immediately re renders and also forces all of its children to re render as well


====================================================================


Redux
JSX


====================================================================



Functional component

const SearchBar() = {
  return (
    <div>Hello World!<div>  
  );
}

Class component — when you want the concept of state

class SearchBar extends React.Component {
  render() {
    return <input />           //must return jsx
  }

}


====================================================================

import React, {component} from ‘react’;


====================================================================

event handler,


====================================================================

We want the most parent component to be responsible for fetching data



====================================================================



## Converting a Function to a Class

- You can convert a functional component like Clock to a class in five steps:
- Create an ES6 class, with the same name, that extends React.Component.
- Add a single empty method to it called render().
- Move the body of the function into the render() method.
- Replace props with this.props in the render() body.
- Delete the remaining empty function declaration.

## Convertinga a Class to a Function

- create a function with the same name as the class and pass in props     function ImageModal(props) {}
- create a return function                                                return ();
- move the body of the render method into the return function
- take out all of the `this.props` and replace with just `props`.



