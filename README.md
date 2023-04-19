# reference-website
1. Naming convention for all filenames, paths
- The naming conventions for all filenames should be lowercase, no spaces and dashes are fine. Folder naming convention should be similar to filenames. For paths, the folders, assets and files should be inside the root folder so they can easily linked inside any .html files
    `index.html`

2. Best practices for commit messages
- The best practices for commit messages is to use a minimun of three words and 10 characters. Always check for proper spelling and grammer. Always start with a capital letter and do not add periods. Always start with: Create, Add, Solve, Fix, etc

3. What is HTML?
- HTML is hypertext markup language and it is the coding language used to describe the content of websites

4. Proper syntax for HTML tags
- When writing in HTML, all of the tags used to define the purpose of the text that follow a specific syntax. Example below of a syntax in HTML
    `<p> I am a paragraph </p>`

5. Explain or demonstrate commonly used html tags/elements:

- headings: h1-h6
    Heading tags are wriiten to mark headings. The `<h1>` tag is the most important because it is the main heading in a website. The `<h2>` tag is used for subheadings. The `<h6>` is the least important and smallest one. Example shown below of headings:
    `<h1>` `<h2>` `<h3>` `<h3>` `<h4>` `<h5>` `<h6>`
- p
    The '<p>` tag is a paragraph tag and it is used to define the paragraph of text
- lists: ul, ol, dl
    `<ul>` is known as an unordered list and they are lists that begin with a bullet point. `<ol>` is known as ordered list and they are lists where each item in the list is numbered. For example, this list might be a set of steps for a recipe. `<dl>` is known as description list of terms also showing the description of the terms 
- a 
    `<a>` is used to define a hyperlink, which is usually used to link from one page to another like to web pages
- img
    `<img>` is used to insert images into an HTML document. Example shown below when inserting image into an HTML document:
    `<img src="images/art-piece.jpg">`
- q
    '<q>` is used to indicate that the enclosed text being used is a short inline quotation. Example below of 
    `<q>"I am a q-quote"</q>`
- blockquote
    The `<blockquote>` tag is usually used for longer quotes that take up an entire paragraph. The `<p>` is still usually used inside the `<blockquote>` element
- cite
    The cite element is used when you are referencing a book or research paper. This element is used to indicate where the citation is from `<cite>`
- em
    The `<em>` is known as emphasis. The placement of emphases usually changes the selected text to italic
- strong
    The `<strong>` tag indicates that there is strong importance and the selected text will appear bold
- b
    The `<b>` is used when you want to make text appear in bold. Although `<strong>` does the same thing, the `<b>` is used when it is not as important
- i
    The `<i>` tag is used when you want to make selected text in italic
- small
    The `<small>` tag is used when you want to make selected text smaller than the regular size font being used

5. Explain block elements and explain the list of block element and why they are used from below.
1. html - Anything inside the `<html>` and `</html>` is HTML code
2. head - The head contains information about the page. Before `<body>` is where you will see `<head>`
3. body - Everything inside the `<body>` element will be shown inside the main browser and window
4. header - Represents the introductory content and usually contains a heading, logo, or icon
5. nav - Represents a specific section of a page that links to other parts or pages within the page. The tag for this is `<nav>`
6. main - Anything content put inside `<main>` will be displayed to the person visiting the webpage
7. section - The `<section>` element is used to group related elements on a webpage. The `<section>` also defines the section in a HTML document
8. article - The `<article>` element is used to specify indepent, self-contained content.
9. div - `<div>` is a block element used to group elements together
10. aside - `<aside>` is almost the same as `<div>` but contains content that is only related of the main page content
11. footer - `<footer>` is found at the bottom of the webpage. They usually contain the author of a document with year in it
12. span - `<span>` is a generic inline container that is used to markup a part of text or document. It can also be used in grouping elements for styling purposes in CSS. 
13. small - `<small>` tag is used for specifying smaller text 

7. Explain why accessibility is important and explain the properties like:
- Web accessibility is important becuase it means everyone. By everyone means including users with disabilities to access your webpage. There are four principles to remeber when you want to have accessible content, and they are perceivable, operable, understandable, and robust. 
1. Landmark roles - 
2. Aria labels - 
3. Image alternative texts - 

8. What is CSS and how can we implement CSS to our html file (write proper explanation with the code required to attach a CSS file inside html file)
- CSS means cascading style sheets. It is to control the appearance of our HTML pages, like the design part of it. Adding CSS to our html file include a couple of steps. First step is making a `CSS` file and the create a `style.css` document. After these are made, you put the `style.css` inside the `CSS` file. Second step is to link the CSS file in HTML. Inside HTML, you attach the CSS file inside the `<head>` in HTML document using the `<link>` element. Example below
`<link rel="stylesheet" href="css/style.css">`

9. What is the difference between CSS property and value (write a proper explanation with the code required to attach a CSS file inside html file)
- CSS property informs CSS what you are changing and value informs CSS how you want an element to change. Property is also used with the type of design you want to add like color, border, width, etc. Value is an accepted value for property like 40px, purple. Example below of code when attaching a CSS file inside html file
`<link rel="stylesheet" href="css/style.css">`

10. Why do we use border-box property in CSS?
- We use border-box property in CSS becuase it is for setting box-sizing. It is used to setting the height and width to the border of the document.

11. Explain different type of ways we can add spacing to an element
- Different type of ways we can add spacing to an element is to either use the margin and padding properties. 

12. What is the main difference between margin and padding?
- The differences between margin and padding is margin is the space around an elements border and padding is usually the space between an elements border and the elements content.

13. What are different types of display properties?
- The different types of display properties are inline, block, inline-block, flex, and grid.

