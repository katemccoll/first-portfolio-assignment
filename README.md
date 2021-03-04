# Homework 2 Portfolio
Create a Portfolio from scratch

## Acceptance Criteria


```
GIVEN I need to sample a potential employee's previous work
WHEN I load their portfolio
THEN I am presented with the developer's name, a recent photo, and links to sections about them, their work, and how to contact them
WHEN I click one of the links in the navigation
THEN the UI scrolls to the corresponding section
WHEN I click on the link to the section about their work
THEN the UI scrolls to a section with titled images of the developer's applications
WHEN I am presented with the developer's first application
THEN that application's image should be larger in size than the others
WHEN I click on the images of the applications
THEN I am taken to that deployed application
WHEN I resize the page or view the site on various screens and devices
THEN I am presented with a responsive layout that adapts to my viewport
```

## Mock-Up

The following animation shows the web application's appearance and functionality:
<img src="Assets\images\02-advanced-css-homework-demo.gif">


### Screenshots

<img src="Assets\images\mock-up-2.PNG">

Notes:

Nav
- Nav Bar is a Navy-greenish colour with light teal writing and box.
- Box on left hand side has no left margin. Enter Name here
- Nav elements are underlined.
- There is a Resume link here. We can either make a button at the bottom to say download resume, or we can do that in the link. Lets do second option as that makes more sense for this.
- About Me, Work, Contact Me, Resume

Hero
- photo taking up full length.
- teal box again with margins saying cool subtitle. Here we can put the job the person is after.
- in the criteria it says to have a recent photo. I think the image size here is too slim. Otherwise there will be a small photo of the person and a lot of space around the person. Either we make it bigger or we add a photo in the about me section.

About me
- We have the heading in the side bar. Line dividing heading and content. 
- we could add the photo here, when you hover over it it could say 'about me'


<img src="Assets\images\Mock-up-1.PNG">

Work
- Once again, side bar has heading work.
- Right hand-side has images relating to the work.
- Each photo has a border around it with a box at the bottom left-side corner. 
- Tinge of teal
- When you hover over, the photo becomes clear.
- One large photo, 4 small ones.

<img src="Assets\images\Mock-up-3.PNG">

Contact Me
- Heading in sidebar with line in the middle
- Phone number, email, Github, Twitter, Spotify

Footer
- In the mock up provided, we see no footer.
- perhaps we will add one in to complete the page.

## My sketch

<img src="Assets\images\draft layout.JPG">


## Start

I have created my index.html and style.css. Before I started writing this, I had researched and started creating a portfolio that would be unique to me. But after checking with Lu (Ta), he said that I have to make the portfolio as close to the mock up. So! For fun, I have chosen a different name (Sorry Learnatino, hard lesson to learn). Michael Collins, even though he is currently retired, he is wanting to have a side hobby of being a web developer. Good on you, Mike!

I have made my basic html page by writing '!' then enter. I have linked my stylesheet and changed the title of the web page to Mike Collins - Web Developer.


### Navbar

I will just make the skeleton up, starting with the nav bar. Quickly first, I know ideally you are meant to do mobile layout first. But because we have a desktop layout, so I will make this first.

In my CSS, I have used the root element to create my colour theme for the page.

I have spent a fair bit of time playing around with the nav bar. I finally got the inner box to be on the edge of the page, but then my nav links hid behind it. I have changed my position from absolute to relative for now and will come back to this. 

<img src="Assets\images\Nav bar.PNG">
<img src="Assets\images\navbar_draft.PNG">


### Hero Image

I have gone with a space themed, some nice stars, colours go nicely with the colour theme too. 
Once I had the hero image up, I adjusted the navbar and finally got it working!

<img src="Assets\images\Hero_Nav_draft.PNG">

I was not happy about the heading in the nav bar, I reworked on this. I have it at the edge, but it is filling the height of the nav. Not what I want but will come back to this later.
I decided instead of making teal boxes for each of the headers, it would be easier just making one.
<img src="Assets\images\Hero_Nav_draft2.PNG">

Also played around with the font.
<img src="Assets\images\Font_ Verdana.PNG">


### About Me

There was two ways to tackle this. I could either do a side bar to have all of my headings in, or make a column and have headings on one side and content on the other. I went with the last one so I could control the line in the middle of heading and text easier. 
<img src="Assets\images\Adding Text.PNG">
In css, I created a grid that spanned over 90% of the webpage. Grid itself had four columns, this way i could have the heading in one and the text in the other three.

### Work

I used the same classes for my grids in the work section. This way the headings and the line between would be the same widths.

I struggled trying to get the image fitting nicely in the 3/4 of the grid. Once i got that, the four below were a lot easier to do. I had to created a box heading for each one, so reused my class for the header. 

The first work photo/project you are presented with is my own work. You click on the words and it will take you to the website I debugged. Since this is our second homework assignment, I had to put placeholder images for the other images. I have placed links on those so it will take you to google for now.


### Contact Me

This footer has the same layout as the about me section. I reused my classes for that. But instead of the content, I used a list. For now, I have placed placeholders for the phone number, email and etc. 

## End

I had a few finishing touches to do. 
First I added links to my Nav bar. This means when you click on work, it will take you to the work sections.
The resume, I have just put the google link as a placeholder. But Very easy to change when you have your resume.

I have added opacity to my photos in the work section. It stays at half opacity till you hover over it, then it changes to full opacity.

I also changed my subtitle to be a bit cooler as that is what it originally said. So I changed it to a cool Web Developer for now.

Though this wasn't in the mock up, in the acceptance criteria it did mention to have a recent photo. I assumed this meant a latest photo of yourself. I decided that it wouldn't look nice in the hero image. As it would either be cut to a part of your face, or there will be a lot of background. Instead I added a placeholder photo that goes above the subtitle. 
I do realise that the photo of Mike is not a recent one but I thought since it was only a placeholder, it wouldn't matter too much.

Lastly, the media queries! Not as easy as I originally thought it was going to be! But hey! It now works on smaller devices! YAY! 
I ended up having to changed each block of my code. Had to change the font size, directions, display and so on. 


# Results

## Desktop View

<img src="Assets\images\Final Top.JPG">
<img src="Assets\images\Final Bottom.JPG">


## Mobile View

<img src="Assets\images\Final Mobile Top.JPG">
<img src="Assets\images\Final Mobile Mid.JPG">
<img src="Assets\images\Final Mobile Bottom.JPG">