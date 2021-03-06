# All About Markdown
*Non-authoritative* info about and examples for Markdown in the RFC standard, GFM, and Stackoverflow varieties.&nbsp; *Comprised of research notes and not authoritative.*

---
### Summary
Markdown was initially created in 2004 by [John G](https://daringfireball.net/projects/markdown/). as a preprocessor of plain text files or text data.&nbsp; Markdown is used by many websites to allow users to easily format text for readability, although several of the larger websites that have Markdown style text formatting capabilities have implemented custom features specific for the website users' needs.&nbsp; [RFC 7763](https://tools.ietf.org/html/rfc7763) describes Markdown as a "writing format" in contrast with HTML being a "publishing format".&nbsp; That RFC 7763 as well as [RFC 7764](https://tools.ietf.org/html/rfc7764) put Markdown on a contextual spectrum as less formal then HTML and binary data file formats, and more formal than completely unstructured plain text.&nbsp; Because Markdown style is easily adapted for use in different contexts for different purposes often with purpose-specific functionality additions, there is no official standard Markdown.

### Basic Markdown Stylization Elements
This information on basic Markdown is from [John G.'s Markdown syntax specification](https://daringfireball.net/projects/markdown/syntax) and [Adam P.'s GitHub cheatsheet reference](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet).
* **Headers** - Line start with one to six octothorpes and a space.&nbsp; H1 and H2 can be optionally indicated with equals sign or minus sign character underlining on the line after the heading text.
* **Emphasis** - *italics* are denoted with single surrounding asterisks, **bold** uses two surrounding asterisks, **_both bold and italicized_** is denoted with two surrounding asterisks around a surrounding underscore, and ~~strikethrough~~ is denoted with two surrounding tilde characters.
* **Ordered Lists** - line start with '+', '-', or '\*' character.
* **Unordered Lists** - line start with any number, a period, and a space like '1.'; actual number is replaced with number for the item position in the list.
* **Links** - Link text enclosed in square brackets immediately followed by URL target address in parentheses.  An optional link title can be included in the parentheses in quotes following the URL and a space.  Example: \[link text\]\(url\_address\_text "link title"\).&nbsp; Reference style link definitions can either have the link text in both the text body and at the bottom of the text body, or have a number for the url address in another pair of square brackets after the link text, and list the actual url address at the bottom of the document.
* **Images** - Can be inline style or reference style.&nbsp; Inline-style: !\[alternative text\]\(image\_link\_url\)\[image title text\].&nbsp; Reference-style !\[alt text\]\[reference text\], with the reference text at the text body bottom like \[reference text\]: image\_url\_address.
* **Inline code highlighting** - denoted by surrounding backtick characters.
* **Block code highlighting** - originally denoted by indenting all of the code block lines one tab or four spaces, in GFM code blocks can be denoted by a line with three backticks and the language, then the code block, then a line with three backticks.
* **Tables** - columns are separated by the vertical bar character, with the column headers underlined by a text line of hyphens.&nbsp; The column header separator repeated hyphen lines can also indicate left/right/center alignment with semi-colons at the column header underline repeated hyphens start/end/both.
* **Block Quotes** - Start each block quote line with a greater-than character.&nbsp If a single long text line starts with the greater-than character, the entire wrapped block should be quote indented.
* **Horizontal Rule** - three or more hyphens, asterisks, or underscores.&nbsp; Depending on the css used to style the output, these might have different thicknesses.
* **Line Breaks** - Two successive new lines should start a new paragraph.&nbsp; One newline does not usually separate a paragraph into two paragraphs.

### GFM - Github Flavored Markdown
One of the most useful and popular sites that has a Markdown-style implementation is github.com.&nbsp; From the github.com page describing the [Basic writing and formatting syntax](https://help.github.com/articles/basic-writing-and-formatting-syntax/), the different Markdown elements that are available are:
**Headings**, **Text Styling**, **Quoting Text**, **Quoting Code**, **Links**, **Page Section Links**, **Relative Links**, and **Lists**.&nbsp; There are also several github.com specific Markdown level text preprocessing such as **[Task Lists]**, **[User and Team Mentions]**, **[Issue Tracker Entry References][1]**, **[Pull Request References][1]**, and **Emoji**.&nbsp; The way that github.com handles paragraphs and line breaks using an empty newline to start a new paragraph, as well as the '\\' backslash character escape code for showing the '\\', '\`', '\*', '\_', '\{\}', '\[\]', '\(\)', '\#', '\+', '\-', '\.', and '\!' characters.

[Task Lists]: https://help.github.com/articles/basic-writing-and-formatting-syntax/#task-lists
[User and Team Mentions]: https://help.github.com/articles/basic-writing-and-formatting-syntax/#mentioning-users-and-teams
[1]: https://help.github.com/articles/autolinked-references-and-urls/

### StackOverflow.com Markdown
https://stackoverflow.com/editing-help
