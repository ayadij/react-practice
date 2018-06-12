# reducers

plain js object
function that returns a piece of the application state
our applications can have many different peices of state, you can have many reducers

reducers produce the value of our state
the reducer is only concerned with the value of the state

so for books, it will produce an array of strings




simple funciton that returns an array of books:
export default function() { 
  return [
    {title : 'Harry Potter 1'},
    {title : 'Harry Potter 2'},
    {title : 'Harry Potter 3'},
    {title : 'Harry Potter 4'}
  ]
}



