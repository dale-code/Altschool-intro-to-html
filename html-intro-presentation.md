# Introduction to HTML
## PowerPoint Presentation Outline

---

## Slide 1: Title Slide
- **Title:** Introduction to HTML & How the Web Works
- **Subtitle:** Building the Foundation of Web Development
- **Instructor:** [Your Name]
- **Date:** [Current Date]

---

## Slide 2: Lesson Objectives
- Understand how the web works (client-server model)
- Learn what HTML is and its purpose
- Understand HTML document structure
- Create a simple webpage using common HTML elements
- Practice proper HTML syntax and formatting

---

## Slide 3: The Internet vs. The World Wide Web
- **Internet:**
  - Global network of interconnected computers
  - Infrastructure that allows computers to communicate
  - Includes email, file transfers, messaging, etc.
- **World Wide Web:**
  - Information system built on top of the Internet
  - Collection of linked resources accessed via URLs
  - Just one "application" that uses the Internet

---

## Slide 4: Client-Server Architecture
- **[IMAGE: Simple diagram showing client and server communication]**
- **Clients:** 
  - Devices that request and display information
  - Web browsers (Chrome, Firefox, Safari)
  - Mobile apps, smart devices
- **Servers:**
  - Computers that store, process, and deliver web content
  - Respond to client requests
  - Host websites, applications, databases

---

## Slide 5: HTTP - The Language of the Web
- **HTTP (Hypertext Transfer Protocol):**
  - Protocol for transmitting web documents
  - Request-response communication pattern
- **Common HTTP Methods:**
  - GET: Retrieve data (loading a webpage)
  - POST: Submit data (forms)
- **Status Codes:**
  - 200: Success
  - 404: Not Found
  - 500: Server Error

---

## Slide 6: URLs and DNS
- **URL Structure:** 
  - **[IMAGE: Diagram breaking down URL parts]**
  - Protocol: `http://` or `https://`
  - Domain: `www.example.com`
  - Path: `/products/item.html`
- **DNS (Domain Name System):**
  - Translates human-readable domain names into IP addresses
  - Acts like the internet's phone book

---

## Slide 7: The Three Core Web Technologies
- **HTML:** Structure
  - Defines the content and organization
  - The "nouns" of the webpage
- **CSS:** Presentation
  - Controls the appearance
  - The "adjectives" of the webpage
- **JavaScript:** Behavior
  - Adds interactivity and functionality
  - The "verbs" of the webpage

---

## Slide 8: What is HTML?
- **HTML = Hypertext Markup Language**
- Markup language for creating web pages
- Uses tags to define elements
- Tells the browser how to structure content
- Not a programming language
- Current version: HTML5

---

## Slide 9: HTML History (Brief Timeline)
- 1991: Tim Berners-Lee creates HTML
- 1995: HTML 2.0 (first standard)
- 1997: HTML 3.2
- 1999: HTML 4.01
- 2000-2014: XHTML and HTML5 development
- 2014: HTML5 becomes official recommendation
- Today: Living standard with ongoing updates

---

## Slide 10: How Browsers Interpret HTML
- **[IMAGE: Browser rendering process]**
- Browser receives HTML from server
- Parses HTML into DOM (Document Object Model)
- Renders content on screen
- Demo: View Source/Inspect Element in browser

---

## Slide 11: Basic HTML Document Structure
```html
<!DOCTYPE html>
<html lang="en">
    <head>
        <!-- Document metadata goes here -->
        <title>Page Title</title>
    </head>
    <body>
        <!-- Content visible to users goes here -->
    </body>
</html>
```

---

## Slide 12: The DOCTYPE Declaration
- Tells the browser which version of HTML to use
- Modern DOCTYPE is simple:
  ```html
  <!DOCTYPE html>
  ```
- Historical DOCTYPEs were more complex
- Without it, browsers may enter "quirks mode"

---

## Slide 13: The `<head>` Section
- Contains metadata about the document
- Not visible on the page itself
- Key elements:
  ```html
  <title>Page Title</title>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="Page description">
  <link rel="stylesheet" href="styles.css">
  <script src="script.js"></script>
  ```

---

## Slide 14: The `<body>` Section
- Contains all visible content
- Everything users see on the webpage
- Text, images, links, forms, etc.
- Organized using various HTML elements

---

## Slide 15: HTML Syntax
- **Elements** defined by tags:
  ```html
  <tagname>Content</tagname>
  ```
- **Attributes** provide additional information:
  ```html
  <tagname attribute="value">Content</tagname>
  ```
- **Self-closing tags** for empty elements:
  ```html
  <img src="image.jpg" alt="Description">
  ```

---

## Slide 16: HTML Element Nesting
- Elements can contain other elements
- Must be properly nested:
  ```html
  <!-- Correct -->
  <p>This is <strong>very</strong> important.</p>
  
  <!-- Incorrect -->
  <p>This is <strong>very important.</p></strong>
  ```

---

## Slide 17: Text Elements - Headings
- Six levels of headings:
  ```html
  <h1>Main Heading</h1>
  <h2>Subheading</h2>
  <h3>Sub-subheading</h3>
  <h4>Sub-sub-subheading</h4>
  <h5>Lower level heading</h5>
  <h6>Lowest level heading</h6>
  ```
- Important for document structure and SEO
- Use only one `<h1>` per page

---

## Slide 18: Text Elements - Paragraphs
- Basic text containers:
  ```html
  <p>This is a paragraph of text.</p>
  <p>This is another paragraph.</p>
  ```
- Browsers automatically add space before and after
- Line breaks within paragraphs:
  ```html
  <p>Line one<br>Line two</p>
  ```

---

## Slide 19: Text Formatting
- **Bold text:**
  ```html
  <strong>Important text</strong>
  <b>Bold text</b>
  ```
- **Italic text:**
  ```html
  <em>Emphasized text</em>
  <i>Italic text</i>
  ```
- Semantic vs. presentational tags
  - `<strong>` and `<em>` have semantic meaning
  - `<b>` and `<i>` are purely visual

---

## Slide 20: Lists
- **Unordered lists:**
  ```html
  <ul>
      <li>Item 1</li>
      <li>Item 2</li>
  </ul>
  ```
- **Ordered lists:**
  ```html
  <ol>
      <li>First item</li>
      <li>Second item</li>
  </ol>
  ```
- **Nested lists:**
  ```html
  <ul>
      <li>Main item
          <ul>
              <li>Sub-item</li>
          </ul>
      </li>
  </ul>
  ```

---

## Slide 21: Links
- Created with anchor (`<a>`) elements:
  ```html
  <a href="https://www.example.com">Visit Example</a>
  ```
- **Absolute URLs:** Full path including protocol and domain
  ```html
  <a href="https://www.example.com/page.html">Link</a>
  ```
- **Relative URLs:** Path relative to current page
  ```html
  <a href="about.html">About Us</a>
  ```

---

## Slide 22: Link Attributes
- **Target attribute:**
  ```html
  <a href="page.html" target="_blank">Opens in new tab</a>
  ```
- **Title attribute:**
  ```html
  <a href="page.html" title="More information">Help</a>
  ```
- **Email links:**
  ```html
  <a href="mailto:contact@example.com">Email Us</a>
  ```

---

## Slide 23: Images
- **Basic syntax:**
  ```html
  <img src="image.jpg" alt="Description of image">
  ```
- **Always include alt text:**
  - Describes image content
  - Used by screen readers
  - Displays if image fails to load
- **Size attributes:**
  ```html
  <img src="image.jpg" alt="Description" width="500" height="300">
  ```

---

## Slide 24: Image Formats
- **JPEG (.jpg):** Photos and complex images
- **PNG (.png):** Graphics, transparent images
- **GIF (.gif):** Simple animations
- **SVG (.svg):** Scalable vector graphics
- **WebP (.webp):** Modern efficient format

---

## Slide 25: Tables
- Used for tabular data:
  ```html
  <table>
      <tr>
          <th>Name</th>
          <th>Age</th>
      </tr>
      <tr>
          <td>John</td>
          <td>25</td>
      </tr>
  </table>
  ```
- **Key elements:**
  - `<table>`: Container
  - `<tr>`: Table row
  - `<th>`: Table header
  - `<td>`: Table data cell

---

## Slide 26: Semantic HTML5 Elements
- Give meaning to page structure:
  ```html
  <header>Site header</header>
  <nav>Navigation menu</nav>
  <main>
      <article>Main content</article>
      <aside>Related info</aside>
  </main>
  <footer>Site footer</footer>
  ```
- Better for accessibility and SEO
- Clearer code organization

---

## Slide 27: Common HTML Attributes
- **id:** Unique identifier
  ```html
  <div id="unique-element">Content</div>
  ```
- **class:** Categorizes elements
  ```html
  <p class="highlight">Content</p>
  ```
- **style:** Inline CSS
  ```html
  <p style="color: blue;">Blue text</p>
  ```

---

## Slide 28: HTML Comments
- Not visible on the webpage
- Helpful notes for developers
  ```html
  <!-- This is a comment -->
  
  <!-- 
      Multi-line
      comment
  -->
  ```

---

## Slide 29: HTML Validation
- Why validate HTML?
  - Ensures standards compliance
  - Finds errors and bugs
  - Improves accessibility
- W3C Markup Validation Service:
  - https://validator.w3.org/

---

## Slide 30: Practical Exercise
- Create a simple personal webpage including:
  - Heading with your name
  - Paragraph about yourself
  - List of interests/hobbies
  - Link to a favorite website
  - Image with proper alt text
- Use proper HTML structure and indentation

---

## Slide 31: Developer Tools Demonstration
- **[IMAGE: Browser with developer tools open]**
- Viewing page source
- Inspecting elements
- Editing HTML live in the browser
- Viewing network requests

---

## Slide 32: Next Steps
- Learn CSS for styling
- Explore HTML forms
- Study responsive design
- Learn JavaScript for interactivity
- Practice by building more webpages

---

## Slide 33: Resources
- MDN Web Docs: https://developer.mozilla.org/
- W3Schools: https://www.w3schools.com/
- HTML Validator: https://validator.w3.org/
- Free code editors:
  - Visual Studio Code
  - Sublime Text
  - Atom

---

## Slide 34: Q&A
- Any questions?
- **[IMAGE: Question mark or related visual]**

---

## Slide 35: Thank You
- **Contact information:**
  - Email: [Your Email]
  - Website: [Your Website]
- **[IMAGE: Contact or farewell visual]**
