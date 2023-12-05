# HTML Advanced

![Final result](home.jpg)


## Concepts

In this project, you will delve into advanced HTML concepts. Make sure to familiarize yourself with the following:

- Some pointers about HTML
- HTML - elements of a web page
- HTML Foundations
- HTML - Semantic sectioning elements
- HTML Semantic Elements
- HTML Validation



## Resources

Read or watch the following materials:

- Learn to Code HTML & CSS (until "Creating Lists" included)
- Introduction to HTML
- MDN

## Learning Objectives

By the end of this project, you should be able to explain the following concepts without relying on Google:

### General

- What is HTML
- How to create an HTML page from a wireframe
- What is a markup language
- What is the DOM
- What is an element/tag
- What is an attribute
- The purpose of each HTML tag

## Requirements

### General

- All your files should end with a new line.
- A README.md file at the root of the project folder is mandatory.
- You are not allowed to install, import, or use external libraries. The website must be built with only HTML/CSS/JavaScript; no NodeJS, React, VueJS, Bootstrap, etc.
- Your code should be W3C compliant and validate with W3C-Validator.

## Tasks

### 0. README and Objectives! (mandatory)

In this and coming projects, you will implement a webpage from a designer file. For this first project, focus solely on the HTML structure - no CSS, no style - just pure HTML semantic.

The designer file is available on Figma. Create an account to access the final result here:

- [Page in Figma](fig file)

And "Duplicate to your Drafts" to have access to all design details.

### Important notes with Figma:

- If your computer lacks missing fonts, you can find them here: [source-sans-pro](https://www.fontsquirrel.com/fonts/source-sans-pro) and [Spin-Cycle-OT](https://www.fontsquirrel.com/fonts/Spin-Cycle-OT).
- Some values are in float - feel free to round them.

For this task, please write an amazing README.md.

Repo:

- GitHub repository: holbertonschool-web-development
- Directory: html_advanced
- File: README.md

## HTML Advanced

### 1. Header (mandatory)

Let’s start by the top: the header

Here the wireframe of it:

Create the HTML skeleton (html, head, body, etc.)
In the body, add a header tag
Inside this header:
- Add a link element with an image inside
- Add a block of 3 link elements

Repo:

- GitHub repository: holbertonschool-web-development
- Directory: html_advanced
- File: index.html


### 2. Banner (mandatory)

Now, the banner under the header:

Under the header, add a main element with inside a section element.

In this section element, add:

A block with inside:
- An heading tag (don’t forget to use the correct heading value)
- A text element
- A button tag

Another block with inside:
- Another heading tag (same, be careful about which one you are using)
- A block containing 4 blocks - each block with inside:
    - An image
    - An heading tag
    - A text


### 3. Quote (mandatory)

Under the banner, we will add the quote block:

The quote section is inside the main:

Create a new section for the quote
Inside, add a block containing:
- An image
- Another block with inside:
    - A quote tag
    - An author quote
    - A text


### 4. Videos (mandatory)

Let’s now add the videos list:

New section with inside:

- An heading tag
- A block containing the 4 video blocks - each of them is composed with:
    - An image
    - An heading
    - A text
    - A block for the author:
        - An image
        - An heading
    - A block for the rating:
        - A block of images (one star = one image)
        - A text


### 5. Membership (mandatory)

Membership section is similar to the videos list:

After the videos list section, add a new section containing:

- An heading
- A block with inside 4 block items - each block defined with:
    - An image
    - An heading
    - A text
    - A button


### 6. FAQ (mandatory)

The FAQ section is ending the page before the footer:

Add a section for the FAQ with inside:

- A block that contains 2 “row blocks”
    - Each “row block” contains 2 “item blocks”
        - Each “item block” is composed of:
            - An heading
            - A text



### 7. Footer (mandatory)

And… the footer!

After the last section, outside of the main, add a footer:

A global block (used later for centering the footer content), inside this block:
- A “row block” with:
    - An image
    - A block with inside:
        - Images with link
        - A text

And… that’s it for the moment - the result should not be shiny, don’t worry, CSS is coming…
