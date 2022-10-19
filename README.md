Headings
Similar to HTML, there are 6 headings in Markdown:

# H1
## H2
### H3
#### H4
##### H5
###### H6
Try to use heading level 1 for the title of your document, h2 for the sections, h3 for subsections, and so on.

Alternate Headings
There is an alternate way of creating headings that only supports two levels:

Heading Level 1
===============
Heading Level 2
---------------
Paragraphs
Paragraphs are chunks of text separated by at least a blank line:

This is paragraph 1.
This is paragraph 2.
Line Breaks
The line break syntax is less known to the Markdown world.
It is achieved by adding at least two spaces to the end of the line:

This is line 1.  
This is line 2.
It’s less known because it’s invisible.

Emphasis
There are three ways to emphasize:

Bold
Italic
Bold and italic
Making bold can be done by double underscores or double asterisks:

This is __bold__, so is **this**.
But inside a word, only the asterisks work:

**Thi**s **i**s a **GitH**ub-**flavor**ed **Markdo**wn **cheatshe**et **focusi**ng **o**n **les**s-**kno**wn **featur**es.
To make italic, use one underscore or one asterisk, and again, inside a middle only the asterisk syntax works:

This is _italic_, so is *this*. And it's not *un*important.
And to make something bold and italic, one can mix the two syntaxes:

All of these are: ***bandi***, _**bandi**_, **_bandi_**, __*bandi*__, *__bandi__*, ___bandi___.
And inside the word: b***and***i which means bold***and***italic.
Inline Code
To write code in monospace font inside a regular text, enclose it in backticks:

This is `code` inside text.
If you want to write a code that has backticks in it, you can use double-backticks:

This is the syntax: ``This is `code` inside a text.``
Code Block
To create a code block, put four lines or a tab before it:

This is the code:
    for i in range(10):
        pass
The alternative syntax is wrapping the code in three backticks.

This is the code:
```
for i in range(10):
    pass
```
To display triple backticks in a code block, wrap them inside quadruple backticks.

The alternative syntax is wrapping the code in three backticks.
``‌``
This is the code:
```
for i in range(10):
    pass
```
``‌``
To display triple and quadruple backticks inside a code block, wrap them inside quadruple backticks and put a zero-width non-joiner inside the quadruple backticks you want to display.

Code Block with Syntax Highlighting
To create a code block with syntax highlighting, you can use the three backtick syntax and write the language name in front of it:

This is the code:
`‌`‌`python
for i in range(10):
    pass
`‌`‌`
As of now, some 583 languages are being supported for syntax highlighting. You can access the full list here.

Blockquotes
Blockquotes are designated by a > in front of them:

> Veniet tempus quo ista quae nunc latent in lucem dies extrahat et longioris aevi diligentia.
Use double > to create nested blockquotes.

Ordered Lists
To create an ordered list:

1. First item
2. Second item
3. Third item
The number can be out of order:

1. First item (indexed 1)
1. Second item (indexed 1)
5. Third item (indexed 5)
Markdown still fixes the counters and outputs the correct numbers:

First item (indexed 1)
Second item (indexed 1)
Third item (indexed 5)
Unordered Lists
To create unordered lists, use any of the following “bullet characters”: hyphen -, asterisk *, or plus sign +:

- Item
- Another item
- Yet another item
One can mix the bullet characters in one list, but it’s a bad practice.

Task Lists
A task list (aka checklist or todo list) is an unordered list with each item having a checkbox in front, either checked or unchecked. Tasks lists are very useful when writing issues on GitHub, as one can then check or uncheck them without manually editing the Markdown source of the comment or description.

- [x] Write the tests
- [ ] Implement the functions
- [ ] Fix the code formatting
Horizontal Line
To create a horizontal line, use three or more asterisks (***), hyphens (---), or underscores (___):

Some text!
---
Next chapter or something!
URLs and Email Addresses
To turn URLs and email addresses into links, just wrap them into angle brackets:

Take a look at my Medium posts: <https://aerabi.medium.com>
You can also email me at <mohammad-ali@aerabi.com>
Links
To create a link, enclose the linked text in brackets and then immediately the URL in parentheses:

Take a look at my [Medium posts](https://aerabi.medium.com/).
You can also add a title to the link that shows as a tooltip:

Take a look at my [Medium posts](https://aerabi.medium.com/ "Git Weekly is published there!").
Take a look at my Medium posts.

Images
Image syntax is similar to that of links, only it has an exclamation mark in front and the text is the alt text:

![My GitHub avatar](https://avatars.githubusercontent.com/u/44623032?v=4)
Subscript and Superscript
Subscripts and superscripts are used in chemistry, et cetera:

One might want to write about H<sub>2</sub>O or Batman<sup>TM</sup>.
Mathematics
One can write LaTeX-style mathematical formulae in GitHub-flavored Markdown now:

I know why $e^{i\pi} + 1 = 0$. And I also know that:
$$ \frac{G}{\mathrm{Ker}(\phi)} \cong \mathrm{Im}(\phi). $$

How the mathematical formulae render on GitHub
Tables
Tables are cool:

| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |
Emojis
Emojis can be written by using colons, hurray! 🎉

Emojis can be written by using colons, hurray! :tada:
Emojipedia has the GitHub shortcodes for emojis, e.g. 🏖️ Beach with Umbrella.

HTML
One can use HTML tags in Markdown as well.

One can use <b>HTML</b> tags in Markdown as well.
Comments
To hide contents in a Markdown document, one can use the HTML comment syntax:

<!-- This is comment and won't be rendered! -->
