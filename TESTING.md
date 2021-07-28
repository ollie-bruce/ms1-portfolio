# Portfolio Site - Testing

## User Stories

### As Oliver:

* I am able to provide employers examples of my best work that is easy to navigate via both the Videography and Development pages.
* I am able to provide employers pertinent information about myself and my skills via the About page.
* I am able to provide ready access to my CV and contact information via an obvious download link the website's header and an easily-navigable Contact page.
* I now have a clean, easy-to-navigate portfolio website that is indicative of my skills at this point in my career.
* I have an easy-to-access archive of my work that I can easily refer to and edit using the documentation provided both via README.md and comments left in the code itself.

### As a future employer:

* I have easy access to the relevant parts of Oliver's portfolio with clear distinctions between Development and Videography.
* I can easily assess Oliver's skillset in a few moments by using the table on the About page
* I can download Oliver's CV separately for file-keeping and contact Oliver via the contact form or the information provided in his CV.
* I am able to determine some of Oliver's skillset from the website itself and navigating it as a user.

## Manual Testing

### Common Elements

These elements appear on every page identically and as such were tested once. 

* The navbar `hover` effect to confirm which links the user is about to click.

![A gif showing the navbar elements being tested for their hover function](assets/testing/hover-testing.gif)

* Clicking on "Download my CV" will download the correct file without errors.

![A gif showing the CV download element being tested for function](assets/testing/download-testing.gif)

### Page Testing

#### Landing Page

Clicking the logo refreshes the landing page

![Landing page refresh](assets/testing/testing-gifs/landing-page-refresh.gif)

Page responsiveness

![Landing page responsiveness](assets/testing/testing-gifs/landing-page-responsive.gif)

#### About

Clicking the logo takes you back to the landing page

![Clicking the logo on the About page](assets/testing/testing-gifs/about-logo-click.gif)

Page responsiveness

![About page responsiveness](assets/testing/testing-gifs/about-responsive.gif)

Skills table responsiveness

![Skills table responsiveness](assets/testing/testing-gifs/about-table-responsive.gif)

#### Videography

Clicking the logo takes you back to the landing page

![Clicking the logo on the Videography page](assets/testing/testing-gifs/videography-logo.gif)

Clicking on the video embeds starts the video player

![Video embed test](assets/testing/testing-gifs/videography-embed-test.gif)

Page responsiveness

![Videography responsiveness](assets/testing/testing-gifs/videography-responsive.gif)

#### Development

Clicking on the logo takes you back to the landing page

![Clicking the logo on the Development page](assets/testing/testing-gifs/development-logo.gif)

Page responsiveness

![Development page responsiveness](assets/testing/testing-gifs/development-responsive.gif)

#### Contact

Clicking on the logo takes you back to the landing page

![Clicking the logo on the Contact page](assets/testing/testing-gifs/contact-logo.gif)

Text entry for each of the fields on the Contact form

![Text entry for the contact form](assets/testing/testing-gifs/contact-text-entry.gif)

Page responsiveness

![Contact page responsiveness](assets/testing/testing-gifs/contact-responsive.gif)

## Automated Testing

### W3Schools Validator

#### Landing page

![W3School HTML Validation screenshots for the landing page](assets/testing/landing.png)

#### About

![W3School HTML Validation screenshots for About](assets/testing/about.png)

#### Videography

![W3School HTML Validation screenshots for Videography](assets/testing/videography.png)

#### Development

![W3School HTML Validation screenshots for Development](assets/testing/development.png)

#### Contact

![W3School HTML Validation screenshots for Contact](assets/testing/contact.png)

#### CSS

![W3School CSS Validation](assets/testing/css.png)

### Lighthouse Audit

The full Lighthouse Audit can be found [here.](assets/testing/lighthouse-audit-ms1.pdf)

## User testing

The website and documentation were given to friends and family to provide feedback on any bugs present or usability issues. From this feedback, two main features were implemented:

* Adjusting the font sizes of main page titles for smaller screen sizes to increase readability (i.e. multi-word titles remaining on the same line)
* Stacking video embeds and their blurbs vertically on smaller screen sizes to help with readability and maintain a succinct layout.
