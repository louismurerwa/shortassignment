# CS52 Workshops: Introduction to Static Site Generation with Jekyll

The websites we've been building so far (think Lab 1 and 2) fall under the category of static sites. Static sites respond to requests much faster than dynamic ones, provide improved security since there's nothing dynamic to be exploited, and are better suited at handling traffic surges, as they only need to serve static files. If you are building a site where its information doesn't need to be constantly updated, static sites are a great option.

*Static site generators* allow an entire site to be built in one go on your computer before being put on the server. 

There are many different static site generators out there, but today we’re going to be working with a static site generator called **Jekyll**.

**Jekyll** is the static site generator behind the CS 52 course website, is integrated into GitHub, and is a pretty popular choice among static site generators these days.

## Overview

![Alt Text](https://media.giphy.com/media/5wWf7H89PisM6An8UAU/giphy.gif)

Summary of what we're about to do.

## Setup

### Windows

1. Install a [Ruby+Devkit](https://rubyinstaller.org/) version . Use default options for installation.
2. Open a new command prompt window from the start menu, so that changes to the PATH environment variable becomes effective.
3. Install Jekyll and Bundler via: gem install jekyll bundler

### Mac 

1. In terminal, install Xcode command line tools: `xcode-select --install`

2. You should have homebrew by now so we're not going over that

3. Install Ruby `brew install ruby`

4. Install Jekyll `sudo gem install jekyll`

### Check Jekyll

* `jekyll -v`

You should see this: `jekyll 3.8.5`

## Step by Step

* Try a fully set-up jekyll template 
* In terminal/git bash `cd` into your preferred directory
* `jekyll new tester`
* `cd tester`
* `jekyll serve`
* Voila! You have a basic jekyll site you can tweak
![](img/Capture.PNG)


#### 1. Create a site
  * Create a new directory for your site and name it whatever you'd like. Don't forget to initialize a Git repository.
  * Add your first file. Make an `index.html` file and add in the following code:
```<!doctype html>
<html>
  <head>
    <meta charset="utf-8">
    <title>Home</title>
  </head>
  <body>
    <h1>Hello World!</h1>
  </body>
</html> 
```
####2. Build the site
    * We need Jekll to build the site before we can view it. To do this, we can run two commands:
        * `jekll build` - This will build our static site to a directory called `_site`.
        * `jekll serve` - Does the same thing except it will rebuild any time you change the site and will run a local server at `http://localhost:4000`.
    * While developing the site it's better to use `jekyll serve` as it updates with any changes you make.
    * Go ahead and run `jekyll serve` and go to `http://localhost:4000` in your browser. You should see "Hello World!".
Remember to explain any notation you are using.

```javascript
/* and use code blocks for any code! */
```

![screen shots are helpful](img/helloworldworkshop.png)
####3. Liquid :shower:
Liquid is a templating language specific to Jekyll. It has three main parts: objects, tags, and filters.

:sunglasses: GitHub markdown files [support emoji notation](http://www.emoji-cheat-sheet.com/)

Here's a resource for [github markdown](https://guides.github.com/features/mastering-markdown/).


## Summary / What you Learned

* [ ] can be checkboxes

## Reflection

*2 questions for the workshop participants to answer (very short answer) when they submit the workshop. These should try to get at something core to the workshop, the what and the why.*

* [ ] 2 reflection questions
* [ ] 2 reflection questions


## Resources

* https://learn.cloudcannon.com/jekyll-setup/
* 
