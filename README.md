# Sascha Gogolin Portfolio

---

## Table Of Contents

- General Information
- Technologies
- UI
- UX
- Accessibility
- Challenges
- Features
- Testing
- Versioning
- Credits
- License

---

## General Information

User Centric Frontend Development Milestone Project
A personal portfolio with a minimalistic design, giving potential employers/contractors a brief introduction to who I am, my different skillsets, work history, examples of my past work/projects and a contact form.
The reason I decided to build a personal portfolio for this project is because I wanted to create something that I can continue to build upon while progressing through the training and something that will be of use to me even after course completion.

---

## Technologies

- HTML
- CSS
- Bootstrap v4.3.1
- FontAwesome 4.7.0

---

## UI

My goal with the minimalistic design was to keep the viewer’s focus on the core information and what I’m trying to communicate at all times whilst providing small visual elements and subtle effects to keep the viewer interested and make the website appealing to the eye.
Except the background, paperclip image and photography thumbnails, all colors on the website use a pallet of various grey tones.
The idea behind the paperclip image, background image and ‘Shadows Into Light’ font is to simulate a notebook style design to make the website less ‘strict’ and more relaxed.
On smaller screen sizes, the navbar is replaced by a nav-toggler (menu icon) and the background + paperclip images are hidden to increase the real estate available for the content, increase viewability/readability and reduce risk of any unintended overlap.

---

## UX

I aimed to keep the navigation between the different pages natural and intuitive. The viewer can navigate between the different pages using a standard top navigation bar on larger screens and a toggler/menu button on smaller screens. Links to social media pages have been placed discretely in the footer.

---

## Accessibility

To increase accessibility of the website, ALT attributes have been added to all images and ‘sr-only’ attributes have been added to the top navigation bar, social links in the footer and to the progress bars on the skill page to allow screen readers to capture and reproduce the data/information presented.

---

## Challenges

One of the main challenges in the beginning of the project was to design and adjust the size/position of the background images used in the larger screen size version in a way so it would stay clear of the content as much as possible.
For smaller screen sizes the challenge was to find a way to keep the ‘notebook’ feeling alive whilst providing the user with a clear orientation without using up too much ‘real estate’ something that was achieved by removing the background images entirely and replace the top navigation bar with a nav-toggler menu.

---

## Features

### Existing Features

The background image provides viewers using larger screens a navigation orientation as the text written by the hand/pen image reflects the current page that’s loaded (i.e. about, work history, etc.). Viewers on smaller screens will instead be presented with a orientation label at the top of the screen below the main logo to avoid text blurring together with the background image on smaller screens.
Subtle hovering effects (color transition and scale transform) on the navbar and social link items and photography thumbnails. and a soft transition effect to the toggler/menu window on smaller screens.

### Features Left To Implement

I’d like to add a portfolio page in the future where I can present all of my future projects. Since I for this project wanted every page to only reflect accurate information of me, my skills and work history, at this stage, I decided not to add a portfolio page with ‘fake’ projects.

---

## Testing

The site was created using a mobile-first approach and ongoing testing of the responsiveness thus became a crucial part of the testing process to ensure the site is presented as intended on all screen sizes. Testing was also performed across multiple browsers such as Chrome, Safari, Internet Explorer, Edge, Firefox to ensure responsiveness and compatibility.
The majority of responsiveness and functionality testing was performed during development using the developer tools in Google Chrome and towards the end of the project also live on a high-resolution screen (iMac) and iPhone 7 plus.
I cross-checked and tested all links on every single page to ensure that they work as intended on both a desktop and mobile client.
Furthermore, the code of each page and stylesheet has been checked for errors using a HTML and CSS validator tool.
During testing, I on purpose introduced broken image links to ensure the ALT attributes loaded and showed correctly.
All social links in the footer along with all photos in the photography section are meant to open in new tabs using ‘target=”_blank”’ something my testing of all applicable links confirmed to be working as intended.
All fields in the contact form have the ‘required’ attribute to ensure no field is left blank before submitting and it’s not possible to submit the contact form without entering a valid email address, something I tested as well.
During testing towards the end of the project, I deployed the site via GitHub pages, loaded it live on mobile devices such as iPhone plus 7 and encountered multiple errors that the Google Chrome developer tool had not revealed. For example, importing the Google fonts used on the site in the first line of the CSS stylesheet did not load the fonts correctly on mobile devices and therefore the font import had to be performed in the html-head instead.
Another feature that was working correctly in the ‘iPhone view’ of the developer tools but not on a real life device was the nav-toggler menu. In order to be able to address and fix this, I had to create a new test repository, working live with a deployed version back and forth via GitHub pages, loading the site on a live iPhone 7 plus.

---

## Deployment/Versioning

GitHub is used for version control. The site is hosted on GitHub pages and deployed/updated via the master branch upon every new commit.

---

# Credits

## Content

All content on the website except the below mentioned graphics and elements have been written, coded and designed by me.

## Media

The ‘hand/pen’ background image was taken from PurePNG here and the paperclip image from HiClipart here.

## Acknowledgements

The css nav-toggler menu code was found on this page and significantly modified to fit the styling and design of the page.

## License

This project is licensed under the MIT License - see the LICENSE.md file for details


