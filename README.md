# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help me improve my coding skills by building realistic projects. 

## Table of contents

  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  

## Overview

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process
- I have wrote  html and css separately and link togather and it has two versions
    1. mobile design version
    2. desktop design version

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid

### What I learned

Use this section to recap over some of your major learnings while working through this project. Writing these out and providing code samples of areas you want to highlight is a great way to reinforce your own knowledge.

To see how you can add code snippets, see below:

```<!DOCTYPE html> 
<html lang="en">
    <head>
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <meta charset="utf-8">
        <title># Frontend Mentor - QR code component</title>
        <link rel="stylesheet" href="desktop-design.css">
        <link rel="stylesheet" href="mobile-design.css">
        <link rel="icon" type="image/x-icon" href="../images/favicon-32x32.png">
    </head>
    <body>
        <main>
            <div class="main">
                <div class="image-back">
                <img src="../images/image-qr-code.png" alt="QR image" id="image">
                <p id="title">Improve Your Front-end Skills by building projects</p>
                <p id="description"> Scan the QR code to visit Frontend Mentor and take your coding skills to the next level </p> 
            </div>
        
        </main>
    </body>
</html>
```
```css for desktop version
 body{
   
    font-family: Gill Sans, sans-serif;
    font-weight: 400;
    display: flex;
  
}
.main{
   background-color: hsl(212, 45%, 89%);
    width:  34cm;
    height: 19cm;
    margin: 20rem;
    padding-top: 3.8cm;
    position: relative;

  
   }

 .image-back{
   width: 7.5cm;
   height: 12cm;
   background-color: white;
   border-radius: 25px;
   margin-left: 13.6cm;
   padding-top: 15px;
   padding-left: 3px;
   padding-right: 3px;
   
}


#image{
    width: 6.8cm;
    height: 6.8cm;
    border-radius: 20px;
    padding-left: 12px;
   }

#description{
   font-size: 15px;
   padding:0 20px;
   text-align: center;
}
#title{
    padding: 0 20px;
    text-align: center;
    font-size: 20px;
}
```


If you want more help with writing markdown, we'd recommend checking out [The Markdown Guide](https://www.markdownguide.org/) to learn more.
