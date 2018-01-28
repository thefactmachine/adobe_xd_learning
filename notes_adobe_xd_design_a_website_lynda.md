# Exererience Design Notes
This course is called **Adobe XD Design a Web Site** by Paul Trani. It was released on August, 2016.

There is a **"Designing a Mobile App Using Adobe XD as Well"**  So check out that.

```
https://www.lynda.com/Adobe-Experience-Design-tutorials/Using-graphics-from-UI-kits/492709/530129-4.html?autoplay=true

```

### Introduction
Have a look at the splash screen to begin and see the **"Getting Started With a Sample File"**

## Creating Graphics
This project is a website. We select 1280 by 800 webite. 

To pan around, hold down the spacebar and then move with mouse. 

You can clicke the label to the top right of the image and choose a label. 

Command + 0 fits the artboard to screen. 

With the pen tool you can drag the points created to move them.  To insert, just click on the line. 

You can intersect the shapes with the boolean tool. 

In the appearance panel, you can change the radius of the borders individually. 

After making two shapes to create an envelope.  Select them both and then choose group. 

### SVG Graphics
You can directly import svg graphics by using file > import. 

When you import the SVG, you can double click on it and change the color.  You can even double click again to have access to its points. 

### Import Image
If you file > import image (ie. JPEG) then you can scale the image but it will never change the aspect ratio.   But you can double click the image and then move the points on the corner in order to crop the image.  

But a better (according to the author) workflow is to create a rectangle and then drag the image into the rectangle from finder. 

You can then scale without being constrained to the aspect ration. 

## Adding Text and Effects

Add text with the text tool.  To change the size of the text, select the text box, click the circle in the lower middle and drag.  

In the properties, can change the tracking and leading. You can add fonts from Creative Cloud typekit. Its quite cool actually. 

The backround image has a black background behind it.  If you want to make the background image more darker (i.e. transparent with a black background) then select the image and then on the appearance panel adjust the slider to make the image more darker.

You can put a drop shadow on the text as well. 

**Background Blur** adds a nice frosted transparent effect to objects.  This was used on the grey bar in the middle. After selected you can adjust the bluriness. 

The glow around the logo object was created by creating a rectangle of the same size and then creating an Object Blur. 

## Creating Additional Pages
These additional pages are called artboards.  

To **deselect** something, shift plus click somewhere. 

To copy the current artboard, just click on the title on the left top and then edit > duplicate. 

Command 0 to fit everything on the same page. 

One the copied background image we want to change the back ground image.  So, we select the background image and from finder just drop on the new image. 

### Designing for different screen sizes and platforms. 
To **add artboards** for different screens press the artboard tool (underneath the type tool) and then just select the various presents on the right hand side (you can add multiple artboards just by selecting the various presents -- one after the other). 

To **organise artboards** do a command + 0 (fit all) and then drag the suckers to fit. 

You can **duplicate objects** by holding down the alt key (option) and then dragging. 

To create an I pad or mobile with landscape view select the artboard and then in the properties, there is a landscape option. 

### Using Graphics from UI Kits
Graphics for the various Apple / Google / Microsoft applications are available.

#### Adding a carrier bar
A carrier bar is all those icons at the top of a mobile screen.

Well, we just go to File > Get UI Kits and then download the appropriate set of UI kits.  I put these UI kits in my current project direction.  I guess why you have to download these is because Apple / Google etc may update these kits in the future.

To **use these*  after downloading them, just go to the downloaded file and then goto File > Open and select the most appropriate file and open.  Then just copy whatever you want accross.  You can double click on the UI kit to select a specific component. 

The Google UI did not update until I intalled the latest XD. 

## Repeating Content Using a Grid
We firstly get the home_a page and duplicate it.  And then re-arrange some of the elements to make a large space available in the centre.

We then add a large rectangle for the content.  Followed by another rectnage to fit in the picture + text elements.  Followed by another rectangle to contain the picture. 

I then select the elements that I want to repeat (image + containing rectangle + 2 text elements) and then press repeat grid.  I drag the handles down and then accross.  I select the vertical and horizontal gutters to adjust them for all.

You can also double click indvidual elements and this will then select for the entire grid.


### Adding unique images for each Repeat Grid element.

#### Adding repeating images
Select one image in the repeating grid.  Then in finder select the eight property images. Then drag the images from finder into the selected image.


#### Adding repeating property titles
We have a text file of property titles *(property_titles.txt)* and then we drag this from Finder right onto a specific title (the title does not have been selected first).  

The property titles file is a single file with 8 titles - one on each line. 

### Repeat grid for an about page
Bascially another example of repeat grid. 

### Creating multiple pages for prototyping
#### How to ungroup a grid

* Shrink the grid such that one element is showing
* Select ungroup grid (on the right)
* Select object > ungroup

You can create a **text box** by clicking on the text tool and then dragging an area and then just type in some dummy text.  Then you can just drag "Property01.txt" onto the text box and voila.


## Protyping
Designing a website for different platforms and screens is one thing..but its another thing to really experience how it works.

### A simple interation
We need to wire the home_a screen "Real Estate" "Contact" and "About" text items to screens.

To conect the "Real Estate" text box, I go into "Prototype" mode, then I select the "Real Estate" text field, then click the arrow next to that field and drag it to the "Real Estate" artboard.  After a connection has been made, you can adjust the **transition** to slide up...etc. 

#### Ease Out
This means slowly rest into place. 

#### Interaction with the logo
Just select the logo in the Real Estate page and then connect it to the "home_a" page. 

#### Dissolve from home_a to home_b
Just select the image from home_a and then connect it to home_b.

#### The start of the prototype
This has a blue tag on the top left.  To make another page the home page (i.e start page), then just select the page and click the grey box on the top right --- and it will turn blue.

#### To preview
Click the arrow on the top right of the top screen.

## Protyping an entire website
The **indvidual** sections in the **Real Estate** section can be wired to the individual pages by selecting the underlying rectangle and then wiring them up. 

### Duplicating selctions
The "Real Estate" "Contact" and "About" **that were previously wired** can be duplicated and then copies to other screens.  This **saves time** as you do not need to do any of the manual wiring up.

### Viewing all the selections
Use the **select all**


## Prototyping
There are a couple of ways of **sharing** things.

### Creating a video (good for incomplete links)
In **prototype** mode press the play button.  Then press the little circle on the top right.  Then do the various interactions.  Then press the circle on the top right to stop.  You will then be prompted for a file to save the video.

### Sharing a prototype
Press the icon on the far right (the one with the arrow key pointing up). And then following the prompts.

### Exporting artboards and assets
You can export pngs, jpegs, pdfs of the entire site.
Or by selecting individual items, you can export just a particular icon / image. 
























