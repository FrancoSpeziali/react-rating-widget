# React Rating Widget

![Sample output](./sample.gif)

In this project you will be building a rating widget, but with React.

The widget should work similar to [this example on CodePen](https://codepen.io/depy/pen/vEWWdw).

## What you will be doing

You will be working with:

- handling events in React (click, hover)
- handling state in React
- styling React components
- testing your logical thinking!

This project assumes you've already had experience with:

- React Basics
- create-react-app
- React Components
- Handling state in React
- Handling styles in React

## Expectations

✔ Change the design if you like (for example, colours, dimensions or layout). You **do not** have to match the design 100%. Be creative!

✔ Separate your code into components

✔ You can use functional or class based components, or both

✔ You can use functional or class based components, or both

## Requirements

The rating widget should have the following functionality:

✔ The rating widget should give the user the option to give a rating from 1 to 5

✔ The ratings should be visualised with a list of icons

✔ Each of these icons should have 2 states, "active" and "inactive"

✔ When the user clicks on an icon, it should make that icon and all previous icons "active", and all following icons "inactive"

## Getting Started

Create a new project folder, using `create-react-app`

Use a folder name of your choice

[How to use create-react-app](https://reactjs.org/docs/create-a-new-react-app.html#create-react-app)

### Step 1 - Initial design

It's important to lay a good foundation, or you may find yourself in the future unable to fulfill your tasks easily.

Before you start coding, consider the following:

    - How can you separate the responsibilities in the application?

    - Can you translate these responsibilities into React components?

    - How will you handle state?

1. Setup your component/s

> Hint: Will you build everything in one component? Could you split the responsibilities between subcomponents?

### Step 2 - Designing and rendering the state

Setup and render the state within your component. It should;

- produce 5 icons
- each icon should either be "active" or "inactive"
   
> Keep in mind the following:
> 
> The rating the user can submit is between 1 - 5
> The rating icons will each have a "binary" state - either they will be active or inactive 
> Your state should be a reflection of how the ratings

### Step 3 - Styling

Now the logic is out of the way, we can focus on styling.

Add styles and icons for the rating widget. The ratings should be visualised with a list of icons.

### Step 4 - Adding click events

1. Add a click event to each rendered icon

> Hint: How will you tell your handler function which icon has been clicked on?

2. The click event should call a handler function, which should change the state - and change the rendered output

> Example: The user clicks on icon 3. Icons 1 and 2 and 3 are now "active". Icons 4 and 5 are "inactive"

### Bonus Step 5 - Adding a hover event

When you hover over the  "inactive" icons, it should give you a preview of how the icons might look.

The preview should only be temporary, once the user moves the mouse away from the widget, the original state should be rendered.
