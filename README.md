# React Developer Curriculum - ALAB 320H.1.2 - React Fashion Blog

## Learning Objectives
- After completing this lab, learners will have demonstrated the ability to:

- Create an HTML/CSS page from a given mockup.
- Convert an HTML/CSS page into React.
- Style React components to create a desired layout.

## Instructions
In this assignment lab, we'll be creating a Fashion Blog in React.

Build this site locally in plain HTML. Don't use React yet.
Push the site to GitHub, and deploy it on GitHub Pages.
Remake the site with React, and deploy it to Netlify (instructions below).
In the GitHub ReadMe file for your React Application, remove all of the React boilerplate information and replace it with the following:
# [Netlify Live Link](Netlify link here)
# [GitHub Pages Live Link](GitHub Pages link of HTML version)
# [GitHub Link of HTML Version](GitHub link for HTML version)
Submit the link to the React version GitHub repository to Canvas.

## Deliverables
A link to a GitHub repository that contains your completed lab with no errors (comment things out if they do not work).

## Build the HTML
We'll walk you through some of the steps necessary for this portion of the project. You should already be familiar with most of this process.

Create your html boilerplate in the index.html file.
Add a new file called style.css and link it to the HTML file.
In the body of your HTML, use <header>, <main>, and <footer> tags to clearly define the different parts of the page.
Use an <h1> tag for the site title and an <h2> for the subtitle inside the page header.
Use <nav> tags inside the page header to create an accessible navigation. Follow the example in the W3C Web Accessibility Initiative (WAI) Guidelines to format your navigation:

Wrap each link in an anchor tag.
Wrap each anchor tag in a list item.
Wrap all of the list item tags in an unordered list tag.
Place the unordered list inside the the nav tag and give it attributes for aria-label="Main Navigation" and role="navigation".
Mark up both of the blog posts using the <article> tag.
Use this W3C WAI Guideline example to help you structure your blog post content. Follow the pattern! Make sure there is a <p> tag that contains some lorem ipsum text (remember, you can create this with Emmet by typing p>lorem and pressing tab)!
Make sure your images all have alt attributes so that they are accessible.
Inside the page footer, use the same technique you used earlier to create a semantic and accessible navigation, using a wrapping <nav> tag, unordered list, and the aria attributes.
Add a copyright in the <footer>. For the © symbol, use an HTML entity.
Make sure to add and commit your changes when you've got the HTML done!


## Style with CSS
Use a border only on the left side of the page's <html> element. It should have a width of 5px and a color of lightgray.
Set the <body> element's min-height to be at least 100% of the viewport height. Also, use the font-family property to set the entire page to use sans-serif fonts.
Give the <body> a max-width of 1000px and center it on the page with the margin auto technique.
The border is too close to our text and we've got an issue with margin-collapse at the top of the page! Add padding to the <header>, <main> and <footer> elements of 1rem on the top and bottom and 2rem on the left and right to fix these issues.
For the <h1> on the page we want the color to be tomato.
Set all of the images to have a width of 100%.
For your site navigation, you'll need to remove all of the padding on the <ul> elements and then set it's list-style-type to none. It would be a good idea to use a class to style the navigation so that you can still make a bulleted list on your page. Use Flexbox to style the <ul> for the navigation elements. On the top navigation use the space-between rule to have the menu items spread across their container evenly. Set the color for the anchors inside the main navigation to be lightgray and the footer navigation to be tomato.
Style the title of each of your blog posts so that they are larger.
Style the 'continues...' anchor tags so that they are aligned to the right and are bold and tomato colored.
Set the margin on the bottom the <article> tags to be 4rem. Also, add a 1px solid border in lightgray to the bottom of each one and give each padding on the bottom of 2rem.
For the <p> tag inside your <article>, use the pseudo-element ::first-letter to style the drop cap and set it's color to lightgray.
Style the copyright so it is lightgray.
Awesome job, add, commit and push changes to create your pull request!


## Convert to React
Now, you're on your own.

Remake the entire project in React, and deploy it to Netlify, as shown below.

When you're finished, you should have component files for App.js, Header.js, Nav.js, Article.js, and Footer.js.


Deploy on Netlify
Link GitHub to Netlify for free.







Run the build command in your app in the command line (for the React app only).

npm run build
Drag and drop the application folder from your computer into Netlify.






