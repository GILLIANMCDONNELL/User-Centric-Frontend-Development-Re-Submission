# The Monkees

The Monkees Website aims to be simple, modern with easy to use navigation for fans of all ages. Clear and Simple links to Social Media and Third Party Sales agents ensures Fans have easy accesibility to check out upcoming events and purchase tickets. 
Displaying some information about the band a simple gallery and link to both Spotify and YouTube shows the bands versatility to keep up with the times, allowing fans and potential fans to enjoy music through the decades.
The contact section of the site allows fans and potential fans to communicate with the band through multiple channels by direct email, newsletter sign up or link to social media. 
 

## UX

My goal in the design was to provide a place where fans and potential fans could book an event and have a sample taste of music and video's with links to The Monkees social media aswell as showcasing images of the band. 

# User Stories
- As a site owner I want to be able to showcase my band and offer promotions to fans to increase brand awareness.
- As a site owner I want to link off to social media sites to effectively speak to audiences on different social media sites targeting a wider audience.
- As a site user I want to instantly see what new events are taking place 
- As a site user I want to be able to book for an event easily from a trusted source.
- As a site user I want to watch and hear tracks from The Monkees so I can see what they have available.

[Wireframe Link](https://github.com/GILLIANMCD/User-Centric-Frontend-Development-Milestone-Project/blob/master/assets/wireframe.pdf)
i.e. I have not re-designed the original wireframe as I was conscious of improving on the site and not completing a full re-design. Changes to original wireframe are in the music - contact us and social share elements which now flow in a more consistanct manner. 


## Features

-This site uses the scrollSpy feature in Bootstrap. The navbar is responsive to create a less crowded view on mobile eliminating any crowded space on mobile.

### Existing Features
- Contact Form - allows users to send a message or request for available dates. 
- Newsletter Sign Up - Allow users to sign up to newsletter to keep up with events.
- Spotify - allows users to listen to the bands music and find further music on spotify.
- You-Tube - allows users to watch video of The Monkees which does not automatically start on page load giving the option for the user to play video when they want.

## Technologies Used
- HTML
- CSS
- Bootstrap
- [JQuery](https://jquery.com)
 - The project uses **JQuery** to simplify DOM manipulation.

## Testing
The site has been tested using Chrome Developer tools checking responsiveness on various mobile, tablet and desktop. 

- Tested site as in steps below for aite and contact form Seperately

1. Open .html file in chrome browser.
2. Right click and choose inspect.
3. hover over area to inspect styles and cick inspect again, alternatively click on page area in Elements to also show styles of the page area.
4. Configure styles css to desired format. 
5. Update source css file and save for changed to be implemented.

- Contact form:
 1. Go to the "Contact Us" page
 2. Try to submit the empty form and verify that an error message about the required fields appears 
    - Works Correct
 3. Try to submit the form with an invalid email address and verify that a relevant error message appears 
    - Works Correct
 4. Try to submit the form with all inputs valid and verify that a success message appears. 
    - This Feature is not added in this Project

 - Spotify Player - test play and link to spotify site.
 - YouTube Video - 

Review of site testing for sections

The overall feel and look of the site is themed well with good structure and easy to follow navigation.

- Navbar - navbar transforms to burger menu on mobile 
 - however covers some content. 

- Home - Image looks well on desktop - does not shrink down well on tablet or mobile *Tablet and Mobile to be addressed.
   - This issue is addressed and resolved. 
- About/ Gallery- about and Gallery on mobile and tablet and desktop with columns adjusting accordingly.
   - 
- Video - Appears to big for user * Video size to be adjusted and listen to spotify to be placed in 2 cols in order to keep media together and provide a better user experience. 
   - This issue is addressed and resolved
- footer - Music plays, contact button works and social medial links work. However the colums appear to overlap 
   - This issue is addressed and resolved

## Deployment

This site is hosted using GitHub pages, deployed directly from the master branch. The deployed site will update automatically upon new commits to the master branch. In order for the site to deploy correctly on GitHub pages, the landing page must be named index.html.

To run locally, you can clone this repository directly into the editor of your choice by pasting git clone https://github.com/GILLIANMCDONNELL/User-Centric-Frontend-Development-Re-Submission into your terminal. To cut ties with this GitHub repository, type git remote rm origin into the terminal.

- [GitHub Pages](https://gillianmcdonnell.github.io/User-Centric-Frontend-Development-Re-Submission/)

## Credits

### Content
- The text for section About was copied from
--[METV](https://www.metv.com/lists/10-things-you-might-not-know-about-the-monkees)
-- [Wikipedia - Davy Jones](https://www.metv.com/lists/10-things-you-might-not-know-about-the-monkees) 
--[Wikipedia - Mickey Dolenz](https://en.wikipedia.org/wiki/Micky_Dolenz)
--[Wikipedia - Michael Nesmith](https://en.wikipedia.org/wiki/Michael_Nesmith)
--[Wikipedia - Peter Tork](https://en.wikipedia.org/wiki/Peter_Tork)
--[The Monkees UpComing Events](https://www.facebook.com/pg/TheMonkees/events/)

### Media
- The photos used in this site are directly linked to source file throughout the site. 
- Gallery Photos [Getty Images](https://www.gettyimages.ie/)

### Acknowledgements

- I received inspiration for this project from
- [YouTube Drew Ryan](https://www.youtube.com/watch?v=Ht1F9KuhJO4&t=185s)
- [W3Schools](https://www.w3schools.com)

### Notes

Improvements Made 
- Landing Page Image Changes for more stricking effect and Caption changed for clearer message of site user goal to promote upcoming events.
- About Section - Paragraph added and Cards Updated to create a more streamlined uniform look. 
- Gallery Section changed with all images displaying the same size in a simple format. 
- Music Section - Spotify and YouTube Section updated and fixed responsiveness.
- Social Icons styled to the color scheme of the website and made larger to be more prominant. 
- All Buttons styled the same for User Ease. 


