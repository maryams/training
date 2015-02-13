## Introduction

To begin with, and while our projects are relatively lo-tech, we will develop on a system called JSBin. JSBin is a website that makes websites: it allows you to write html, css, and javascript on an online environment that automatically combines the three and instantly updates the result. JSBin hosts all of your work with a unique URL meaning you can come back to a project anytime from any machine. 

- <a href="https://github.com/join" target="_blank">Get a GitHub account</a> - We'll come back to this later, it's good to connect this to JSBin early. 
- Open <a href="http://jsbin.com/locamo/latest">this reference page</a> and click through to your development environment.
- Set up a JSBin account using your GitHub details and take ownership of the bin!

### Contents
1. [Basic Principles of Web Development](#basics)
2. [HTML](#step-1)
3. [CSS](#step-2)
4. [Responsive Design](#step-3)

## Basics
#### You're Better than binary!
- Coding can often be frustrating, but at the same time, getting something to work and look how you intended can be an incredible feeling. However, don't be fooled into thinking that it's all just a case of your code working or not. 
- Always take the time to understand what you're doing as you implement it. Try to get to a place where you can repeat what you just did and explain it to someone as you go along. 
#### Readability is, like, super, super important.
- Your code may be fancy, your website may look beautiful, but if nobody, not even you can come back to it and make changes: you're a bloomin' liability.
#### Don't Stop Learnin'
- Push the boundaries of what's possible. Be creative: the only limitation is your own engenuity!

## Step 1
### *HTML*

HTML is Hypertext Markup Language. It is the bare-bones framework that describes the flow of every document you will find on a website. 
HTML is a descriptive and instructive language which defines what things you want to go where on your website. It doesn't care about white-space or indentation or line-breaks and it should *never* (except for some very rare circumstances) contain logic or styling.

## Step 2
### *CSS*

CSS is Cascading Style Sheets. It takes this form:

```
selector {
    property: value;
    another-property: value;
}
```
Selectors can be an element, a class name, or an ID.

The C in CSS reflects the importance of ordering your style declarations correctly. A parent element's styles will cascade down to a child's styles, and a declaration using a selector at the start of the document will be overwritten by a declaration on the same selector at the bottom. 

#### Take-aways
- Learn to use selectors at the <a href="http://flukeout.github.io/">CSS Diner</a>
- <a href="https://developer.mozilla.org/en-US/Learn/CSS/Basic_text_styling_in_CSS">Text-styling with Mozilla</a>

## Step 3
### *Responsive Design*

There is so much to be said for responsive web design it can make your head spin. Responsiveness is a fundamental ingredient in modern web design. Gone (well, gone soon) are the days of mobile sites for mobile devices and web sites for computers. Now, if your site doesn't work on as many devices as possible your site ain't shit, buddy!

<a href="http://blog.froont.com/9-basic-principles-of-responsive-web-design/">This blog post from Froont</a> is a great place to start to get your head around what it means for a site to be responsive.

#### Frameworks
- [Twitter Bootstrap](http://getbootstrap.com/getting-started/)
- [Concise](http://concisecss.com/get-started/)
- [Foundation](http://foundation.zurb.com/)
