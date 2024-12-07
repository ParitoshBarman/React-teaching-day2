# React Class - Day 2 Notes

## Task 1: Create a div Element Using React.createElement
1. *Root Element:* div#root
2. Create a div element with the following specifications:
   - id: "container"
   - class: "main"
   - 3 child elements:
     - h3 element with text: "Learning React"
     - p element with text: "Day 2"
     - button element with text: "Click Me!"

---

## Task 2: Create a div Element Using JSX
1. *Root Element:* div#root
2. Create a div element with the following specifications:
   - id: "container"
   - class: "main"
   - 3 child elements:
     - h3 element with text: "Learning React"
     - p element with text: "Day 2"
     - button element with text: "Click Me!"  
       *Functionality:* Clicking this button should print "button clicked..." to the console.

---

## Task 3: React Application with Components
### Components
1. *Navbar Component*  
   - div with id="navbar" containing:
     - A p element with text: "navbar"
     - A p element with text: "links will be displayed here"

2. *Main Component*  
   - A React.Fragment wrapper containing:
     - A p element with text: "main content"

3. *Footer Component*  
   - div with id="footer" containing:
     - A p element with text: "Footer"

---

## Task 4: React Application with Multiple Components
### Components
1. *App Component*  
   - This component should render the following:

2. *Navbar Component*  
   - A div with a logo on the left side (use an img element).
   - A list of a tags on the right side as links.

3. *Main Component*  
   - Includes the following child components:

4. *Sidebar Component*  
   - Contains multiple MenuItem components.  
     Each MenuItem is a p element with text like: "home", "explore", "categories".

5. *ProductsContainer Component*  
   - Contains multiple ProductItem components:
     - Each ProductItem contains:
       - An img element (use a placeholder image).
       - A p element for the product name.
       - An h3 element for the product price.

6. *Footer Component*  
   - div with id="footer" containing:
     - A list of dummy links.

---

## React Setup Template
```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>React Template</title>
  </head>
  <body>
    <div id="root"></div>
  </body>
  <script src="https://www.unpkg.com/react@18.2.0/umd/react.development.js"></script>
  <script src="https://www.unpkg.com/react-dom@18.2.0/umd/react-dom.development.js"></script>
  <script src="https://unpkg.com/@babel/standalone/babel.min.js"></script>
  <script type="text/babel">
    // My Code goes here;
  </script>
</html>
