# Introduction to HTML: Lesson Plan

## Lesson Overview
- **Title**: Introduction to HTML
- **Duration**: 120 minutes (extended to include web fundamentals)
- **Target Audience**: Beginners with no prior coding experience
- **Prerequisites**: Basic computer skills

## Learning Objectives
By the end of this lesson, students will be able to:
1. Explain what HTML is and its role in web development
2. Understand how the web works (client-server model)
3. Understand the basic structure of an HTML document
4. Create a simple webpage using common HTML elements
5. Use proper HTML syntax and formatting

## Materials Needed
- Computers with text editors (Notepad, VS Code, Sublime Text, etc.)
- Web browsers (Chrome, Firefox, etc.)
- Projector for demonstrations
- Optional: Handouts with HTML reference guide and web architecture diagram

## Lesson Content

### 1. How the Web Works (30 minutes)
- The Internet vs. the World Wide Web
  - Internet: Global network of computers
  - Web: Information system on the Internet accessed via URLs
- Client-Server Architecture
  - Clients: Devices that request and display information (computers, phones)
  - Servers: Computers that store and process information
  - How they communicate
- HTTP (Hypertext Transfer Protocol)
  - Request-response cycle
  - Common HTTP methods (GET, POST)
  - HTTP status codes (200 OK, 404 Not Found, etc.)
- Domain Names and URLs
  - Structure of a URL (protocol, domain, path)
  - DNS (Domain Name System) - translating domain names to IP addresses
- Web Development Technologies
  - HTML: Structure
  - CSS: Presentation
  - JavaScript: Behavior/Functionality
- Activity: Trace a web request from typing a URL to seeing a webpage
  - Use browser developer tools to show network requests

### 2. Introduction to HTML (15 minutes)
- What is HTML? (Hypertext Markup Language)
- Brief history and purpose of HTML
- The role of HTML in web development (structure vs. styling)
- How browsers interpret HTML code
- Demonstration: Show a simple webpage and its corresponding HTML code

### 3. HTML Document Structure (20 minutes)
- Basic HTML document structure:
  - DOCTYPE declaration
  - `<html>` element
  - `<head>` and `<body>` sections
- Essential elements in the `<head>`:
  - `<title>`
  - `<meta>` tags
- Proper HTML syntax:
  - Opening and closing tags
  - Self-closing tags
  - Attributes and values
  - Nesting elements correctly
- Demonstration: Creating a basic HTML document template

### 4. Common HTML Elements (30 minutes)
- Text elements:
  - Headings (`<h1>` through `<h6>`)
  - Paragraphs (`<p>`)
  - Text formatting (`<strong>`, `<em>`, `<br>`, `<hr>`)
- Lists:
  - Ordered lists (`<ol>` and `<li>`)
  - Unordered lists (`<ul>` and `<li>`)
- Links:
  - Anchor tags (`<a>`)
  - Relative vs. absolute paths
- Images:
  - Image tags (`<img>`)
  - Alt text and accessibility
- Demonstration: Adding various elements to the webpage

### 5. Hands-on Practice (20 minutes)
- Guided activity: Students create a simple personal webpage with:
  - A heading with their name
  - A paragraph about themselves
  - A list of interests/hobbies
  - A link to a favorite website
  - An image (can be from the web)
- Instructors circulate to provide assistance

### 6. Conclusion and Next Steps (5 minutes)
- Recap of key concepts
- Preview of future topics (CSS, more HTML elements, forms, etc.)
- Resources for further learning
- Q&A session

## Assessment
- During practice: Observe students' ability to implement HTML elements
- After class: Review completed webpages for proper HTML structure and syntax
- Optional: Short quiz on HTML concepts and web architecture

## Extension Activities
- Add more complex elements to their webpage (tables, divs, etc.)
- Explore additional HTML5 semantic elements
- Create a multi-page website with navigation links
- Use browser developer tools to inspect existing websites

## Resources for Students
- HTML reference guides
- Online tutorials (MDN Web Docs, W3Schools, etc.)
- Code validators (W3C Markup Validation Service)
- Browser developer tools documentation

## Sample Code for Demonstration

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My First Webpage</title>
</head>
<body>
    <h1>Welcome to My Webpage</h1>
    
    <h2>About Me</h2>
    <p>Hello! My name is <strong>Alex</strong>. I am learning <em>HTML</em>.</p>
    
    <h2>My Hobbies</h2>
    <ul>
        <li>Reading</li>
        <li>Hiking</li>
        <li>Photography</li>
    </ul>
    
    <h2>My Favorite Websites</h2>
    <ol>
        <li><a href="https://www.example.com">Example Website</a></li>
        <li><a href="https://www.wikipedia.org">Wikipedia</a></li>
    </ol>
    
    <h2>A Picture</h2>
    <img src="https://via.placeholder.com/300x200" alt="Placeholder Image">
</body>
</html>
```

## Visual Aids for "How the Web Works" Section

### Client-Server Model Diagram
Draw or display a simple diagram showing:
- Client (browser) on one side
- Server on the other side
- Arrows showing request/response flow
- Labels for HTML, CSS, JavaScript files

### URL Structure Breakdown
Example URL: https://www.example.com/products/index.html
- Protocol: https://
- Domain: www.example.com
- Path: /products/index.html
