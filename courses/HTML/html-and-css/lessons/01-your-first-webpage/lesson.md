# Lesson 1: Your first webpage

**Course:** HTML and CSS  
**Status:** In progress

## What are HTML and CSS?

A webpage is usually made from three main technologies:

- **HTML** describes the content and structure. It tells the browser what things are.
- **CSS** controls the appearance. It handles colors, spacing, fonts, sizes, and layout.
- **JavaScript** adds behavior. It can respond to clicks, update information, and make things interactive.

For now, we'll focus on HTML and CSS.

## Your first HTML page

In Kodo, create a new file named `index.html`. Type this:

    <!DOCTYPE html>
    <html>
      <head>
        <title>My First Page</title>
      </head>
      <body>
        <h1>Hello, world!</h1>
        <p>This is my first webpage.</p>
      </body>
    </html>

If Kodo offers a preview, open it. You should see a large heading and a paragraph.

## What do the parts mean?

- `<!DOCTYPE html>` tells the browser to use modern HTML.
- `<html>` contains the whole page.
- `<head>` contains information about the page.
- `<title>` sets the browser tab title.
- `<body>` contains what appears on the page.
- `<h1>` is the main heading.
- `<p>` is a paragraph.

Most HTML elements have an opening tag and a closing tag. The closing tag has a slash, like `</p>`.

## Add some personality

Try changing the heading and paragraph. Add another paragraph of your own.

Then add this inside the `<head>` section:

    <meta name="viewport" content="width=device-width, initial-scale=1">

This helps the page fit phone and tablet screens properly.

## Challenge

Make a page about a game you want to create. It must have:

1. A page title in the browser tab.
2. One main heading.
3. Two paragraphs.
4. Your own wording.

Don't worry about making it pretty yet. We'll use CSS for that soon.

## Key idea

HTML is the page's structure. Tags label the different pieces of content so the browser knows what each piece is.
