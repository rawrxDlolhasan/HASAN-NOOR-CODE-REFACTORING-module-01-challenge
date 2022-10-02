# module-01-challenge
## Overview
In the module-01-challenge, a marketing-agency wants me to refactor its code to make-sure it follows accessibility-standards and is opitimized for search-engines.

My tasks include incorporating semantic-elements in index.html, logically-restucturing the elements in index.html independent of its styling and positioning, add alternate-text to the images in index.html and style.css, ensure the headings are written in sequential-order, and to write a title that represents the webpage.

### 01: Incorporating Semantic-Elements in index.html.
To incorporate semantic-elements in index.html, I replaced all the <|div|> and <|/div|> tags with their respective semantic-elements. For example, I changed <|div class="header"|> and <|/div|> to <|header class="header"|> and <|/header|>.

### 02: Logically-Restructuring the Elements in index.html Independent of its Styling and Positioning.
To logically-restructure the elements in index.html independent of its styling and positioning, I categorized elements with identical-properties in CSS into a class. For example, I categorized the elements and attributes in the <|article|> and <|/article|> tags into class="article-content" because they shared identical-properties in CSS. Also, regarding elements consisting of classes pertaining to one-thing, I changed the classes to ids. For example, I changed <|h1|>Hori<|span|> class="seo"|>seo<|/span|>n<|/h1|> to <|h1|>Hori<|span id="seo"|>seo<|/span|>n<|/h1|>. Not to mention, I deleted extra-tags and extra-symbols in elements. For example, I deleted the "/" in the <|img|> tags.

This isn't required, but I relocated the elements in style.css too to align them with the locations of the elements in index.html. For example, I relocoated .article-class to align it with its location in index.html.

### 03: Add Alternate-Text to Images in index.html and style.css.
To add alternate-text to the images in index.html, I incorporated alt="..." in the <|img|> tags.

To add alternate-text to images in style.css, I incorporated <|span role="img" aria-label="This is an image of a digital-marketing meeting."|> and <|/span|> between <|figure class="hero"|> and <|/figure|>.

### 04: Ensure the Headings Are Written in Sequential-Order.
To ensure the headings are written in sequential-order, I changed <|h2|>Made with ❤️️ by Horiseon<|/h2|> to <|h4|>Made with ❤️️ by Horiseon<|/h4|> in class="footer".

### 05: Write a Title That Represents the Webpage.
To write a title that represents the webpage, I replaced <|title|>website<|/title|> with <|title|>Horiseon<|/title|>.