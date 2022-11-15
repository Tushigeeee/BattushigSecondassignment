GIVEN I need to sample a potential employee's previous work
WHEN I load their portfolio
THEN I am presented with the developer's name, a recent photo or avatar, and links to sections about them, their work, and how to contact them
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


HTML structure 
<--header-->
name 
<--Navigation bar-->
home 
about 
works
contact
<--about me -->
about my self
<--contact-->
my contact information 

CSS file 
added scroll-behavior: smooth; which when press the navigation bars it directs to it 
on header added background image
on navigation bars added hover over , when hover over it changes color
can view any media screen 