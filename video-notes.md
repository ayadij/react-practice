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




Redux
JSX







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



import React, {component} from ‘react’;



event handler,


We want the most parent component to be responsible for fetching data


