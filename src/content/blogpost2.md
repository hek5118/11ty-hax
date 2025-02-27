---
title: Beginning to work with web components
order: 3
---
## Web Components for Beginners
<a href="{{ '/posts/firstpost/' | url }}">First post</a>

If you're a beginner in web development and web components, you've come to the right place. As of a few days ago, I had never worked with web components and had worked very little with JavaScript as a whole. In this post, I will give some pointers on how to start out on your web components journey. 

## What are web components?
When beginning to learn about a new tool, it helps to have a basic understanding of what it is. Web components are a set of API platforms that allow the creation and sharing of HTML tags when developing new sites and apps. The primary four specifications they are based on include custom elements, shadow DOM, ES modules, and an HTML template. [Learn more.](https://www.webcomponents.org/introduction)

![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/6uhawiyzi7ng7b8jmnuc.png)

## JavaScript Basics
Another important thing to note when learning about web components is their relationship with the coding language JavaScript. If you are new to JavaScript, I recommend [this article](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/JavaScript_basics) to help give you a basic understanding of its uses. 

I myself found this to be very helpful when I first began coding in JavaScript, as most of my background up to that point had been in Java; while there are some similarities between the two, it can certainly help to brush up on some of the key differences between a new language and your comfort language when programming.

## Downloading your IDE
The next step after brushing up on JavaScript would be to download an IDE to begin coding with it. Personally, I recommend VSCode; I found it to be very intuitive and beginner-friendly. I used [this site](https://code.visualstudio.com/) to download it onto my computer. 

## Downloading Node.js
After downloading VSCode, the next thing to do would be to head to https://nodejs.org/en/ to download Node.js. Be sure to download the LTS version to ensure that you are getting the most stable downloaded version. Node.js is a runtime for JavaScript that allows you to run server-side operations and programming. 

When you think you have it downloaded, an easy way to double check is to simply run `node -v` in your terminal like so:


![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/lfr3m3w1ffrhcrn3bksi.png)

## Downloading npm
Good news- if you successfully downloaded Node, you should already have npm as well. Npm is the default package manager for Node.js. You can double check this the same way you did for Node; type `npm -v` into your terminal:


![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/rnd9lrlbfeq8aejv9i4d.png)

##Downloading git
Using [this link](https://github.com/git-guides/install-git), you should be able to download git onto your computer. Git allows you to track all of the changes you make for any files and is highly recommended for use by programmers. Although this step isn't 100% necessary for this project, it is good to have.

## Initializing your open-wc project
Once you have VSCode, Node.js, and npm all installed correctly, we can move onto web components. If you are using git, first create a pathway of folders that you want this project to be in, and clone a repository from your GitHub into one of the files. After that, you can enter `npm init @open-wc`.  If this runs, you have correctly installed all of the necessary components thus far and are ready to begin working on web components! 


![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/96aor7e4dgsl4b7uj294.png)

You should be prompted with some questions following the command to launch web components. I chose the following: Scaffold a new project, Web component, Linting, Testing, Demoing, and I chose no for using typescript. You will be prompted to enter a tag name for the web component, perhaps "hello-world", and then I chose yes, and yes with npm. If this was done correctly, you should get a message instructing you to simply change directories and run the web component, which should take you to a screen such as this one: 


![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/ivkqoxths0v5r4zsb3dc.png)

Congratulations! You have completed the first steps of beginning to work with web components. If you are interested, I would recommend following this up with going through the /src file and ensuring you understand where most lines of code are coming from and contributing. Happy programming!