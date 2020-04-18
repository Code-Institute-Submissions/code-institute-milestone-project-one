# User Centric Front End Development - Milestone Project One.

## HTML & CSS3 based static website for Daryl Johnson, Music Producer and Mix Engineer. 

## https://mattingliscoding.github.io/code-institute-milestone-project-one/


## Overview 

This site is aimed at making it incredibly simple for professional in the Music Industry to hire Daryl Johnson as their next mix or recording engineer. With efficient, stately UI choices preventing what would be a very crowded site otherwise, the user arrives on the lading page and instantly can fulfil their purpose for being there. The site, supplemented with Bootstrap, is completely responsive and behaves exactly as it should from large 1440x1044 displays to smaller mobile screens at 320x679.

When choosing a style to pursue for this project, it felt natural to choose a subject that came pre-loaded with assets and content, rather than trying to procure my own. I chose to create a website for Daryl Johnson because, I wanted to try a different approach than my initial/simplest idea for the submission (which was a portfolio for my own web design career). I tried to approach the project as if it was a real-world freelance situation, to develop good habits in Web Development for a future career.

## UI/UX

Here is a link to the wireframe I created using Balsamiq for this site: https://pdfhost.io/edit?doc=44ea32a5-c665-47c4-96f7-3f84b68aa26d (also uploaded to docs directory in repository)

Having done market research on other freelance engineer sites, I found many of them cluttered, and too crammed with text and features, which is exactly what I wanted to avoid. The landing page on my site is designed in a way to present exactly what the user would need to see; an image of the product (Daryl in this case), a CTA in a jumbotron to entice the user, and two buttons taking them to the most pertinent page of the site, maximising efficiency as much as possible. 

I had already decided that I wanted to create a multi-page site, as I wanted to test myself for the first time in organising my directory files in GitPod. It was a welcome challenge from the simple sites I had made before to work with much larger amounts of code, and I endeavoured to use commenting in my HTML and CSS to split up areas and make it easier to read. I utilised Bootstrap for sections of this site as I find the class system incredibly intuitive, but I was cautious of leaning too heavily on their styling and used my own design ideas as much as possible to created a personal style. When speaking with Daryl (the 'client' in this case), he told me that a dark, bespoke UI was what he wanted, and I reflected this in the stately green primary colours, and header font (Roboto Slab). A site of this type, naturally has a lot of important information that needs to be conveyed, so to break up the text and stop cognitive overload, I used Bootstrap cards to separate blocks of text becoming too tiring to read. 

### Some user stories that would highlight this sites ease of use are: 

* As a user when I arrive at the landing page would like to be able to easily navigate to a contact page.
* As a user, I want to be able to find the social media presence of the product/site subject.
* As a user, as this is a music industry based-product, I would like the ability to hear the quality of mix on offer without leaving the site.
* As a user I would like to see a list of previous clients, to see the calibre the freelancer has worked with previously.
* As a user I want to see a digestible workflow that the freelancer takes, to see if it corresponds to how I would like the work to be done.

## Features
* Navigation bar with page links (ALL PAGES) - Allows users to reach all available pages on the site, collapses to a "hamburger" menu on smaller screens so the UI is not cluttered.
* Footer (ALL PAGES) - The "quick links" page menu, social icon links and copyright text box, fixed to the bottom of the screen, allows users to easily navigate without going back up to the navigation bar. Recognisable social icons easily display without labels, which site they direct to. 

* Landing Page CTA/Buttons - Immediately tells the user what the site is about and allows them to navigate directly to the corresponding pages.
* About.html Features and Testimonials cards - These were used to break up what would other wise be a very fatiguing, text-heavy site, preventing cognitive overload.
* Hover.css - A third party hover "grow" animation applied to Nav items and cards. This gives the site a tactile, responsive feel and keeps the user interested. 
* Credits page table element - Used for the ability to scroll through the data (mix engineer credits) without taking up too much screen real estate and making the page tiring to look at. 
* Credits page video container - Embeded youtube videos, allowing users to hear examples of Daryl's work without leaving the site.
* Contact page form - Would allow the user to send a project request via email. The required class stops blank text areas being submitted.

## Technologies Used

In this project I used several technologies to achieve my end result:
* Languages - HTML5 & CSS3
* Frameworks - Bootstrap 4

* Libraries - Unsplash.com for one avatar and two background images, FontAwesome for icons, Hover.css for hover effects, Google Fonts for typography and the jQuery API to facilitate the navigation bar collapsible menu.
* https://unsplash.com/
* https://fontawesome.com/
* https://ianlunn.github.io/Hover/
* https://fonts.google.com/
* https://jquery.com/

## Testing 

* In order to ensure that moving around the site is at full capacity, I checked every link on the Navigation bar and Footer on each page to guarantee they direct to the correct page. The same test was carried out on the Landing page buttons. 

* The embedded media player plays with no issues at every responsive screen size from Mobile (small) to 4K (large) in Google Chrome DevTools. 

* Although the Contact page form is static and front-end only as per the project brief, the form still functions correctly in that it does not allow blank areas to be submitted and the browser auto-fill recognises the type of form area that is clicked on (a list of saved emails come up in the email text-area).

## Responsive Design Testing

Even with the nature of Bootstrap naturally catering to responsive web development, I still heavily customised the Bootstrap elements that I used and as such diligently tested the site at as many screen sizes as possible. For this is first tried it on my own varying screens but predominantly I used Chrome DevTools Device Toolbar to visualise the site at every size, everything from 4K displays & iPad Pro to the smallest mobile view available and adjusted element margins and padding accordingly. This was in order to keep the UI clean and avoid clutter at smaller sizes. For example, the navigation bar menu collapses into a recognisable icon dropdown, and the footer closes down to just the social media links to prevent it having too much height on the screen. In addition, the horizontally arranged cards on the About and Services pages transition to displaying vertically. 

## Deployment

To deploy the project for public viewing, I used the feature in GitHub known as GitHub Pages. This was the logical choice as the site was coded in GitPod online IDE. The link to the deployed version, can be found at the beginning of this README. 

To achieve the deployment, GitHub makes it as easy as entering the settings of the repository and navigating to the GitHub Pages area and selecting which branch to deploy. In the case of this project it was simply the master branch, and soon after I had a deployed, shareable URL for my project. 

## Credits

### Content 

All text content for the site was provided by the site subject Daryl Johnson, including the testimonials from clients.

###Media 
3 photos for this site were obtained from Unsplash.com, and these are the credits due to the photographers: 
* Mike Larson testimonial avatar - Photo by Jacek Sniecikowski on Unsplash
* Black and White mix desk fader image - Photo by Leo Wieling on Unsplash
* Colour API desk close up image - Photo by Yassine Khalfalli on Unsplash

### Inspiration
Several ideas for the site were inspired by different creators online: 
* mdbootstrap.com - Used for inspiration on colour schemes and code ideas for the card elements across the site. In addition for the Bootstrap embedded video containers on the Credits page of the site. 
* css-tricks.com - Used for inspiration on the opaque overlays on background images and box shadows on the card elements. 

