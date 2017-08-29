
Instructions

Create two new GitHub repositories and name them Responsive-Portfolio and Bootstrap-Portfolio.
Clone these repositories to your computer.
Copy the contents of Basic-Portfolio (your first homework solution) and paste the mentioned files into Responsive-Portfolio.
Note: Be sure not to include any dot files (e.g. .git, .gitignore) from the Basic-Portfolio repo.
If you chose the Skeleton exercise for your first homework assignment, contact a TA, who will provide you with a template for your portfolio.
Assignment One Instructions - (No Bootstrap)

Inside your Responsive-Portfolio folder, find your styles.css file. You will write your media queries at the bottom of styles.css.
Use three @media screen tags, each with one of these max-widths: 980px, 768px and 640px.
You use 980px because you never want any of the content to be cut off. Since the desktop layout is about 960px wide, you want the media queries to kick in before your content gets cut off.
768px is about the width of a tablet and 640px is about the width of a phone in landscape.
Make the layout match the following screenshots:
index.html: 980px, 768px, 640px
portfolio.html: 980px, 768px, 640px
contact.html: 980px, 768px, 640px
Make the position of the header static (the default positioning) when the screen is 640px wide. The header design takes up a lot of room; you don't want it to stick to the top of a small screen and leave no room for the rest of your site.
Be sure to include the viewport tag in all your HTML files, otherwise your media-queries won't function as expected on mobile devices. (Hint: You won't need to use exact pixels for anything other than the container)
Protip: Use the Chrome extensions Window Resizer and Browser Width to see the browser dimensions in Chrome.
Deploy your new portfolio (now with media queries!) to GitHub Pages.
Assignment Two Instructions (Bootstrap)

Inside your Bootstrap-Portfolio repo, create index.html, portfolio.html and contact.html.
Using Bootstrap, recreate your portfolio site with the following items:
A navbar
A responsive layout (remember the grid, rows and columns are your friends)
eg. On xs and sm screens, each section should take up the entire grid. On m and larger screens, each section should take up 2/3 of the grid and the sidebar should take up 1/3 of the grid
Responsive images
BONUS Using Bootstrap, make a sticky footer and use sub-rows and sub-solumns on your portfolio site (Hint: Check out the Bootstrap documentation)
