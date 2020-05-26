# File to maintain notes

- NPX
  - an npm package runner that came with npm@5.2.0
  - allows you to use local dev dependencies instead of globally installed, similarly to virtualenv for python
  - can test node commands on different node versions without nvm and other version managers

- Super
  - you need to always call super when defining the ocnstuctor of a subclass
  - react compononent classess that have a constructor should start with a super(props) call
  
- States
  - try to keep the state in the parent component for less confusion, which in this case is the board component
  - you can share the state between children by passing it down from the parent
  - the .slice() method creates a copy of an array to modify it --> immutability

- Immutability
  - two approaches to changing data
    1. mutate the data by directly chaning the data's values
    2. replace the data with a new copy
  - immutability makes complex features much easier to implement like game history or future history
  