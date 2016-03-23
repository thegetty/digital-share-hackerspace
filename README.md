# Hackerspace!

> Curious about how software actually gets built? Get introduced to some of the tools that developers use at the Getty, 
> and use them to build your own blog!

Welcome to the **Hackerspace**, part of the first-ever Getty Digital Share.
This file contains some useful links and resources to help you get started.

## Free Software

Some flash drives pre-loaded with useful free software are floating around 
during the workshop. If you didn't get one, or you if you want to learn more about
the programs used during the event, here are the links. All of this software is 
available in both PC and Mac versions:

- [Markright Markdown Editor](https://github.com/dvcrn/markright) (scroll down to the [download](https://github.com/dvcrn/markright#download) heading for latest versions)
- [Github Desktop Client](https://desktop.github.com/)
- [Atom Text Editor](https://atom.io/)

## Workshop Topics

1. [Markdown](#markdown)
2. [Git (and GitHub)](#git)
3. [Building Websites with Static Site Generators](#static-site-generators)

### Markdown

Markdown is a lightweight and easy-to-use syntax for formatting documents.
It doesn't require any special program to use—all markdown files are really just _plain text_.
There are many tools available which will automatically convert markdown texts into HTML, PDF, 
and many other formats.

> The overriding design goal for Markdown’s formatting syntax is to make it as readable as
> possible. The idea is that a Markdown-formatted document should be publishable as-is, as plain
> text, without looking like it’s been marked up with tags or formatting instructions.
>
> -- [John Gruber, creator of Markdown](https://daringfireball.net/projects/markdown/)

#### Basic Markdown Syntax

Syntax | Output
--- | ---
`# Heading 1` | H1 tag
`## Heading 2` | H2 tag
`### Heading 3` | H3 tag
`#### Heading 4` | H4 Tag
`##### Headiing 5` | H5 Tag
`###### Heading 6` | H6 Tag
`_italics_` | _Italicized text_
`**bold**` | **Bold text**
`[Link](http://www.google.com)` | [Hyperlinks](http://www.google.com)
`![Image](https://octodex.github.com/images/yaktocat.png)` | ![Yaktocat](https://octodex.github.com/images/yaktocat.png)
`:+1: :camel: :boom:` | Emoji! :+1: :camel: :boom:

This whole document is actually written in Markdown! Want to see the raw text? Just [click here!](https://raw.githubusercontent.com/gettypubs/digital-share-hackerspace/master/README.md)

:bulb: For a more complete reference on Markdown, check out this [Guide](https://guides.github.com/features/mastering-markdown/)


### Git

**Git** is a tool that software developers use for **version control**. Version Control is sort of like Track Changes in Microsoft Word, but for code. It's also a lot more powerful. Using Git, a developer can move forward and backwards through a project's history, see who made what changes, revert mistakes, and create alternate versions of the same codebase. These different versions are called **branches**, and a project being tracked by git is called a **repository**.

Git is very powerful, but it can also be a bit confusing at first:  

![XKCD GIT](http://imgs.xkcd.com/comics/git.png)  
_ Source: [XKCD](https://xkcd.com/1597/)

#### GitHub

Git is a computer program used to track changes in software projects.
[**GitHub**](https://github.com) is a social network that allows people all around the world to share code. Think of it as a friendly interface that sits on top of `git`. The document you're reading now is hosted on GitHub.

If you don't have an account, sign up for free [here](https://github.com/join)

Since a full explanation of how Git works is beyond the scope of this workshop, we'll use the [GitHub Desktop Client](https://desktop.github.com/) to interface with Git for now.

##### :bulb: Want to learn more about how Git and Github work?
- [GitHub's Hello World Guide](https://guides.github.com/activities/hello-world/) (~10 minute read)
- [Try Git Tutorial](https://try.github.io/levels/1/challenges/1) (An interactive tutorial – learn the `git` commands right in your browser)

### Static Site Generators

> Some info about Jekyll/static site generators here

#### Create a blog with Github Pages
1. Find a theme you like at [Jekyll Themes](http://jekyllthemes.org/)
2. Clone the repo to your computer
3. Make some changes, write stuff
4. Create a new branch called `gh-pages`
5. Publish your branch on GitHub
6. navigate to `www.your-username.github.io/your-repository-name` To see your site!
