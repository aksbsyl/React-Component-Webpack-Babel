### React-Component-Webpack-Babel
  
1) Babel : Internal compiler inside React that converts E6(2016) to E5(2009 features)
2) webpack: While making projects we have lots of javascript files. Use of webpack is to bundle our files to bundle.js or bundle.css and so on

*Babel and webpack are implemented internally in create react using nodejs.

3) component: A website is composed of components. Components basically is part of user interface. It can be understood as Navbar, body, footer.
 There are two types of components: a) Class based components b) Function based components

a)Function based components 
import React from "react";
import ReactDOM from "react-dom";

//component in React

function App() {
  return <h1> Hello </h1>;
}

ReactDOM.render(<App/>,document.getElementById('root'));
//render is method that comes from ReactDOM. We can pass two parameters here
//first is component(functin based component), second the location where we want to keep our data
 
//We make components in separate files
