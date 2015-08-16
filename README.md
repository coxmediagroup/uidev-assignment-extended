# uidev-assignment

This is an HTML/CSS assignment for UI Developers interviewing at Cox Media Group.  As a CMG manager, I want to gauge your skill, code completeness and accuracy, as well as your affinity for standards-based development.

This assginment requires knowledge in the following areas:

- HTML5
- CSS3
- Bootstrap framework
- Less preprocessor
	- modifying some global variables and recompiling the bootstrap CSS files.
- Grunt or other task-based command line build tool of your choice 
	- you will be removing all Javascript components not being used and recompiling the Bootstrap JS files.
- AngularJS
- Google fonts

##Assignment criteria

Create a responsive webpage based on the graphical mockups provided.

-	Using the provided feed data, construct a page that is formatted to match the included mockups located in the comps folder.
- You will only be using one HTML document for this assignment.
- Place your HTML in index.html. All other resources should be saved where appropriate in the uidev-assignment folder hierarchy.

###Directions:

####Feed data

Your page should load data, into the More Stories content area of the page, from the provided datafile. No content should be hard-coded into your document.  

uidev-assignment/js/uidev-assignment-data.js

You will render the headline list content are of the web page via an Angluar directive (ng-repeat).  Use the Angular directive ng-class to format the background color of the list.

####Design attributes

- For most visual elements, you are provided with details on styling below. 
- Other visual elements that are not detailed below will require you to use your best judgement to match the mockups provided.
- Place all CSS in the external stylesheet unidev-assignment/css/styles.css.

####Fonts

Use the Google font Oswald for the web page headers.  Use the default Bootstap framework font for the web page body text, however change the default font size for the body to 16px.  This will require changeing a global variable and recompiling your bootstrap CSS file.

####Evaluation of assignment

You will be evaluated on your HTML, CSS, and JavaScript code quality as well as your attention to detail in completing the code test.


####How you should deliver your completed assignment

The preferred method of delivery via github. Publicly fork this repository, complete the assignment, then send a pull request. If you require an alternate delivery method, please contact your hiring manager.

####Anything else?

You should commit your progress often and write clear and informative commit messages.
