# All About Markdown
*Non-authoritative* info about and examples for Markdown in the RFC standard, GFM, and Stackoverflow varieties.&nbsp; *Comprised of research notes and therefore not considered authoritative.*

---
### Summary
Markdown was initially created in 2004 by [John G](https://daringfireball.net/projects/markdown/). as a preprocessor of plain text files or text data.&nbsp; Markdown is used by many websites to allow users to easily format text for readability, although several of the larger websites that have Markdown style text formatting capabilities have implemented custom features specific for the website users' needs.&nbsp; [RFC 7763](https://tools.ietf.org/html/rfc7763) describes Markdown as a "writing format" in contrast with HTML being a "publishing format".&nbsp; That RFC 7763 as well as [RFC 7764](https://tools.ietf.org/html/rfc7764) put Markdown on a contextual spectrum as less formal then HTML or binary data file formats, and more formal than completely unstructured plain text.&nbsp; Because Markdown style is easily adapted for use in different contexts for different purposes often with purpose-specific functionality additions, there is no official standard Markdown.&nbsp The original Markdown text-to-HTML conversion tool is described and downloadable at 

### Basic Markdown Stylization Elements
This information on basic Markdown is from [John G.'s Markdown syntax specification](https://daringfireball.net/projects/markdown/syntax) and [Adam P.'s GitHub cheatsheet reference](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet).
* **Headers** - Line start with one to six octothorpes and a space.&nbsp; H1 and H2 can be optionally indicated with equals sign or minus sign character underlining on the line after the heading text.
* **Emphasis** - *italics* are denoted with single surrounding asterisks, **bold** uses two surrounding asterisks, **_both bold and italicized_** is denoted with two surrounding asterisks around a surrounding underscore, and ~~strikethrough~~ is denoted with two surrounding tilde characters.
* **Ordered Lists** - line start with '+', '-', or '\*' character.
* **Unordered Lists** - line start with any number, a period, and a space like '1.'; actual number is replaced with number for the item position in the list.
* **Links** - Link text enclosed in square brackets immediately followed by URL target address in parentheses.  An optional link title can be included in the parentheses in quotes following the URL and a space.  Example: \[link text\](http\://address.url "link title").
* **

### GFM - Github Flavored Markdown
One of the most useful and popular sites that has a Markdown-style implementation is github.com.&nbsp; From the github.com page describing the [Basic writing and formatting syntax](https://help.github.com/articles/basic-writing-and-formatting-syntax/), the different Markdown elements that are available are:
**Headings**, **Text Styling**, **Quoting Text**, **Quoting Code**, **Links**, **Page Section Links**, **Relative Links**, and **Lists**.&nbsp; There are also several github.com specific Markdown level text preprocessing such as **Task Lists**, **User and Team Mentions**, **Issue Tracker Entry References**, **Pull Request References**, **Emoji**.&nbsp; The way that github.com handles paragraphs and line breaks using an empty newline to start a new paragraph, as well as the '\\' backslash character escape code for showing the '\\', '\`', '\*', '\_', '\{\}', '\[\]', '\(\)', '\#', '\+', '\-', '\.', and '\!' characters.
