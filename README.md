# Git and github introduction

This repository gives a short introduction for [Fontys University of Applied Sciences in Venlo](https://www.fontys.nl) Software Engineering and Business Informatics students regarding usage of Git and Github. 

## What is Git?

* **DVCS** – Distributed Version Control System
* Like a **“more advanced”** SVN (Subversion)
* Most used VCS in the world (>70%)
* Used often in open source projects

## What is Github?

* Git hosting repository - [see Github.com](https://www.github.com)
* Besides hosting additional features
* Own workflow (pull requests) 
* There are more hosters: [bitbucket](https://www.bitbucket.org), [gitlab](https://www.gitlab.com) ...

More information: [github guide](https://guides.github.com/introduction/git-handbook/)

## Git basic commands

Command | Description | SVN command
--------|-------------|-------------
git clone | Clones a repository – making a local copy | svn checkout 
git status | To check the status of files you’ve changed in your working | svn status
git add | adds changes to stage/index in your working directory | svn add 
git commit  | commits your changes and sets it to new commit object for your remote | svn commit (differs in git)
git push/pull | Push or Pull your changes to remote. If you have added and committed your changes and you want to push them. Or if your remote has updated and you want those latest changes | svn commit (push is committing)
git branch | Lists out all the branches | svn copy 
git checkout |Switch to different branches | svn switch (on branches) or svn revert (on files)
git stash | Save changes that you don’t want to commit immediately | does not exist in svn
git merge | Merge two branches you were working on | svn merge
git reset  | You know when you commit changes that are not complete, this sets your index to the latest commit that you want to work on with. | svn revert (differs in git) 


## Markdown

Markdown is the language for documenting and communication. Comparable to Asciidoc. 

How do write markdown:

## Markdown Syntax


### Headers

```
# This is an <h1> tag
## This is an <h2> tag
###### This is an <h6> tag
```

# This is an \<h1\> tag
## This is an \<h2\> tag
###### This is an \<h6\> tag


### Emphasis (Bold, Italic)

```
*This text is italic*
_This is also italic_
```

*This text is italic*
_This is also italic_

```
**This text is bold**
__This is also bold__
```

**This text is bold**
__This is also bold__

```
_You **can** also combine them_
```

_You **can** also combine them_


### Lists

_Unordered_

```
* Item 1
* Item 2
  * Item 2a
  * Item 2b
```

* Item 1
* Item 2
  * Item 2a
  * Item 2b


_Ordered_

You do not need to manually number your ordered list. Subsequent items in the list will be automatically numbered if you use `-` instead of numbers.

```
1. Item 1
- Item 2
- Item 3
   1. Item 3a
   - Item 3b
```

1. Item 1
- Item 2
- Item 3
   1. Item 3a
   - Item 3b




_Combined_

```
1. Item 1
- Item 2
   - Sub-item
   - Sub-item
```

1. Item 1
- Item 2
   - Sub-item
   - Sub-item




_Task Lists_

```
- [x] first, choose an ordered or unordered list style, then add checkboxes
- [x] completed item
- [ ] incomplete item
```

- [x] first, choose an ordered or unordered list style, then add checkboxes
- [x] completed item
- [ ] incomplete item


### Tables

You can create tables by assembling a list of words and dividing them with hyphens - (for the first row), and then separating each column with a pipe `|`:

```
Column 1 Header | Column 2 Header
------------ | -------------
Content from cell 1 | Content from cell 2
Content in the first column | Content in the second column
```


First Header | Second Header
------------ | -------------
Content from cell 1 | Content from cell 2
Content in the first column | Content in the second column


### Strikethrough

```
~~strikethrough text like this~~
```

~~strikethrough text like this~~


### Images

Image syntax allows for alternative text. The format is `![alt text](URL)`. The URL can be a relative project path or an external website URL.

```
![Org Logo](../logo_square.png)
![Org Logo](https://raw.githubusercontent.com/wendikristine/documentation-template/master/logo_square.png)
```

![Org Logo](../logo_square.png)

![Org Logo](https://raw.githubusercontent.com/wendikristine/documentation-template/master/logo_square.png)

### Links

Links are created automatically in most cases (and always on Github). Or, you can specify a link with alternative text.

http://github.com - automatic!

```
[GitHub](http://github.com) link
```

[GitHub](http://github.com) link


### Block Quotes

```
> "Not enough blinky lights."
> - Henry Neeman, SiPE 2018
```


> "Not enough blinky lights."   
> ~ Henry Neeman, SiPE 2018


### Code

```   
I think you should use an
`<addr>` element here instead.
```   

I think you should use an   
`<addr>` element here instead.



```   
mkdir lesson06/   
cd lesson06   
```      


Markdown supports language-specific syntax highlighting.


```javascript
function fancyAlert(arg) {
  if(arg) {
    $.facebox({div:'#foo'})
  }
}
```


```javascript
function fancyAlert(arg) {
  if(arg) {
    $.facebox({div:'#foo'})
  }
}
```


You can also simply indent your code by four spaces:

    function fancyAlert(arg) {
      if(arg) {
        $.facebox({div:'#foo'})
      }
    }


### Horizontal Rule

```
---
```

---


### Emoji

GitHub supports emoji! :sparkles: :camel: :boom:

To see a list of every image we support, check out the Emoji Cheat Sheet.


See [Mastering Markdown](https://guides.github.com/features/mastering-markdown/) for more information about Markdown. 
