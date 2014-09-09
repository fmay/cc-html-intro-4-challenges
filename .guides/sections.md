---
title: "ASSESS YOUR HTML&CSS KNOWLEDGE"
files: []
editable: false
layout: 2-panels-tree

---
#'Forking' this module
If you check the url address bar of your browser, if it starts with `https://codio.com/anon/....` then this means it is an anonymous project and any changes you make will be lost when you close down the browser tab. This will be the case if you access the module from the Codio Courses screen.

To avoid losing changes, you can 'fork' the module into your own Codio account where it will appear in your projects list. To do this, select the **'Project->Fork'** menu item and choose a suitable name for the project.

#A few words about the Codio Guide
Before we start with this module here are a few pointers about using this Codio Guide.

If you've already read this in another Guide then skip to the next section.

![](.guides/img/guides-helper.jpg)

#The File Tree
The left most panel is the File Tree **(1)**. This is where your project's files are stored. You can open up files you see listed there by clicking on them.

#About the Codio Guide
The Codio Guide **(2)** is the content you are reading right now. It's worth knowing the following

- if you ever close the Guide tab by mistake, simply open in from the View menu **(3)**.
- you can expand and collapse the Guide's Table of Contents **(4)** with the Hamburger icon **(5)**
- you move from one section of the Guide to the next using either the Table of Contents or the Navigation Buttons (6)

#The Rocket Menu
The Rocket menu **(7)** is a dropdown menu that lets you load code into your file tree when you click it as different sections might want to show different bits of code.

You are usually encouraged to mess around with the live code. It is perfectly likely that you can wreck the code so pressing the Rocket menu button will restore the code again to its original state.

#Previewing
The Preview button **(8)** lets you run your web application. When you press it, it will open up a preview window so you can play with your app.

#Code Tabs
When you open some code from the file tree or the Codio Guide opens a file for you automatically, they will appear within a tab **(9)** in one of the panels. You can have several of these open at one time so you may need to click on the respective tab to get to see the file you want.


---
title: Overview
files: []
editable: true
layout: ""

---
**STATUS** : Incomplete. We are working on this and will shortly be populating it with some proper challenges.

#Fork the project
If you want to save your work you must fork this project into your own Codio account first. You can do this from the 'Project->Fork' menu item at the top.

#What is this module?
This module is a whole series of challenges that assess your knowledge of HTML and CSS.

If you can complete all of the tests below, right through to brutal, then it will be safe to assume that you know enough to be seriously impressive.

You should aim to conquer the easy and moderate tests (and feel free to use Google to help) to be at a solid level.


#How do I start?
In the left hand side you will see three folders `easy`, `moderate` and `hard`. Inside each of these are further folders that contain the individual challenges.

Select one of these challenge sub folders and you will see that files are provided as a suitable starting point. You should open these up and start working on them to meet the challenge.

Open up the `README.md` file to get instructions and then you can start the challenge.

The file will initially open up as markdown, so press the floating icon in the top right to view it nicely displayed.

#Preview
Whenever you want to run your code, simply press the 'Preview' menu button in the top.

#Challenge Summary
The following pages give a summary of the available challenges.

---
title: EASY
files: []
editable: true
layout: ""

---
The challenges in the following sections are not too hard. Feel free to use Google to help you as you need, but try without to start with.


---
title: "Color & Font Size"
files: []
editable: false
layout: ""

---
#Loading the Challenge
To load this challenge, press the link below. 

[**LOAD CHALLENGE**]()

#Challenge
Your challenge is to get the output shown below by modifying `main.css`.

![](.guides/easy/01-colors/result.png)

You should incorporate the following

>- define the font size (20px) using the body selector
- for the <h1> color, use a color name, not a hex value
- for the <p> color, use a hex color value (use Google to find out about hex color values in general)

#Saving your work
If you want to move to another challenge then you can save what you have done on the current challenge by clicking the link below.

[**SAVE MY WORK**]()  cp ~/workspace/main.css ~/workspace/.guides/easy/01-colors && cp index.html ~/workspace/.guides/easy/01-colors

To restore it, click this link

[**RESTORE MY WORK**]() cp ~/workspace/main.css ~/workspace/.guides/easy/01-colors && cp ~/workspace/main.css ~/workspace/.guides/easy/01-colors

---
title: Inline Styles
files: []
editable: false
layout: ""

---
#Loading the Challenge
To load this challenge, press the link below. 

[**LOAD CHALLENGE**]()

#Challenge
Your challenge is the same as the previous one - to get the output shown below - but this time, you should include your styles inside `index.html` without using `main.css`. Generally speaking, this is not good practice but is useful in simple situations like this.

![](.guides/easy/02-inline/result.png)

If you don't know how to do this yet, and it was not covered in our prior modules, then Google it. You'll see that you need to include the <style> tag.

#Saving your work
If you want to move to another challenge then you can save what you have done on the current challenge by clicking the link below.

[**SAVE MY WORK**]()  cp ~/workspace/main.css ~/workspace/.guides/easy/02-inline && cp index.html ~/workspace/.guides/easy/02-inline

To restore it, click this link

[**RESTORE MY WORK**]() cp  ~/workspace/.guides/easy/02-inline ~/workspace/main.css && cp ~/workspace/.guides/easy/02-inline ~/workspace/main.css



---
title: Lists
files: []
editable: false
layout: ""

---
#Loading the Challenge
To load this challenge, press the link below. 

[**LOAD CHALLENGE**]()

#Challenge
You need to create the output you see below. You start out with the simple `index.html` provided and you need to add your own HTML list elements into it.

You then edit `main.css` to create the desired output styles

- the bullet point list has **square** bullets, not the default round ones
- the numbered list has a larger than normal line spacing


![](.guides/easy/03-list/result.png)

If you don't know how to create lists, it's easy, just Google it.

#Saving your work
If you want to move to another challenge then you can save what you have done on the current challenge by clicking the link below.

[**SAVE MY WORK**]()  cp ~/workspace/main.css ~/workspace/.guides/easy/02-inline && cp index.html ~/workspace/.guides/easy/02-inline

To restore it, click this link

[**RESTORE MY WORK**]() cp  ~/workspace/.guides/easy/02-inline ~/workspace/main.css && cp ~/workspace/.guides/easy/02-inline ~/workspace/main.css



---
title: Link CSS files
files: []
editable: false
layout: ""

---
#Loading the Challenge
To load this challenge, press the link below. 

[**LOAD CHALLENGE**]()

#Challenge
You need to create the same output as the previous challenge with the 2 lists. However, rather than having all your CSS in one single `main.css` file, you need to create two CSS files.

![](.guides/easy/04-linkcss/result.png)

- create 2 CSS files (you can name them any way you like)
- inside the first CSS file, style the <ul>
 unordered list
- inside the second CSS file, style the <ol> ordered list
- add the 2 elements into your `index.html` file that links each of these files

To save you time, you can copy and paste the following code into your new CSS files

```css
ul {
  list-style-type: square;
}
```

```css
ol {
  line-height: 2em;
}
```

#Saving your work
If you want to move to another challenge then you can save what you have done on the current challenge by clicking the link below.

[**SAVE MY WORK**]()  cp ~/workspace/main.css ~/workspace/.guides/easy/02-inline && cp index.html ~/workspace/.guides/easy/02-inline

To restore it, click this link

[**RESTORE MY WORK**]() cp  ~/workspace/.guides/easy/02-inline ~/workspace/main.css && cp ~/workspace/.guides/easy/02-inline ~/workspace/main.css



---
title: "Position a <div>"
files: []
editable: false
layout: ""

---

---
title: MODERATE
files: []
editable: true
layout: ""

---
1. [2 Columns, fixed width]() - designing a 2 column layout that is page centered.
1. [2 Columns, variable width]() - a 2 column layout with columns expanding to almost fill the page.
1. [What's wrong here?]() - we've got a layout issue that is not quite working. Sort it out!
1. [Make the whole div a link]() - we have got a <div> with an image and some text with a link on it. Make the entire <div> clickable.
1. Web Font
1. Font Awesome Icons
---
title: "50:50 panels"
files: []
editable: false
layout: ""

---

---
title: "Fully clickable <div>"
files: []
editable: false
layout: ""

---

---
title: "Floating <div>s"
files: []
editable: false
layout: ""

---

---
title: HARD
files: []
editable: false
layout: ""

---
1. [CSS Button that is fully clickable]() - create a CSS based button where the entire button is clickable, not just the text.