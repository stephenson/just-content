# Just Content, blogging theme for Ghost with focus on the content

I just want an awesome and simple designed blog, so I created just-content! Inspired by an old design from Segment.com's blog this turned into my private blog that I am now moving to Ghost and open sourcing the theme.

[DEMO](https://www.stephenson.dk) (not powered by Ghost yet, still in the process of moving my blog).

[Download version 0.1 beta](https://github.com/stephenson/just-content/archive/v0.1-beta.zip), please provide feedback as [issues here on Github](https://github.com/stephenson/just-content/issues).

Come and help make it awesome!

![Just Content Ghost Theme](https://github.com/stephenson/just-content/blob/master/assets/screenshot-desktop.jpg?raw=true)

## I am in no way perfect

I am not a frontend developer, nor a designer. I am just a script kiddy that likes great design, so please help improve this theme both when it comes to code, features, and design. I am here to learn!

## Local development setup

You need to set up Ghost on your local machine, read the official documentation [here](https://docs.ghost.org/v1/docs/install-local).

I use [Sass](http://sass-lang.com) to generate CSS files. 
First, you need to install bundle on your machine if you are on a mac run `bundle install`. This will install Sass. 

Go to the theme directory and run `sass --watch assets/css:assets/built`, this will run Sass in the background and update the compiled .css file in the built dir every time you make changes to the .scss files.
