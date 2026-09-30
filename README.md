# basic_html
📌 About This Repository
This repository contains a complete beginner-friendly reference for HTML5, covering commonly used tags, attributes, forms, tables, semantic elements, multimedia, and important HTML concepts.
It is useful for:

Beginners learning HTML
College assignments and projects
Web development practice
Quick revision before interviews
Placement preparation
📚 Topics Covered
1. Basic HTML Structure
<!DOCTYPE html>
<html>
<head>
    <title>My Page</title>
</head>

<body>

    <h1>Hello World</h1>

</body>
</html>
2. Headings
<h1>Heading 1</h1>
<h2>Heading 2</h2>
<h3>Heading 3</h3>
<h4>Heading 4</h4>
<h5>Heading 5</h5>
<h6>Heading 6</h6>

<h1> is the largest/most important heading and <h6> is the smallest.

3. Text Formatting

Common tags:

<p>Paragraph</p>

<b>Bold text</b>
<strong>Important text</strong>

<i>Italic text</i>
<em>Emphasized text</em>

<u>Underlined text</u>

<mark>Highlighted text</mark>

<small>Small text</small>

<del>Deleted text</del>

<ins>Inserted text</ins>

<sub>Subscript</sub>

<sup>Superscript</sup>
4. Links
<a href="https://example.com">Visit Website</a>

Open in a new tab:

<a href="https://example.com" target="_blank">
    Visit Website
</a>
5. Images
<img src="image.jpg" alt="Description">

Common attributes:

src → image location
alt → alternative text
width → image width
height → image height

Example:

<img src="cat.jpg" alt="A cat" width="300" height="200">
6. Lists
Unordered List
<ul>
    <li>Java</li>
    <li>Python</li>
    <li>HTML</li>
</ul>
Ordered List
<ol>
    <li>Wake up</li>
    <li>Study</li>
    <li>Go to college</li>
</ol>
Description List
<dl>
    <dt>HTML</dt>
    <dd>HyperText Markup Language</dd>
</dl>
7. Tables

Basic table:

<table>
    <tr>
        <th>Name</th>
        <th>Age</th>
    </tr>

    <tr>
        <td>John</td>
        <td>22</td>
    </tr>
</table>

Important tags:

<table> → creates table
<tr> → table row
<th> → table heading
<td> → table data
8. Forms

Basic form:

<form>
    <label>Name:</label>
    <input type="text">

    <label>Email:</label>
    <input type="email">

    <button type="submit">Submit</button>
</form>

Common input types:

<input type="text">
<input type="password">
<input type="email">
<input type="number">
<input type="date">
<input type="time">
<input type="file">
<input type="checkbox">
<input type="radio">
<input type="range">
<input type="color">
<input type="submit">
<input type="reset">
9. Useful Form Attributes
<input type="text" placeholder="Enter your name">
<input type="text" required>
<input type="text" disabled>
<input type="text" readonly>
<input type="text" value="Hello">

Common attributes:

placeholder
required
disabled
readonly
value
name
id
class
10. Textarea
<textarea rows="5" cols="30">
</textarea>

Used for multi-line text input.

11. Select Dropdown
<select>
    <option>India</option>
    <option>USA</option>
    <option>UK</option>
</select>
12. Semantic HTML

Semantic tags clearly describe the purpose of the content.

<header>
    Header content
</header>

<nav>
    Navigation
</nav>

<main>
    Main content
</main>

<section>
    Section content
</section>

<article>
    Article content
</article>

<aside>
    Sidebar content
</aside>

<footer>
    Footer content
</footer>

Benefits:

Better accessibility
Better SEO
Cleaner code
Easier maintenance
13. <div> and <span>

div is a block-level container:

<div>
    This is a div.
</div>

span is an inline container:

<p>Hello <span>World</span></p>
14. Audio
<audio controls>
    <source src="song.mp3" type="audio/mpeg">
</audio>
15. Video
<video controls width="500">
    <source src="video.mp4" type="video/mp4">
</video>
16. Iframe

Used to embed another webpage, video, map, etc.

<iframe
    src="https://example.com"
    width="600"
    height="400">
</iframe>
17. HTML Comments

Comments are ignored by the browser.

<!-- This is a comment -->
18. HTML Entities

Some special characters require entities.

&lt;    <
&gt;    >
&amp;   &
&nbsp;  space
&quot;  "
&apos;  '

Example:

<p>5 &lt; 10</p>
19. Global Attributes

These attributes can be used on most HTML elements.

id
class
style
title
lang
hidden
data-*

Example:

<p id="intro" class="text" title="Introduction">
    Hello
</p>
20. id vs class
ID

Used for one unique element.

<p id="heading">Hello</p>
Class

Can be used for multiple elements.

<p class="text">Hello</p>
<p class="text">World</p>
21. External CSS
<link rel="stylesheet" href="style.css">
22. Internal CSS
<style>
    p {
        color: blue;
    }
</style>
23. Inline CSS
<p style="color: red;">
    Hello
</p>
24. JavaScript

External JavaScript:

<script src="script.js"></script>

Internal JavaScript:

<script>
    alert("Hello!");
</script>
25. Viewport

Important for responsive websites:

<meta name="viewport"
      content="width=device-width, initial-scale=1.0">
🔑 Common HTML Attributes
Attribute	Purpose
id	Unique identifier
class	Group elements
style	Inline CSS
title	Tooltip information
href	Link destination
src	Resource location
alt	Alternative text
width	Width
height	Height
name	Element/form name
value	Element value
placeholder	Hint text
required	Makes input mandatory
disabled	Disables element
readonly	Makes input read-only
target	Controls where link opens
🚫 Void Elements

Void elements don't require a closing tag.

<br>
<hr>
<img>
<input>
<meta>
<link>
<source>
<area>
<base>
<embed>
<param>
<wbr>

Example:

<img src="photo.jpg" alt="Photo">

There is no </img>.

⚠️ Deprecated HTML Tags

Avoid old/deprecated tags such as:

<center>
<font>
<marquee>
<big>
<strike>

Use CSS and modern semantic HTML instead.

🧩 Complete Mini HTML Project
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">

    <meta name="viewport"
          content="width=device-width, initial-scale=1.0">

    <title>Student Portfolio</title>
</head>

<body>

    <header>
        <h1>My Portfolio</h1>

        <nav>
            <a href="#about">About</a>
            <a href="#skills">Skills</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>

    <main>

        <section id="about">

            <h2>About Me</h2>

            <p>
                Hello! I am a computer science student.
            </p>

            <img src="profile.jpg"
                 alt="Profile picture"
                 width="200">

        </section>

        <section id="skills">

            <h2>Skills</h2>

            <ul>
                <li>Java</li>
                <li>HTML</li>
                <li>CSS</li>
                <li>JavaScript</li>
            </ul>

        </section>

        <section id="contact">

            <h2>Contact Me</h2>

            <form>

                <label>Name:</label>
                <input type="text" required>

                <br><br>

                <label>Email:</label>
                <input type="email" required>

                <br><br>

                <label>Message:</label>

                <br>

                <textarea rows="5"></textarea>

                <br><br>

                <button type="submit">
                    Send
                </button>

            </form>

        </section>

    </main>

    <footer>
        <p>© 2026 My Portfolio</p>
    </footer>

</body>

</html>
