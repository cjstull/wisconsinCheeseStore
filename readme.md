README file for Front End Development Final Project

This site is a prototype for a Wisconsin Cheese Lover's Shop. The site has a list of different cheese, and their cost per pound.
I've tried to add some humor by including things like CheezWiz to the shop. I've designed the website mobile first, and have add a navigation menu, a gallery of cheeses with descriptions about the cheese as well as the price. 

The Project is built mobile first:

There are base styles in the CSS code that apply to all screens (starting with mobile first). 

The Media Queries then adjust the layout of the navigation and footer menu at 700 and 992px on the index page.
The header displays as block as the default, then display flex and flex-direction: column once the viewport hits 700px, and then flex-direction: row and justify content: space-between at 992px and larger.

I've also added a media query to the contact.html page that switches the form layout as the user expands the window.

Project is uploaded to Github Repo and has at least 5 commits

The CSS Feature(s) that this project uses are as follows:
1) A navigation menu that expands and collapses properly at desktop and mobile sizes. 
    i) The nav menu on mobile uses flex-direction: Column
    ii) The nav menu at the higher media queries - specifically 992px use Flex-direction: Row  

2) Flexbox was used on cheese inventory. Default Mobile site is in column form, as the window is expanded it switches to flexbox:row

The JavaScript Feature(s) that his project uses are as follows:
On the Which Cheese Are You? page the following features were used:
    1)Math.Random() to help calculate a random number between 0 and 9
    2) An array to reflect the probability of the items, and code which calls the position of the array
    3) onclick button event that uses document.querySelector to pass the result of the getRandomCheese() function into the HTML

Other features include:
    1) The footer links have code to open the links in new pages
    2)