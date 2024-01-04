# JavaScript: Bringing Web Pages to Life

JavaScript was created to bring interactivity to web pages. Instead of static content, it allows for dynamic and responsive elements.

## Understanding JavaScript

- **What is JavaScript?**
  - Initially designed to make web pages dynamic.
  - Scripts in JavaScript are snippets of code that make web pages interactive.
  - Unlike Java, JavaScript doesn't require compilation and can be directly included in HTML.

- **JavaScript's Reach:**
  - It can execute not just in browsers but also on servers and various devices equipped with a JavaScript engine.

## Powers of In-Browser JavaScript

1. **Manipulate Page Content:**
   - Add, change, or modify HTML content and styles dynamically.

2. **React to User Actions:**
   - Respond to user inputs like clicks, mouse movements, and key presses.

3. **Network Operations:**
   - Send requests to servers, download/upload files (using AJAX and COMET technologies).

4. **Interact with Users:**
   - Manage cookies, prompt user input, and display messages.

5. **Client-Side Data Storage:**
   - Store data locally using "local storage".

## Limitations of In-Browser JavaScript

- **Restricted Actions:**
  - Cannot read/write files on the hard disk, copy files, or execute programs.
  - Limited communication between different browser tabs/windows.
  - Fetching data from external sites/domains requires explicit permissions.

![Flow Diagram: JavaScript Capabilities](https://github.com/codingmonk-yt/js-notes/assets/116005536/56e54750-35fa-464d-967c-182189eda125)

## Unique Features of JavaScript

JavaScript stands out due to:
- **Seamless Integration:** 
  - Easily works with HTML/CSS, enabling smooth interaction.
- **Simplicity:** 
  - Simplifies handling basic tasks efficiently.
- **Universal Browser Support:** 
  - Supported by all major browsers and enabled by default.

----------------------

# Hello, world!

This tutorial focuses on core JavaScript, the language itself.

## Running JavaScript in the Browser

To execute JavaScript, the browser serves as a suitable environment. However, if you plan to work in another environment like Node.js, we'll minimize browser-specific commands like 'alert'.

### Attaching a Script to a Webpage

JavaScript programs can be inserted within HTML using the `<script>` tag:

```html
<!DOCTYPE HTML>
<html>
  <body>
    <p>Before the script...</p>
    <script>
      alert('Hello, world!');
    </script>
    <p>...After the script.</p>
  </body>
</html>
```

The JavaScript code within `<script>` tags runs when the browser processes the tag.

## Modern Markup

The `<script>` tag has attributes that were used in old code:

### The `type` Attribute: `<script type=...>`

In older HTML standards, scripts required a `type` attribute like `type="text/javascript"`. However, it's optional now and can even be used for JavaScript modules.

### The `language` Attribute: `<script language=...>`

This attribute indicated the script's language but is no longer necessary as JavaScript is the default language.

## External Scripts

For larger JavaScript code, placing it in separate files is recommended. Use the `src` attribute to link these files to HTML:

```html
<script src="/path/to/script.js"></script>
```

Absolute or relative paths can be used to specify the script file's location.

### Attaching Multiple Scripts

To link multiple scripts, use multiple `<script>` tags:

```html
<script src="/js/script1.js"></script>
<script src="/js/script2.js"></script>
<!-- ... -->
```

### External Library Example

Linking to a JavaScript library from a Content Delivery Network (CDN):

```html
<script src="https://cdnjs.cloudflare.com/ajax/libs/lodash.js/4.17.11/lodash.js"></script>
```





