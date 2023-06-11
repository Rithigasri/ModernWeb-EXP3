# EXPERIMENT 03: CREATE A WEBLAYOUT USING FLEXBOX
## AIM:
To create a weblayout using flexbox.
## ALGORITHM:
1. Create a html document.
2. Set the body element to display as a flex container with a column direction and a minimum height of 100% of the viewport.
3. Style the header, nav, main, and footer elements with desired background colors.
4. Use flexbox properties to arrange the elements within the nav and main sections, such as justify-content, align-items, or flex property.
5. Assign varying background colors to the left-section and right-section elements within the main section.
6. Apply additional styling to elements as needed, such as padding, margin, or text alignment.

## PROGRAM:
### flexbox.html
```
<!DOCTYPE html>
<html>
<head>
  <link rel="stylesheet" type="text/css" href="flexbox.css">
</head>
<body>
  <header>
    <h1>Website Header</h1>
  </header>
  <nav>
    <ul>
      <li><a href="#">Element 1</a></li>
      <li><a href="#">Element 2</a></li>
      <li><a href="#">Element 3</a></li>
      <li><a href="#">Element 4</a></li>
    </ul>
  </nav>
  <main>
    <section class="left-section">
      <h2>Left Section</h2>
      <p>Add content.....</p>
    </section>
    <section class="right-section">
      <h2>Right Section</h2>
      <p>Add content.....</p>
    </section>
  </main>
  <footer>
    <p>© 2023 My Website. All rights reserved.</p>
  </footer>
</body>
</html>

```
### flexbox.css
```
body {
    display: flex;
    flex-direction: column;
    min-height: 100vh;
    margin: 0;
  }
  
  header {
    background-color: #e5f1ff;
    padding: 20px;
  }
  
  nav {
    background-color: #c3e6cb;
    padding: 10px;
  }
  
  nav ul {
    list-style-type: none;
    display: flex;
    justify-content: space-around;
    margin: 0;
    padding: 0;
  }
  
  nav ul li {
    flex: 1;
    text-align: center;
  }
  
  nav ul li a {
    text-decoration: none;
    color: #000;
  }
  
  main {
    flex: 1;
    display: flex;
    justify-content: space-between;
    background-color: #f8d7da;
    padding: 20px;
  }
  
  .left-section {
    flex: 1;
    background-color: #f5c6cb;
    padding: 10px;
  }
  
  .right-section {
    flex: 1;
    background-color: #ffeeba;
    padding: 10px;
  }
  
  footer {
    background-color: #343a40;
    color: #fff;
    padding: 10px;
    text-align: center;
  }
  
```
## OUTPUT:
![image](https://github.com/Rithigasri/ModernWeb-EXP3/assets/93427256/de45f31e-449f-45b4-810c-2be8a9c0df3f)
## RESULT:
Thus, a weblayout is created using flexbox.
