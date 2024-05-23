## 💬 Hello, World!

Let's dive into displaying an alert in the browser using JavaScript's `alert` function. Follow these simple steps to get started:

1. Create an `index.html` file.
2. Add the following code:

```html
<!DOCTYPE html>
<html>
  <body>
    <p>Before the script...</p>

    <script>
      alert("Hello, world!");
    </script>

    <p>...After the script.</p>
  </body>
</html>
```

When the webpage loads, this code will display an alert with the message "Hello, world!"

## 🔗 Linking JavaScript to Your Webpage

There are a few methods to link a script to your webpage:

### The Script Tag

Using the `<script>` tag, you can either embed JavaScript directly into your HTML document or link to an external script file.

#### Embedding JavaScript

You can write your JavaScript code directly within the `<script>` tag:

```html
<script type="text/javascript">
  // Your JavaScript statements here
</script>
```

#### Linking to an External Script

Alternatively, you can link to an external JavaScript file:

```html
<script src="/path/to/javascript/file"></script>
```

**Important Note:** Our tool is designed to either link to an external script or embed your own script at a time. Attempting to do both simultaneously won't work.

---
