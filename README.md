# uidev-assignment

This is an HTML/CSS assignment for UI Developers interviewing at Cox Media Group.  As a CMG manager, I want to gauge your skill, code completeness and accuracy, as well as your affinity for standards-based development.

This assignment requires knowledge in the following areas:

- HTML5
- CSS3
- Bootstrap framework
- Less preprocessor
	- You will be modifying some global variables and recompiling the bootstrap CSS files.
- Grunt or other task-based command line build tool of your choice 
	- You will be removing all JavaScript components, not being used, and recompiling the Bootstrap JS files.
- AngularJS
- Google fonts

##Assignment criteria

Create a responsive webpage based on the graphical mockups provided.  You will be coding only the header, menu and some of the top content on the page; not the entire page. 

-	Using the provided feed data, construct a webpage that is formatted to match the included mockups located in the comps folder.
- You will only be using one HTML document for this assignment.
- Place your HTML in index.html. All other resources should be saved where appropriate in the uidev-assignment folder hierarchy.

###Directions:

####Feed data

Your page should load data, into the More Stories content area of the page, from the provided data file. No content should be hard-coded into your document.  

uidev-assignment/js/uidev-assignment-data.js

You will render the headline list content are of the web page via an Angular directive (ng-repeat).  Use the Angular directive ng-class to format the background color of the list.

####Bootstrap framework

Your webpage will support the following breakpoints.  Make sure your page displays content correctly (as indicated in the mockups) at these breakpoints.

- 1284px wide (requires global variable change, see Less section below)
- 1024px wide (requires global variable change, see Less section below)
- 768px wide
- 480px wide

####Less preprocessor

You will be modifying some global variables and recompiling the bootstrap CSS files.  

- Add your global variable changes to the file uidev-assignment/less/variables-newstalk.less
- The following global variable changes need to be made:
	- change the gutter width to 20px
	- change the large screen width (screen-lg) to 1284px
	- change the large screen container width (container-large-desktop) to 1264px
	- change the medium screen width (screen-md) to 1024px
	- change the medium screen container width (container-desktop) to 1004px

####Design attributes

- Implement the browser tab icon located in the img folder.
- Create all visual elements of the web page based on the mockups located in the comps folder.  Use your best judgement to match the mockups provided.
- Place all CSS in the external stylesheet unidev-assignment/css/styles.css.

####Fonts

Use the Google font Oswald for the web page headers.  Use the default Bootstrap framework font for the web page body text, however change the default font size for the body to 16px.  This will require changing a global variable and recompiling your bootstrap CSS file.

####Evaluation of assignment

You will be evaluated on your HTML, CSS, and JavaScript code quality as well as your attention to detail in completing the code test.

####How you should deliver your completed assignment

The preferred method of delivery via GitHub. Publicly fork this repository, complete the assignment, then send a pull request. If you require an alternate delivery method, please contact your hiring manager.

####Anything else?

You should commit your progress often and write clear and informative commit messages.
