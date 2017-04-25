# ChickTech- April 29, 2017

## Let's get to know one another:
- What's your name?
- What are two things we wouldn't know about you at first glance?

## Things to keep in mind:
- We are here to help you and we are excited to be here.
- With that in mind, ask as many questions as you can.
- No question is off limits, no matter how silly you may think it is.
- If you're a visual learner or you need something re-explained in a different way, let us know.
- This may be new for you, but we fully believe you can learn it.
- Question the process- don't just take our word for it, ask "but why?" as many times as you want.


## What is front-end web development?
- Everything your eyes can see on the page.
- Composed of HTML, CSS, and JavaScript.
- A front-end developer will take the work of a designer, and code it on the front-end so a back-end developer can build on top of that.

### What is HTML?
- Stands for: Hyper Text Markup Language.
- It is the content of the page.
	- e.g. header or paragraph
- Has its own default styles.

### What is CSS?
- Stands for: Cascading Style Sheet.
- It is the stylistic component of the page.
- Overrides the default styles of HTML.
	- e.g. change the color or the font-family of your header

### What is JavaScript?
- Helps increase interactivity of the page.
- Helps with page interactions such as animations.
- Helps with dynamic loading of content.

## Let's Dive Deeper
### HTML:
#### Tags < >
- Allow you to set up structure of the page.
- Tell the browser how to format content.
- Important block elements to start you off: h1-h6, p, ul/li, hr.

`<h1>Hello World!</h1>`

#### Basic layout for an HTML file

```
<!DOCTYPE html>
<html>
	<head>
			<meta charset="UTF-8">
			<title>My First Webpage</title>
	</head>
	<body>
			<h1>Hello World!</h1>
	</body>
</html>

```
### CSS:
- In order to run external CSS you need to link it to the HTML. This goes in the head tag:

`<link rel=“stylesheet” href=“style.css” >`

#### Basic layout for a CSS file

```
h1 {
	color: #FF9966;
	text-align: center;
}

```
- Series of key value pairs
- Important CSS attributes to get you started: color, background-color, font-size, font-family, text-align, height, width.
### What about different ways to organize content?

#### divs:
- Define a division.
- They are equivalent to empty rectangles.
- They are used to format block elements that can be styled via CSS.

	`<div> </div `

#### spans:
- They are inline elements that are normally displayed without line breaks.

	`<span> </span> `

- Other important inline elements to start you off: img, a.

### Id's versus classes
#### Id's:
- Are selectors.
- They are used if you want a single, unique element.

HTML:

```
<div id=“header”>
	<h1>Welcome to my website</h1>
</div>
```
CSS: hash/pound sign designate an id

```
#header{
	text-align: center;
	color: red;
}
```


#### Classes:
- Are selectors.
- Select an element with a specific class attribute.

HTML:

```
<div class=“paragraph”>
     Here are my favorite hobbies: reading, hiking, and scuba diving.
</div>
<div class=“paragraph”>
     My favorite films are: Life is Beautiful, Life of Pi, and Lord of the Rings.
</div>

```
CSS: a period designates a class

```
.paragraph {
	color: green;
}

```
### JavaScript:

## Summary
- HTML, CSS, and JS work together.
- What do you think is happening on the back-end?