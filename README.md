# advanced-html-lecture

Welcome to the Cookie Recipes HTML Site! This project demonstrates various advanced HTML concepts and features, including forms, images, iframes, links, tables, and more, all centered around a fun and delicious cookie recipes. Each section is organized into different folders to showcase specific HTML elements and structures.

## Table of Contents
- [Project Structure](#project-structure)
- [Examples and Folders](#examples-and-folders)
- [How to View the Site](#how-to-view-the-site)
- [Contributing](#contributing)
- [License](#license)

## Project Structure

The project directory is organized as follows:
```bash
/advanced-html-lecture
├── /1_doc-structure
├── /2_anchor
├── /3_img
├── /4_iframe
├── /5_table
├── /6_form
├── /chrome-home
├── /resume
├── /assets
└── README.md
```


- **/doc-structure**: Contains an example of a basic HTML document structure.
- **/anchor**: Demonstrates the use of anchor (`<a>`) tags, including absolute and relative links, and internal page anchors.
- **/img**: Showcases how to include and display images in HTML.
- **/iframe**: Includes examples of embedding iframes to display external content such as Google Maps or other web pages.
- **/table**: Demonstrates how to create tables to display data in rows and columns.
- **/form**: Contains a contact form with fields like name, email, and message.
- **/chrome-home**: Mimics a simple version of the Google Chrome homepage.
- **/resume**: A longer example showcasing a resume format with HTML tables, images, and links.

## Examples and Folders

### 1. **/1_doc_structure**

This folder contains a basic HTML page structure, including:
- `<!DOCTYPE html>`
- `<html>`, `<head>`, and `<body>` tags.
- Basic metadata such as character set and viewport settings.
- A simple header, main content section, and footer.

### 2. **/2_anchor**

The anchor folder demonstrates how to create various types of links in HTML:
- **Absolute URLs**: Links to external resources.
  ```html
  <a href="https://www.example.com">Example Website</a>
  ```
- **Relative URLs**: Links to pages within the same website.
  ```html
  <a href="/about.html">About Us</a>
  ```
- **Page Anchors**: Links to specific sections within the same page.
  ```html
  <a href="#section2">Go to Section 2</a>
  ```
- **Email Links**: A link that opens the user's email client.
  ```html
  <a href="mailto:info@example.com">Send Email</a>
  ```
- **Phone Links**: A link that allows the user to initiate a phone call on mobile devices.
  ```html
  <a href="tel:+1234567890">Call Us</a>
  ```


### 3. **/3_img**
This folder demonstrates how to add images in HTML, including:

Images using the `<img>` tag with `src`, `alt`, and `width` attributes:
```html
<img src="https://www.example.com/cookie-image.jpg" alt="Delicious Cookies" width="500">
```

### 4. **/4_iframe**
The iframe folder includes examples of using iframes to embed external content, such as:

* Embedding a Google Map.
* Displaying an external website (e.g., an iframe showing a W3Schools page).

Example of embedding an iframe with Google Maps:

```html
<iframe src="https://www.google.com/maps/embed?pb=..." width="600" height="450" style="border:0;" allowfullscreen="" loading="lazy"></iframe>
```

### 5. **/5_table**
This folder demonstrates how to use tables to display structured data. For example:

```html
<table>
  <tr>
    <th>First Name</th>
    <th>Last Name</th>
  </tr>
  <tr>
    <td>Eli</td>
    <td>Ganim</td>
  </tr>
</table>
```

### 6. **/6_form**
The form folder contains a Contact Us form with fields for name, email, subject, and a message. It also includes a submit button.

Example:

```html
<form action="your-server-endpoint" method="POST">
  <label for="name">Full Name:</label><br>
  <input type="text" id="name" name="name" required><br><br>
  <label for="email">Email Address:</label><br>
  <input type="email" id="email" name="email" required><br><br>
  <label for="subject">Subject:</label><br>
  <input type="text" id="subject" name="subject" required><br><br>
  <label for="message">Message:</label><br>
  <textarea id="message" name="message" rows="4" cols="50" required></textarea><br><br>
  <button type="submit">Submit</button>
</form>
```

### 7. **/chrome-home**
This folder contains a simplified version of the Google Chrome homepage. It includes:

* A logo and search bar.
* Links to Google services like Gmail and YouTube.

### 8. **/resume**
The resume folder contains an example of a resume page using HTML, demonstrating:

* A personal introduction.
* Contact information.
* Education and work experience sections.
* Links to external references or projects.

## How to View the Site
To view the project locally, you can open the index.html file in your browser or use a live server extension in Visual Studio Code for a more dynamic experience. Here's how you can do that:

1. Open the project folder in Visual Studio Code.
2. Install the Live Server extension if you haven't already.
3. Right-click on index.html and select "Open with Live Server".
4. Your project will open in your default browser, and you can navigate between the various examples.

