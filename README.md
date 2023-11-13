# data-science
<img width="400" height="250" alt="" src="https://stemettes.org/zine/wp-content/uploads/sites/3/2021/12/ai-gif.gif" />

2. Adding a local GIF file to markdown.

<img width="400" height="250" src="hover-over-color.gif" alt="color picker" />
resize gif in markdown file

This approach works in both vanilla and GitHub markdown files.

The width and height attributes are used to set the width and height of the GIF.

You can use an img tag to add a GIF to your markdown file even without adjusting the GIF's width or height.

README.md
1. Adding a GIF from an external URL to markdown.

<img alt="color picker" src="https://bobbyhadz.com/images/blog/change-vscode-integrated-terminal-colors/hover-over-color.gif" />

2. Adding a local GIF file to markdown.

<img src="hover-over-color.gif" alt="color picker" />
# Adding a GIF to your markdown file with a reference
You can also add a GIF to your markdown file with a reference.

README.md
![color picker][my-gif]

[my-gif]:
  https://bobbyhadz.com/images/blog/change-vscode-integrated-terminal-colors/hover-over-color.gif
Notice that the first line uses 2 sets of square brackets [] and not square brackets [] and parentheses ().

The Last 2 lines set the name of the reference (my-gif) and the path to the GIF.

You can imagine that my-gif in the first line gets replaced with the URL that points to the external GIF.

This approach works in vanilla and GitHub markdown.

add gif to markdown using reference

If you use VS Code as your IDE, check out the following article:

Adding images and links to files to Markdown in VS Code
# Additional Resources
You can learn more about the related topics by checking out the following tutorials:

How to display Directory & File structure in Markdown Files
Right-align, justify-align and center text in Markdown
How to create an Alert/Admonition Box in GitHub Markdown
How to change the color of specific Text in Markdown
How to write Lists inside a Table in Markdown
How to embed a Video into GitHub README.md (Markdown)
I wrote a book in which I share everything I know about how to become a better, more efficient programmer.
book cover
You can use the search field on my Home Page to filter through all of my articles.
Share
Share
Share
Share
Share
author avatar
Borislav Hadzhiev
Web Developer

Twitter
GitHub
Linkedin

<img src=".gif" width="500" height="500"/>
