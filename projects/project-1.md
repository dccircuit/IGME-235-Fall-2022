# Project 1 - "One Page" Responsive Website (in two parts)

For this project, you will select an appropriate topic (a list is below) and create a website beginning with a "build to spec" phase followed by an "adapt to content" phase.

## About the Overall Project

### Potential Topics for this project:
- a personal web portfolio.
- a web page that supports a personal project.
- an in-depth page about a personal pursuit such as a favorite game, hobby, or cause.
- something else that you've discussed with your instructor in advance (send a Direct Message to your instructor via Slack to get the 'ok' for the topic).  The scope of the topic and the existance of visual media to use on the page are key factors.

### FINAL Project 1 General Requirements:
- It must be a "one-page" site that you scroll up and down through to see the _majority_ of the content.
  - It is allowed to create a few "more info" type pages that support information that is already visible on the main page. 
- It must include a navigation system that allows the user to automatically scroll up and down the page by clicking navigation links/elements.
- The page must be responsive to mobile widths with a layout that changes (not just stretches/squishes) between desktop and mobile.  It must also not get overly wide (set a maximum width as well). 
- It must use Flexbox and/or CSS Grid for layout purposes.  No usage of CSS Frameworks for this project.
  - It would be acceptable to use a simple CSS reset file, but not Marx or other (although simple) frameworks.
- Files will be stored in a pre-defined file structure:

Here is an illustration of the file structure you should use:
![Project 1 File Structure](_images/Project1Structure2019-235.png "Project 1 File Structure")  
```
	project1
		index.html (where the final version of your project 1 will live)
		spec.html (your phase 1 will be at this location and should not be changed after submission)
		css (probably only two files here, one for phase 1, one for phase 2)
			spec.css
			final.css
		media (all images, videos, fonts, etc present on your pages, including favicons if you make a custom one)
			image1.jpg
			image2.jpg
			any files (convert to woff/woff2) that support the embedded fonts (if any) on your pages.
		other.html (any other html pages... perhaps a few extra pages that give you "read more" info about a subject)
		src (for files that support your design but aren't actually referenced from the final version)
			source.pdf
			responsive.pdf
```

### FINAL Design Expectations:
- Your page must ultimately have a pleasing layout and design that demonstrates:
  - All four so-called "CRAP" principles.
  - Clear visual hierarchy, good use of white space.
  - Thoughtful choices of colors and other visual elements.
  - Effective typography with typefaces that are clear, legible, and appropriate for the content.
  - An appropriate custom link style (visible somewhere on the page -- put a small link in the footer if you don't have another place to use it)
- The user visiting your page should experience a compelling initial "landing" that pulls them in and orients them to where they are and where they can go.

### FINAL Content Requirements
- Include multiple images of at least two different sizes.  They should be relevant to the chosen topic, of course.
- Demonstrate some kind of layering, such as a background behind a foreground element, or text that appears over an image.  A colored background behind text is not enough to meet this requirement.
- All text must be added as actual text characters in the HTML, no adding text to an image with Photoshop.
- Your final design must "adapt" to accomodate as much information as necessary to fully cover your subject (see more in the "Phase 2" expectations).

## About the Two Separate Parts/Phases

### What's required for Part 1 (the "build to spec" phase)

Web developers commonly work in a team with others such as Content Strategists, User Experience designers, and Graphic Artists.  For the first phase of this project, we will simulate that by asking you to recreate a design that some other Graphic Artist has already created and "published" in print.  It's not always true that a printed design can be fully reproduced on the web, especially when you start to take varying browser and device sizes into account.  But for this first phase of the Project, you should aim to get as close to the printed design as you possibly can, while still thinking about how your page will need to adapt in the 2nd phase to add responsiveness and greater page length as you pour your own content into it.

#### What to do:
1. Select one of these pre-chosen page layouts:
	- 1
	- 2
	- 3
	- 4
	- or submit your own pdf as part of your proposal (See tips below about what's "challenging" enough).
1. Mirror (as closely as possible) the design of your chosen design/PDF through HTML & CSS.
	1. Start by sketching (perhaps by drawing right over your starting image) where your grid lines are going to go.
	1. Build an HTML file (call it spec.html) that will work well with your sketched out plan... Add special sections, divs, figures, etc.  Whatever you need.  Think semantically as often as possible.  Include ids and classes that will work well with the style rules you need to write.
    	- Don't copy the body text word for word, use "lorem ipsum" text where you have blocks of words to fill in. 
  	1. Write the CSS (including, early on, the Grids and Flexbox containers that you'll need).  Make sure to get sizes on your images quickly, too.
    	- You don't need to use the exact images from your design, but similar ones would be best.  Do your best to select a similar font, color scheme, and matching layout.
1. Determine (how your page should adapt to narrower layouts). 
	- Sketch a plan for what will go where when the page is narrower.  This can be mocked up in an image editor or drawn on paper and photographed with a cell phone.  You'll include this along with your zipped up files and link to your spec.html file in your project1 directory.
	- Optionally, you can begin to implement a mobile version of your spec at this stage.  We will primarily care about the wider layout at this time, however.
1. Submit everything to the assignment dropbox:
	- A zip of all of your project 1 files (including all resources and reference images).
	- A direct link to your "source" PDF that you've put into your project 1 directory on banjo (so that we can compare before and after).
	- A direct link to your "spec.html" page. (once submitted, you should make no further changes to the spec.html or the CSS that styles it -- we will want to compare it to your FINAL project 1 page.)
	- An image of your sketched plan for how to add responsiveness to your page.


#### What's Challenging Enough for a Phase 1 layout?
- The design should have a 1 or 2 column layout that makes some sense for web page design.  (typical multicolumn newpaper layouts do not, unless each column starts something new and are not just a continuation of a long article over multiple columns). 
- Should have potential to be made "responsive"... You'll plan out in a sketch what will go where when the page gets narrower... All content should still be present, but incidental images may disappear or resize, order of information may change, etc.
	- Consider how the design will "lengthen" as the page becomes taller with more content/articles/sections.

### What's required for Part 2 (the "adapt to content" phase)

For Phase 2, you'll copy your spec.html file to index.html and make changes as appropriate with new text content, images, colors, and appropriate layout modifications/additions to work well with your chosen content.

1. You've already thought about the responsive part and submitted a plan with Part 1
	- Use Media Queries to enable and disable CSS as appropriate to make the page adjust it's layout at different sizes.
	- An excellent project will look good any any width from "desktop wide" to "mobile narrow", but we're mostly interested that a version at mobile phone width still works well and provides all content that a desktop version has.
	- Consider how the design will "lengthen" as the page becomes taller with more content/articles/sections.
2. Put your own content into the design.
3. Make sure that the initial design 
	







## Overall Requirements


Your main page for the site that you create will be the index page for this directory. You must have css and media directories to store the associated files. **Remember:** Our server is case sensitive, so your files **must** use the case indicated in this assignment. If your files are not named and located as instructed, we can't find them, and you will get a 0.



A page named index.html located in the "project1" directory in your 235 directory on banjo that includes
  - A navigation system to allow the user to quickly access distinct content.
  - A design that in the prototype stage, mimics that of one of the provided PDF files OR one that you've had approved during the proposal phase.
  - A design that in the final deliverable phase is based off of the previous prototype but with changed images, colors and layout as necessary to expand the page and make it a full treatment of the topic you've chosen.


  
## Design Requirements
- The site is [responsive](https://en.wikipedia.org/wiki/Responsive_web_design) and, ideally, a [single-page design](https://en.wikipedia.org/wiki/Single-page_application).  
- You may use additional pages, but only for "further details" type content. For example for a more detailed explanation of a personal project that was already introduced and explained on the first page.  Just a "thumbnail" link from the front page to a deeper page with the "real information" is not acceptable.


	
## Technology Requirements
- Semantic structural tags like `<header>, <section>, <main>, <nav>`, and `<footer>` should be used appropriately.
- Try to use a consistent structure on your page(s) by repeating many of your design elements - for example: the `<header>, <footer>` and `<nav>` elements should be in the same places on each page/section and have the same colors, fonts and spacing.
- Reasonably valid HTML - Any error or warning that could easily be addressed should be addressed - focus on errors, less on warnings. 
- CSS selectors and rules will be used for formatting and positioning.
- Most (if not all) of the style rules will be located in an external style sheet.
- There will be at least 10 style declarations (rules) in your external style sheet.  Use _class and ID_ selectors as appropriate.
- Utilize custom link styles on all your pages by utilizing the `a:link, a:visited, a:focus, a:hover,` and `a:active` selectors.
- Reasonably valid CSS - see note for HTML above.
- Images and other media are properly optimized (both file size, image format, and image dimensions) for screen display

## Documentation Requirements - documentation.html
- Original Source PDF (whether provided or chosen)
- Sketch of Layout grid and intended mobile version.
- Completed HTML/CSS of Design2Spec.
- Include links to all resources (images used, sources of written content if not yourself, fonts used, tutorials referenced, etc).
- Describe the 'goal' for your site, who is your audience, and how these informed your choices about design/organization.
- Any other notes about your project that you'd like to draw our attention to... Ways in which you went 'above and beyond' expectations, perhaps?


------------ I'm kinda down to here -----------------------




## Submission and Due-Date
The site must be placed in the project1 directory inside of your 235 directory (`http://people.rit.edu/youruserid/235/project1/`).  (Later, if you wish to make this portfolio your public portfolio for prospective employers to look at, we recommend that you move it to a different URL (not within your 235 subdirectory, such as http://people.rit.edu/youruserid/portfolio or just http://people.rit.edu/youruserid), but you should wait until you get feedback and a grade for the course)
- You should have a prototype version of your portfolio posted to your banjo account (at the URL above) by the date of the Project 1 Prototype Assignment on myCourses.  Include this link in the comments field.
- ZIP and upload your portfolio files (so far) as well.
- Your final submission must also include the URL to your online documentation in the comments field of the dropbox.

## Grading

The Full Grading Rubric will be attached to the "Final Submission" Assignment.  Here is an overview:
 
  Requirement | Possible Points (100%) |
----------- | --------------- |
Required content present | 15% |
Responsive Design | 15% |
Visual Design | 10% |
Typography | 10% |
Navigation System | 10% |
Semantic, valid HTML | 10% |
Well-structured, valid CSS | 10% |
Documentation | 10% |
File Structure | 5% |
Properly optimized media | 5% |

## Future version notes:
Later (at the end of the semester), you will add:
- Real work examples.
- Your Resume if you didn't add it previously.
- Any additional design elements and/or interactivity that you wish to add.

Also:
- You should correct, adjust, and/or improve (if possible) any elements that were noted by your TA or Instructor in your evaluation and/or video feedback.
- You should consider *removing* your documentation link if it doesn't present your portfolio design in the best light.
- You should be prepared to move your portfolio to a better URL.




Previous Design2Spec:

# Homework: Design to Spec

## I. Overview
Web developers commonly work in a team with others such as Content Strategists, User Experience designers, and Graphic Artists.  For this homework, you are being asked to recreate this design that a Graphic Artist built in Figma (an interface design/prototyping tool).  Your Goal is to use HTML & CSS (but no frameworks such as Bootstrap or Materialize) to realize this site as a functional web page.

## II. Requirements
You are to recreate this design:
![Website Mockup](_images/designtospec2020.png)

This is decidedly NOT a Homework for you to exercise your *design* creativity. (maybe your coding creativity, however)

You will be graded on how close you are able to get your page to the appearance of this image.

Source image files, fonts, and a palette to work with are available here: [DesignToSpecAssets.zip](DesignToSpecAssets.zip)

This is an individual project, and since everyone is doing the EXACT SAME design, you should guard your code carefully so that it is not made available to others.  There is enough ambiguity in the design and the ways that it gets implemented that everyone's project can certainly be unique.

The only requirements about the way that your design is implemented is that it must use either Flexbox, CSS Grid, or (most likely) both of them to do page layout.

You must also use valid, semantic, HTML & valid CSS stored in an external css file.

The Graphic artist has NOT specified a certain design for mobile, but they would definitely *like* to see you provide a Responsive Design solution that works well.  Responsiveness will be worth up to a 20% bonus to your score, so focus first on the 'wider' version of the page.

The Graphic artist has also NOT specified certain behaviors on the page such as link colors or rollover states.  You're free to make your own determinations, but don't go far outside of the provided color palette. 

QUESTIONS?  It is not uncommon to need to ask questions of the Graphic Designer so that you get the clearest understanding of the spec.  For the purposes of this assignment, the Graphic Designer will be your course Instructor and spec clarification questions should be asked in YOUR SECTION'S Slack channel.  You can still ask general HTML & CSS questions in the shared #questions-html-css channel on Slack, but always be careful not to share your (complete or mostly complete) code to the rest of the class.

If you run into trouble and wish to seek help with a specific question that requires the sharing of your code, do so through a DM to your Instructor.

## III. NON Requirements
- You do not need to guess at page colors.  They are all (except for white and black) specified in included color palette.  
- You should attempt to match the fonts by using the included Font files... Both of which are free to use as web fonts.  You do, however, need to go through the process of converting them to web fonts.  Try using an online convertor such as [Font Squirrel](http://fontsquirrel.com) to do so... Examples of using them will be in the zip that you download as a result.
- You may use any SVG axe icon in the top header of the page.  There are many free downloadable SVGs on the web for you to pick from.  See note in the zip file for a possible source.  You should still make it white, however (try to do so in the SVG code).
- It is not necessary to crop the images in exactly the same way as the original images, however, we are providing the original images so that they can match more easily.  Don't use the uncropped/high-resolution full-size images.  A 2.1 MB jpg for your footer is TOO BIG.
- There are no specific pixel dimensions for items on the page.  You're probably best off specifying most elements to be flexible in size and/or based off of the rem unit.
- You should use the same heading texts that we provided, however you do not need to use the same placeholder text.  Use VS Code or another tool to generate "Lorem Ipsum" text for you to hold the spaces open.  Tip:  In VS Code, just type `loremNN` where NN is a number of words that you want followed by Enter, and it will generate a block of text for you.

## IV: Submissions
- You should post your Homework in a subdirectory of your 235 page.  Use a unique folder name (there should be no way to get to it easily from your 235 Home Page).  Zip your files together and upload them to the assignment on myCourses (when it is created), and include a URL to the live version of your page in the comments field.

	---------- stuff to save:
	
	
If you need to use placeholder text we recommend using the lorem command in VSCode.  However, if you wish to use images/videos/links for mock-up purposes beyond those that come from the original PDF layout files, see the following options:

| For placeholder screenshot images, you may use a web service such as https://placeholder.com or https://picsum.photos/ 
| For placeholder video, there are quite a number of them available on YouTube by just searching for "Placeholder Video"  For example:  https://www.youtube.com/watch?v=ScMzIvxBSi4 (has sound) and https://www.youtube.com/watch?v=eEzD-Y97ges (has no sound) |
| For links, you can make a link that appears clickable but goes nowhere (except back to the same page) by putting "#" in the href attribute.  Prevent the jumping back to the top of the page if you want by using this technique: https://stackoverflow.com/a/33285939 (Involves Javascript) |
