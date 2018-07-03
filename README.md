# project0

## Description of my Project0
My <Project0: Homepage> is my personal blog. I hope I can use this webpage not only for a temporary assignment but as an unofficial resume. There are 4 pages; introduction, biography, photography, and Tokyo guide.


## What's going on here?
### intro.html
It is the main page, it can be divided into the 4 section; header, nav(navibar), article, and footer. In nav section, there are links connecting every page that I made. Article section has my picture and a short paragraph about who am I. Some important keywords are linked to the homepage which is related to them. In the footer, I put my personal contact and used ":mailto" command so that visitors can send an e-mail in an easier way.

### bio.html
I don't think this page fits with 'biography' of mine, but I couldn't find any appropriate word, so I chose to use this term. The header shows the title of this page and nav is just same as intro.html. No more footer from this point because I don't think need that in here. In article section, there are two components: The first one is a grid model listing some keywords that are related to me. Every column has the same size, and center aligned. The second one is a table that shows my education track. They don't have any lines because I think it is better, yet all of the elements are clearly divided.

### photo.html
In this page, I've used the Carousel, a component of Bootstrap 4. There are three carousels work exactly same way. With this, I can show lots of pictures in more clean and ordered way. I put some information right downside of the photo, where and when and with which camera I took this photo. Also, in the last of the page, I put a comment that the copyright of all of the photography is on me.

### tokyo.html
I thought to introduce my city to everyone is worth to try. I've used Collapse, Accordion component from Bootstrap 4, and made a change that the font color of the titles(links) into the black. At first, I tried to write the information by myself then I realized that it probably cost more time than to make whole the homepage, so I just scrapped from one of the famous tour guide sites and put references. Also, in the last of the page, I put a comment that the copyright of all of the photography is on me.

### style.scss and style.css
1. I wanted to apply my home university main color(#3f4099) into some parts, such as header, some titles, and link(hover). So I put $color tag so I can easily change it in anytime. 2.
2. Also, using %padding I can easily apply the same amount of padding, to header, nav, and footer sections.
3. The most hardest part in this file was the symmetry of nav and article. I've tried almost every percentage around 20/80 to 40/60, and finally I added max-width tag on nav section, I think it's now more sexier.
4. With @media query, when in a smaller screen(less than 640px), nav goes upside of the article section. I've tried to make it better by adjust the text-align and line-height.

## additional information
Actually, I asked a question on the Slack page about how I can apply layout so that I don't have to repeatedly input the nav section in the head of every page. I got a response from Professor David J. Malan to use Jekyll to solve it, and I tried but failed. In the future, I want to improve it by applying Jekyll.
