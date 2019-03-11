# Answers

1.  What is React JS and what problems does it try and solve?
React is a JavaScript library created by Facebook, is a UI Library, and is a tool for building UI components.
React is founded on the idea that DOM manipulation is an expensive operation and should be minimized. It also recognizes that doing optimizing DOM manipulation by hand will result in a lot of "boilerplate" code, which is error-prone, boring and repetitive. 
React solves this by giving the developer a virtual DOM to render to instead of the actual DOM, which it then diffs with the real DOM, and does the minimum number of DOM operations needed to achieve the new state.
This allows you to not have to worry about DOM performance, and you can simply re-render the entire page all the time, as soon as your state changes. This almost always results in much smaller and simpler code base, which leads to less bugs.

1.  What does it mean to _think_ in react?
Thinking in react is breaking down large applications into smaller pieces to it may be reused elsewhere. Basically thinking about component heiarchies.

1.  Briefly describe some of the differences between a Class/Stateful component and a Functional/Presentational component.
Class/Stateful component is stored on it's constructor and is responsible for managing and communicating state. Functional/Presentational component are responsible for rendering like components and UI. Functional doesn't manage it's own state but can revieve state from parent. 

1.  Describe state.
There are two types of data that control a component: props and state. props are set by the parent and they are fixed throughout the lifetime of a component. For data that is going to change, we have to use state.
In general, you should initialize state in the constructor, and then call setState when you want to change it.

1.  Describe props.
Most components can be customized when they are created, with different parameters. These creation parameters are called props
For example, one basic React Native component is the Image. When you create an image, you can use a prop named source to control what image it shows.
