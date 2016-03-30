# Lesson 02: Hello There

## Software You’ll Need
To get started, we’ll need two pieces of software to work on our project:

First, we’ll need a text editor. And that’s exactly what it sounds like. It’s a simple program that allows you to write, edit and update text. Personally, I recommend [Atom.io](https://atom.io/). It’s free, and that’s what we’ll be using in this course to edit our text. Plus, there are a ton of really helpful addons that you can install to help you out and improve the development process. You can also use a program like Notepad, TextEdit, or other basic text editing program, but be sure you’re saving your files in raw text, not Rich Text Editing.

Next you’ll need a web browser. 

Most operating systems come with a web browser pre-installed like [Internet Explorer](http://windows.microsoft.com/en-US/internet-explorer/download-ie), [Edge](https://www.microsoft.com/en-us/windows/microsoft-edge) or [Safari](http://www.apple.com/safari/). There are some other great alternatives out there like [Chrome](https://www.google.com/chrome/index.html), [Firefox](https://www.mozilla.org/en-US/firefox/new/) and [Opera](http://www.opera.com/). You can take your pick, and use whatever you’d like.

For this course we’ll be using Chrome to view our projects.

## Let’s Jump In!
Before we get started learning the nitty-gritty of ‘how’ and ‘why’ we do HTML, I wanted to start off with some inspiration for you. Everyone loves to accomplish something and it serves to keep the momentum going. So this lesson will focus on doing HTML.

We’re going to dive right in and build our very first HTML web page.

### Project Workspace
First, let’s create a project folder where we will store our project files. In my case, I’m going to place it on my desktop and name it `fundamentals-of-html`.

Next, I'll create a new file in our folder and name it `index.html` and open it in your favorite code editor.

### Writing HTML
With our file open we'll begin by declaring what type of HTML this document will use. We do that by typing `<!doctype html>`. This is an important step as the code we're writing is specific to HTML5, and this line of code tells the browsers that's what we're writing.

HTML elements are written using "tags". Elements either "wrap" around an element with an opening and closing tag or exist in a single tag. For example: `<element>Element contents</element>` or `<element attribute="Element Contents" />`.

Lets put this to practical use by finishing our demo.

###### HTML

Start a new line, and add our '<html>' tags:
```
<!doctype html>
<html>
</html>
```
This defines the scope of our page, and tells the browser where to start and stop interpreting our HTML.

###### Head & Body
Inside our `<html>` element we'll add our opening and closing `<head>` and `<body>` tags.
```
<!doctype html>
<html>
  <head>
  </head>
  <body>
  </body>
</html>
```

I've indented my `<head>` and `<body>` tags to help me (and others viewing my code) to visualize what's going on. It's usually best practice to do that. I prefer 2 space indentation for "nested" elements. In Atom there's a preference setting for this, and other code editors typically allow you to personalize this.

