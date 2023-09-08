# Exercise #5 - Flexbox

### Build a webpage layout with a header, main content area, sidebar, and footer using CSS Flexbox.



1. Create an HTML file (index.html) with the following structure (or simply use the ```index.html``` file in this folder):

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
    <link rel="stylesheet" href="styles.css" />
    <title>Flexbox Layout Exercise</title>
  </head>
  <body>
    <header>
      <h1>Header</h1>
    </header>
    <main>
      <section class="sidebar">
        <h2>Sidebar</h2>
        <p>This is the sidebar content.</p>
      </section>
      <section class="content">
        <h2>Main Content</h2>
        <p>This is the main content of the webpage.</p>
      </section>
    </main>
    <footer>
      <p>Footer</p>
    </footer>
  </body>
</html>
```

2. Create a ```style.css``` file and save it in the same folder as the html file. 

3. Edit the ```style.css``` file and use the CSS Flexbox properties to achieve the following layout:

The header and footer should be fixed at the top and bottom of the page, respectively.
The main content area should take up the remaining vertical space between the header and footer.
The sidebar and content sections should be side by side within the main content area.
Customize the styles as you like (colors, fonts, etc.) to make the layout visually appealing.