# GFM (Github Flavored Markdown) 
__Markdown__ _is_ a lightweight markup *language* **with** *__plain__* text formatting syntax. Its design allows it to be converted to many output formats, but the original tool by the same name only supports HTML.[8] Markdown is *~~often~~* used to format readme files, for writing messages in online discussion forums, and to create rich text using a plain text editor.


# 1. indentation
To create indentation use one of the following:
  - Surround the word(s) with Asterisk (Simillar to whatsapp): *Like this* 
  - Surround the word(s) with a single underscore: _Like this_ 
# 2. Strikthrough
To create a strikthrough (line through the text), surround the word(s) with two tildas at each side: ~~Markup~~

# 3. Bold Text 
To make the text bold:
  - Surround text with two underscores on each side: __like this__
  - Surround text with two Asterisks on each side: **like this** 
  - Surround text with two Asterisks on each side: ##like this
# 4. Bullet points
To create a bullet point, start the line with a minus sign.
# 6. Titles
To create a title line like the one at the top of this page, start with a hashtag. the number of hastags determines the type:
  # Large title
  ## Medium title
  ### Small title

### 7. Task List
Somethimes you want to present a list of itmes using checkboxes (for example, steps in a project). The line containing the checkbox has to start with a asterisk! Create an unchecked checkbox using square brackets with a space between them .To create a checked checkbox (completed item) put an x between the brackets.
  * [ ] Buy Bread
  * [x] Buy milk 

## 8. How to display graphics?
### 1. Display a image
  a. upload a picure to the github project
  b. point to the picure using relative path, this is done using an exclamation mark, followed by the link to the picture within curved brackets
  c. you also need to add some text within square brackets. this text will be displayed if the picure failed to load
### 2. Add hover info.
Add short informative text that will apper when the user's mouse hovers over the image. This is done by adding some words inside quatation marks. place it in the curved brackets, next to the picutre path. add a whitepace between them.
  ![Stock photo][1]
## 9. Using references
Sometimes you may want to add multiple refrences to the same resource within the same document.
This is done by:
1. Declare a reference number by placing a *distinct* number within square brackets followd by a colon: \[1]:. This is usually done at in a seperate segment at the bottom.
2. Place the resource (usually a link or something) below the reference number.
3. Add a reference to it where you want by adding the \[1] mark.

## 10. Ordered & Unordered Lists with Markdown
To create *un-ordered* lists, use \- at the begining of each line.
To create *ordered* lists, use numbers and a dot at the begining of each line. the starting number matters, the rest don't.
To create hirarchy wuthin the list, just add some white spaces at the start of the line. for example:
- Fruits
    - Apple
    - Banana 
- Vegetables
    - Tomato

## 11. Escape charachters
As described in previous sections, some charachters have a special meaning in markdown (e.g hashtag). But what if we want to display it as-is? Markdown has an escape charachter: \ add it to tell markdown to treat the following charachter as a regular one.

# TODO: Explore Mermaid
On February 14th, GitHub gifted a new feature to all devlovers. Mermaid syntax is now supported by default in GitHub Markdown. This means that we can now create and edit diagrams in the native markdown file.
But first, what is Mermaid? 🧜‍♀️

Mermaid is a tool that renders diagrams based on markdown-like text content. It helps us visualize documentation and catch it up with development by dynamically creating and modifying diagrams in the browser. 

[1]: 
https://github.com/oshul/Markdown/blob/main/pexels-pixabay-38537.jpg "What a nice photo!"
