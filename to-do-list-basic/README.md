# New things for me:

## Getting Started with Create React App

- create-react-app . ( in a folder that does not contain any spaces in its name )
( "."  --> use the current folder )

- In the project directory, you can run: 
## `npm start`

- It is not allowed to put 2 JSX elements next to each other inside of a return() ( return can only return one thing )
HACK: wrap everything inside of an empty element: <> </>

- STATE: { useState } hook
 useState() returns an array, so we can destructure it.

- { JS code } - Js code can be written into curly braces

- Each child in a list should have a unique "key" prop. It allows REACT to rerender/change single components instead of rerendering all of them every single time

- { useRef } hook 
 allows us to reference elements inside of our JSX

- npm i uuid 
 ( A universally unique identifier (UUID) is a 128-bit number used to identify information in computer systems. )

 - { useEffect } hook
  ( Accepts a function that contains imperative, possibly effectful code. )

  - in React you should never directly modify a STATE variable
   ( we should always create a copy... for example with the spread operator)
    let newArray = [...array];
