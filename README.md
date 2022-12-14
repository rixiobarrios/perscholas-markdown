![Logo-Stacked-Light width="200" height="200"](https://user-images.githubusercontent.com/55994508/169154347-22ca074d-27cc-4633-9cbd-b722896b7481.png)

# `Intro to README files on Github by Rixio Barrios`

**What is a README.md file?**
GitHub, Inc., is an Internet hosting service for software development and version control using Git. It provides the distributed version control of Git plus access control, bug tracking, software feature requests, task management, continuous integration, and wikis for every project. [*source: Wikepedia*](https://en.wikipedia.org/wiki/GitHub)

**Why is a README.md important**

**Text Formats**

`Headings`
```
# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6
```
# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6

`Mixed`
```
### Heading 3 `Dark Heading`
```
### Heading 3 `Dark Heading`

`Bold`
```
**This sentence is now bold, thanks to asterisks.**
__This sentence is now bold, thanks to underscores.__
```
**This sentence is now bold, thanks to asterisks.**
__This sentence is now bold, thanks to underscores.__


`Italics`
```
*This is now in italics.*
_This is now in italics._
```
*This is now in italics.*
_This is now in italics._

`Strikethrough`
```
~~I am using strikethrough in this sentence.~~
```
~~I am using strikethrough in this sentence.~~

`Code`
```
function myMarkdown(readme) {
    if(readme === 'awesome') {
        return 'I love markdown!'
    }
    else {
        return 'I will try harder'
    }
}

console.log(myMarkdown('awesome'))
```

`Links`
```
This site was built using [GitHub Pages](https://pages.github.com/).
```
This site was built using [GitHub Pages](https://pages.github.com/).

`Relative Links`
```
[Contribution guidelines for this project](docs/CONTRIBUTING.md)
```
[Contribution guidelines for this project](docs/CONTRIBUTING.md)

`Lists`
```
- George Washington
- John Adams
- Thomas Jefferson
```
- George Washington
- John Adams
- Thomas Jefferson
```

1. James Madison
2. James Monroe
3. John Quincy Adams
```
1. James Madison
2. James Monroe
3. John Quincy Adams

`Nested Lists`
```
1. First list item
   - First nested list item
     - Second nested list item
```
1. First list item
   - First nested list item
     - Second nested list item

`Tasks`
```
- [x] #739
- [ ] https://github.com/octo-org/octo-repo/issues/740
- [ ] Add delight to the experience when all tasks are complete :tada:
- [ ] \(Optional) Open a followup issue
```
- [x] #739
- [ ] https://github.com/octo-org/octo-repo/issues/740
- [ ] Add delight to the experience when all tasks are complete :tada:
- [ ] \(Optional) Open a followup issue

`Tables`
```
| Syntax      | Description |
| ----------- | ----------- |
| Header      | Title |
| Paragraph   | First paragraph. <br><br> Second paragraph. |
```
| Syntax      | Description |
| ----------- | ----------- |
| Header      | Title |
| Paragraph   | First paragraph. <br><br> Second paragraph. |

`Mentioning a Github user or team`
```
@github/support What do you think about these updates?
```
@github/support What do you think about these updates?

`Emojis`
```
@octocat :+1: This PR looks great - it's ready to merge! :shipit:
```
@octocat :+1: This PR looks great - it's ready to merge! :shipit:

`Admonitions`
```
> :warning: **Warning:** Do not push the big red button.
```
> :warning: **Warning:** Do not push the big red button.
```
> :memo: **Note:** Sunrises are beautiful.
```
> :memo: **Note:** Sunrises are beautiful.
```
> :bulb: **Tip:** Remember to appreciate the little things in life.
```
> :bulb: **Tip:** Remember to appreciate the little things in life.

`Symbols`
```Copyright (©) — &copy;```
Copyright (©) — &copy;
```Registered trademark (®) — &reg;```
Registered trademark (®) — &reg;
```Trademark (™) — &trade;```
Trademark (™) — &trade;
```Euro (€) — &euro;```
Euro (€) — &euro;
```Left arrow (←) — &larr;```
Left arrow (←) — &larr;
```Up arrow (↑) — &uarr;```
Up arrow (↑) — &uarr;
```Right arrow (→) — &rarr;```
Right arrow (→) — &rarr;
```Down arrow (↓) — &darr;```
Down arrow (↓) — &darr;
```Degree (°) — &#176;```
Degree (°) — &#176;
```Pi (π) — &#960;```
Pi (π) — &#960;

`Footnotes`
```
Here is a simple footnote[^1].

A footnote can also have multiple lines[^2].  

You can also use words, to fit your writing style more closely[^note].

[^1]: My reference.
[^2]: Every new line should be prefixed with 2 spaces.  
  This allows you to have a footnote with multiple lines.
[^note]:
    Named footnotes will still render with numbers instead of the text but allow easier identification and linking.  
    This footnote also has been made with a different syntax using 4 spaces for new lines.
```
Here is a simple footnote[^1].

A footnote can also have multiple lines[^2].  

You can also use words, to fit your writing style more closely[^note].

[^1]: My reference.
[^2]: Every new line should be prefixed with 2 spaces.  
  This allows you to have a footnote with multiple lines.
[^note]:
    Named footnotes will still render with numbers instead of the text but allow easier identification and linking.  
    This footnote also has been made with a different syntax using 4 spaces for new lines.    

`Hidding content/comments`
```<!-- This content will not appear in the rendered Markdown -->```
<!-- This content will not appear in the rendered Markdown -->

`Ignoring Markdown`
```Let's rename \*our-new-project\* to \*our-old-project\*.```
Let's rename \*our-new-project\* to \*our-old-project\*. 