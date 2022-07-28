# RISE Media
RISE media is a global digital media agency with offices in London, New York, Sydney & Toronto. 

Across the world, SMBs and enterprises are in the process of undergoing a digital transformation, primarily driven by Covid-19. With the ability to 'work from anywhere', businesses are looking for innovative strategies that help their brand grow by connecting with their customers on a human and emotional level.

The website is designed to attract higher seniority levels, those who have the ability to affect business decisions and buying, such as CTOs, Marketing Directors, Head of IT etc.

<br>

## Contents
<hr>

## Planning & Development
<hr>

<br>


### Site Objective
<hr>

<br>


### Target Audience
<hr>



<br>

### Prototype
<hr>

<br>

### Prototype
<hr>


<br>

### Colour Scheme
<hr>



<br>

### Typography
<hr>


<br>

## Features
<hr>

All of the contents and features is hosted on one page: homepage.

### Existing Features
<hr>

To evaluate the website, the structure can be split into six sections:

#### Navigation Bar
<hr>

- The navigation supports the brand logo (which upon being clicked returns the user to the homepage) and brand colour (3 colour gradient)
- Supporting the logo in the navigation bar, is links to About Us (aka, What We Do), Services (aka, Raise Your Game) and Free Consultation form
- Responsive across desktop, tablet, and mobile, however the following links are hidden in the nav bar once certain parameters are met regarding width:
    - 800px and less: About Us and Services links are hidden
    - 500px and less: Free Consultation link is hidden and the logo is centered
- The site incorporates a sticky navigation bar to make it easy for users to navigate on the website

For future development: a hamburger menu would be incorporated into the navigation bar once width hits 800px and less to show the hidden links.

<img src="assets/readme-images/nav-bar.jpg">

<br>

#### Hero Image section
<hr>

- The image in the background features a modern looking office to support the brand's forward thinking business model
- All elements have been made bigger than the rest of the homepage to draw the user's attention to the brand's opening heading and message. It's trying to push users to booking a free consultation
- As a consequence of the elements being made bigger for desktop screens, the respective elements reduce in size as media screens get smaller to ensure the hero image sections fits onto screen without scrolling

<img src="assets/readme-images/hero-image.jpg">

<br>

#### About Us (aka What We Do) section
<hr>

- RISE Media is a B2B company, therefore a short summary of who RISE Media is and what they do is essential to informing the user of the company's services and capabilties
- The user is presented with two buttons: 'WORK WITH US' which takes the user to the form section and; 'FIND OUT MORE' which takes the user to find RISE Media's services
- At 690px and less, the 'FIND OUT MORE' drops underneath the 'WORK WITH US' button to ensure there is adequate space between elements and edge of screen


<img src="assets/readme-images/about-us.jpg">

<br>

#### Quote section
<hr>

- Positioning the founder onto the homepage helps to promote a thought leadership position and evoke a human response - human to human interaction helps to forge bonds and emotions. It puts a name to a face and is designed to make the user feel welcome onto RISE Media's website
- At 1200px and less, the image of the founder is hidden to make space for the smaller screen
- At 900px and less, the background logo is hidden to focus the user attention on the text for the smaller screen 
- To highlight it's a quote, the quotation marks have been emphasised by making the font-size greater than the other elements in the section
- There is no heading in the section because it doesn't justify one
- All elements, excluding image of the founder and logo, remain at the same size to highlight that the quote section is a standalone feature on the homepage

<img src="assets/readme-images/quote.jpg">

<br>

#### Services (aka Raise Your Game) section
<hr>

- The top row with three columns seperates into two columns once 1450px width is met, and at 1000x width it collapses to one column. This ensures there is adequate spacing between all five mini-sections and edge of screen
- The five services are seperated by colour to help the user to quickly distinguish between the different services on offer from RISE Media. The elements affected are the icons, heading, horizontal line, and call-to-action button.
- Icons are used to support the titles and help the visitor to easily identify what services we RISE Media have to offer
- A brief description of each service and use of colour to differentiate between the services gives the user enough information to process without feeling overwhelmed

For future development: none of the buttons in this section direct the user elsewhere on the website. At the moment, the buttons are there for presentation purposes. However, once the appropriate services pages are added onto the website, the buttons will redirect the user to the respective service page they've requested to see.

<img src="assets/readme-images/services.jpg">
<img src="assets/readme-images/services-2.jpg">

<br>

#### Footer
<hr>

- The footer indicates the end of the page - this would be replicated on every page on the website.
- Social media icons (provided by Font Awesome) are included on the footer to encourage the visitor to engage with the brand. RISE Media social platforms will provide extra value and content and act as additional touchpoints with the visitor
- For accessibilily, each social link has an aria-label attribute
- When a user clicks on one of the social media icons, the browser redirects the visitor to a new tab. This prevents users from leaving the website
- The company's telephone number and email address is provided to give visitors the opportunity to reach out to RISE Media. The font-color is changed to burgundy to catch the user's eye and highlight they're call-to-action links
- The company details have the appropriate telephone and email links to make user experience friendly. Creating a sense of 'ease-of-use' on the website will evoke positive emotions and help encourage visitors to communicate with the brand

For future development: the footer is to include links to high-priorty pages and office locations.

<img src="assets/readme-images/footer.jpg">



<br>


## Testing
<hr>
Throughout the design of the website, but more so after the structure and contents of the page was added, Google Dev-tools was used extensively to validate new ideas, fix errors, unearth solutions, and ensure consistency with the design and user experience across various devices by ensuring the website was responsive.

### Validator Testing
<hr>

The three websites used to validate the code are:

- https://validator.w3.org/
- https://jigsaw.w3.org/css-validator/


For accessibility, the following websites and extensions were used:

- https://wave.webaim.org/
- WCAG Contrast Checker
- LighthouseS


#### HTML Validator
<hr>
Errors discovered:<br>
<img src="assets/readme-images/html-markup-check.jpg">
<img src="assets/readme-images/html-markup-check-2.jpg">
<img src="assets/readme-images/html-markup-check-3.jpg">

<br>

Errors fixed:<br>
<img src="assets/readme-images/html-markup-check-after.jpg">

<br>

- Whilst the remaining issues were able to be fixed, the warning still remains. In this instance, the quote section does not need no heading elements due to no hierarchy of importance. It is a standalone section which conveys only one message: the Founder's thoughts.

<br>

#### CSS Validator
Website used to validate CSS code: https://jigsaw.w3.org/css-validator/
<hr>
Errors discovered:<br>
<img src="assets/readme-images/css-markup-check.jpg">
<img src="assets/readme-images/css-markup-check-2.jpg">

Errors fixed:<br>
<img src="assets/readme-images/css-markup-check-after.jpg"><br>

- The latest version of the CSS stylesheet reported no errors

<br>

#### WAVE (Web Accesssibility Evaluation Tool)
<hr>
Errors discovered: <br>
<img src="assets/readme-images/wave.jpg">
<img src="assets/readme-images/wave-details.jpg">

Errors fixed: <br>

#### WCAG Contrast Checker
<hr>

<img src="assets/readme-images/contrast-checker.jpg"><br>
It's reported that there are four contrasting errors:

- Two of the errors are located in the services section regarding Social Media Marketing. However, the image provided below show there is no visibility issue  and reading difficulty as there is a contrast between foreground and background colour

<img src="assets/readme-images/contrast-checker-smm.jpg"><br>

- The other two are located in the form section. The h2 and p element have a white foreground colour against a gradient background. The example below shows there are no issues with visibility 

<img src="assets/readme-images/contrast-checker-form-text.jpg"><br>

<br>

#### Lighthouse
<hr>
Lighthouse has reported extemely positive metrics (see graphic below) with scores ranging from 90 to 100. The results are:

- Performance: 100
- Accessibility: 97
- Best practises: 100
- SEO: 90

<img src="assets/readme-images/lighthouse-scores.jpg"><br>

## Deployments
<hr>
The site was deployed to GitHub pages. The steps to deploy are as follows:

- In the GitHub repository, navigate to the Settings tab
- From the source section drop-down menu, select the Main Branch
- Once the master branch has been selected, the page will be automatically refreshed with the word 'active' displayed in a green colour at the end of the sentence (next to last duration when published)
The live link can be found here - https://lewis-worsley.github.io/digital-media-agency/

## Languages
<hr>
The coding languages used:

- HTML
- CSS

<br>

## Software
<hr>
The design for RISE Media was created via the Adobe Creative Cloud Suite; more specifically I used:

- Abobe Photoshop
- Adobe InDesign
- Adobe Illustrator

Through using these three tools, I was able to design the logo, create imagery, design the website, and compress web images by either reducing image size or quality via export.

<br>

## Media
<hr>
The logo and icons for RISE Media was designed by myself, Lewis Worsley.

<br>

## Credits
<hr>
To help bring this project to life, the following deserve recognition:

<br>

### Content
<hr>

- The 3-colour-gradient for the brand was provided by https://mycolor.space/

- The CSS structure for the hero section was inspired by the Code Institute's Coders Coffeehouse

- The CSS code to achieve a gradient background was provided by https://www.w3schools.com/

- To specify a minimum font-size for responsive design - especially for mobile - a user from Stack Overflow in a public open forum https://stackoverflow.com/questions/23984629/how-to-set-min-font-size-in-css provided CSS code to help achieve this

- Change the color of the placeholder text of an input field was provided by https://www.w3schools.com/

- Font pairing (Proza Libre and Open Sans) for RISE Media was inspired by https://www.fontpair.co/

- Social media text icons located in the footer were sourced from https://fontawesome.com/

<br>

### Thanks
<hr>

- Richard Wells
    - His mentorship and time have been of utmost value to me progressing this project along. I showed my concept of RISE Media to Richard on our first call and he gave me the encouragement and belief that I could execute the design. His easy-going and laid-back persona reminds me of myself, which is why I feel our meetings have been valuable and fun. 