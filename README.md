# UdacityNotes
My notes from Udacity´s Intro to Programming

##Basics on the Web and HTML

###What is the web?
It is a collection of HTML (Hyper Text Markup Language) documents. 
You can find anything on the web: plain text, HTML, images, videos, music
HTML: basis for every web page; it glues everything together
Hyperlink: the links between pages or links for short 

Major Pieces:
•	Computer + Browser: browser makes requests via the Internet through servers; requests that use a protocol used HTTP . It is a program that runs on your computer to display files found on the web.. 
•	HTTP: is a protocol that computer uses to communicate with the Internet. 
•	The Internet: world’s larges computer network 
•	Servers: they are computers that host files that make up the web

HTML

•	HTML documents are the hard of the web
•	HTML is made up of 
o	Text content – what you see
o	Markup – what it looks like
•	It’s made up of tags <> opening tag Contents </> closing tag The structure is called element
•	For bold: <b> content </b> (inline)
•	For italized <em> content </em> (inline)
•	If you forget to close a tag everything after the open tag will be like that
•	HTML Attributes (for links) (inline)
o	<Tag attr = “value”> content </tag>
o	Anchor <a> - link
o	<a href="www.reddit.com”>derp</a>
•	Images <img> they don’t have closing tags
o	<img src=”url” alt =”text”>
•	For breaks in lines use <br> content</br> (inline)
•	For a paragraph <p> content </p> (block)
•	Span / div 
o	Span is inline <span class=”foo”>
o	Div is block <div class=”bar”>
o	Reference to other documents – e.g. images + videos 
o	Links to other pages 

1 - What a Web Page is
A web page is a text document written in a language called HTML. Web browsers read these documents, and then interpret and display them.

2 - How Coding Works
Coding happens when programmers write text in a language that a computer can understand. The computer can then follow the instructions the programmer wrote. For example, the computer might do this by making text like this:
I'm <b>learning</b> to code!

3 - Computers are Stupid
Programmers need to write exactly the way a computer understands (also known as writing with correct "syntax").
For example, if you forget to close a <b> tag, the computer won't be able to figure out what you had intended to make bold. This "stupidity" can be very frustrating, but it also gives programmers incredible power: if you know how to talk to a computer than you can tell it to do anything you want.

4 - Programmers Can't Remember Everything
There are too many details to keep everything in your head. And that's okay. If you forget how to make text italic in HTML, you can always just look it up.

5 - Basic HTML Vocabulary
You will be using HTML in the next few lessons, so it will be helpful if you're comfortable with the jargon.
•	Tag: An HTML tag is always contained within angled brackets. Most tags have an opening tag (<p> for example) and a closing tag, (</p>). Some tags (called "void" tags) do not require a closing tag (like the <br> tag).
•	Element: An HTML element refers to everything within a set of opening and closing tags.
Attribute: This is a property of an HTML element. For example, to set the href attribute of an anchor tag to the Udacity URL, you would write <a href="www.udacity.com">


