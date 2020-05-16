### Remember

Answer these on your own, then compare answers as a group

1.  What is React?
  A javascript library that allows us to make dynamic SPA's. //what is an SPA?

2.  What is create-react-app?
  A package build by facebook to facilitate building apps in react and to standardize react apps by centralizing the dependencies.

3.  What is Component Based Architecture?
  Code is split into chunks called components. Makes code highly reusable and easy to debug.

4.  What is JSX?
  Special HTML-like syntax that allows us to write Javascript inside of it.

5.  What is the virtual DOM?
  A virtual copy of the browser DOM stored in memory that React uses to identify changes in the browser DOM in a process called reconcilliation.

6.  What is unidirectional (one-way) data flow?
  Data flows from parent to child.

### Understand

Discuss these questions in pairs if you have a 4-person group

7.  Summarize what happens when you run `create-react-app my-app`
  Create a default blank react application called 'my-app'

8.  Summarize the steps for forking and cloning a repo with an existing React app. How does this process differ from the process of creating a new React app on your laptop?
  1) Fork it
  2) Clone it
  3) Navigate to the directory of your react app
  4) run npm i

9.  Explain what this code does:

```jsx
import React from "react";

const Mentor = props => (
  <div className="mentor-container">
    <h1 className={props.title === "Lead Mentor" ? "lead" : ""}>Tim Biles</h1>
    <ul>
      <li>Fort Worth, TX</li>
      <li>My email address is timbilestimbiles@gmail.com</li>
    </ul>
  </div>
);

export default Mentor;
```

10.  Explain how data is passed from a parent component to a child component.
  

### Apply

Try these on your own, but work together if you start to get stuck.

11.  Use `create-react-app` to create a new React application called `student-directory`

12.  Use the code from `Mentor` above to create a new functional, stateless component called `User` with a list of friends. Hard code the list of friends, do not use state or props.

### Analyze, Evaluate, Create

Discuss these questions as a group

13. What are the benefits and drawbacks of using a tool like create-react-app?

14. Compare and contrast JSX with other templating options, such as those used in Angular or Vue

15. Compare and contrast one-way data flow with two-way data binding.
