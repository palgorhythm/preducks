[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](https://github.com/oslabs-beta/preducks/pulls)
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)

**preducks** is a visual prototyping tool for developers employing **React** component architecture and **Redux** state management, alongside the comprehensive type checking of **TypeScript**.
In other words, **you can draw prototypes and export React / Typescript code!**

**preducks** allows the user to _visualize_ their application architecture dynamically, employing an _application tree_ and a _real-time component code preview_. The user can create components and load _instances_ of these components, as well as nested HTML elements, onto the canvas. The user can also specify the desired shape of their _Redux store_ and _reducers_, as well as _interfaces_ to describe the desired shape of their data, and connections between their components and the store using _Redux hooks_. This architecture can then be _exported_ as TypeScript application files to be used as a starter template for any repository.

## how to use:

#### creating React components:
To create a new React component, type the name of your component into the _add component_ box and click the _+_ button next to it.\
![create component](/images/createcomponent.PNG)\
\
To add a component as a child of another component, click on the parent component in the list of components, and press the _+_ button next to the component you wish to add as a child. To remove a child from a parent, click on the parent in the list, and press the _-_ button which appears next to the component you wish to remove.\
You will not be able to add a component's parents or 
grandparents as its children.\
![add or remove child](/images/addordeletecomponent.PNG)\
\
To completely delete a component, click on it in the list of components and click the _DELETE COMPONENT_ button.\
![delete component](/images/deletecomponent.PNG)
\
#### creating the Redux store:
Since our app uses TypeScript, we give you the opportunity to create TypeScript interfaces to describe the shapes of the data you wish to use in your Redux store. By default, we allow you to choose from the types _number_, _string_, _boolean_, and _any_. You can specify whether you want a value to be a single value of this type, or an array of these types. Once you define an interface, you will be able to use it as the data type of later values you define along with the default ones we provide.\
To create an interface, type in the name of the interface in the _new interface_ field and press the _+_ button next to it.\
![create interface](/images/createinterface.PNG)\
![add to interface](/images/interfacefields.PNG)\
#### connecting React components to the Redux store:
#### exporting your project:

## running your own version

- **Fork** and **Clone** repository.
- open project directory
- install dependencies

```bash
npm install
```

- run application

```bash
npm start
```

- for development experience

```bash
npm run dev
```

## License

This project is licensed under the MIT License - see the [LICENSE.md](https://github.com/oslabs-beta/preducks/blob/development/LICENSE.md) file for details.
