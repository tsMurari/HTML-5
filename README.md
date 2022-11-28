What is HTML?
To understand "HTML" from front to back, let's look at each word that makes up the abbreviation:

Hypertext: text (often with embeds such as images, too) that is organized in order to connect related items

Markup: a style guide for typesetting anything to be printed in hardcopy or soft copy format

Language: a language that a computer system understands and uses to interpret commands.

HTML determines the structure of web pages. This structure alone is not enough to make a web page look good and interactive. So you'll use assisted technologies such as CSS and JavaScript to make your HTML beautiful and add interactivity, respectively.

In this case, I like to break down the three technologies – HTML, CSS, and JavaScript – this way: they are like a human body.

HTML is the skeleton,
CSS is the skin,
and JavaScript is the circulatory, digestive, and respiratory systems that brings the structure and the skin to life.
You can also look at HTML, CSS, and JavaScript this way: HTML is the structure of a house, CSS is the interior and exterior decor, and JavaScript is the electricity, water system, and many other functional features that make the house livable.

HTML Tags
Since HTML defines the markup for a particular web page, you'll want the text, images, or other embeds to appear in certain ways.

For example, you might want some text to be big, other text to be small, and some to be bold, italic, or in bullet point form.

HTML has "tags" that let you get this done. So, there are tags to create headings, paragraphs, bolded words, italicized words, and more.
HTML Elements
An element consists of the opening tag, a character, the content, and a closing tag. Some elements are empty – that is, they don't have a closing tag but instead have a source or link to content that you want to embed on the web page.

An example of an empty element is <img>, which you use to embed images on a web page.

HTML elements are often used interchangeably with tags, but there's a small difference between the two. An element is a combination of the opening and closing tag, and then the content between them.
HTML Attributes
HTML tags also take what are called attributes. These attributes are placed in the opening tag and range from style and ids to classes. They take values, which convey more information about the element and help you do things such as styling and manipulation with JavaScript.

In the infographic below, the opening tag contains a class attribute with a value of “text”. This can be used to style the element or select it with JavaScript for interactivity.

Here's the anatomy of a basic HTML page:

<!DOCTYPE html>
<html>
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Definition of HTML</title>
  </head>
  <body>
    <!--Page content such as text and images goes in here-->
  </body>
</html>

Let's look at the important bits of code here:

<!Doctype html>: Specifies that we're using HTML5 in this code. Before the introduction of HTML5, you had to explicitly state which version of HTML you were coding in with the <!Doctype> tag. For example, HTML4.0, 3.2, and so on. But now we no longer need it. When “html” is written in the code, the browser automatically assumes that you are coding in HTML5.

<html></html>: the root, or top-level element of every HTML document. Every other element must be wrapped in it.

<head></head>: one of the most crucial parts of the HTML document. Web crawlers look inside the head tags to get important information about the page. It contains info such as the page title, stylesheets, meta information for SEO, and lots more.

<meta />: this is an empty element that conveys meta-information about the page. Such information may include the author, what type of encoding it's using (almost always UTF-8), responsiveness, compatibility, and a lot more. Web crawlers always look at the meta tag to get information about the web page, which will play a crucial role in SEO.

<title></title>: this defines the title of the web page. It is always shown in the browser tab.

<body></body>: all the content of the HTML document is located inside the body tag. There can only be one <body> tag on the whole page.
