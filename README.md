# Zheng Yi Sao - Pirate Queen

This webiste is built to provide an introduction to the infamous pirate queen, Zheng Yi Sao. It is targeting amateur history enthusiasts and aims to provide a jumping off point to explore the life and exploits of one of the most successful pirates of all time.

![Zheng Yi Sao Responsive design](assets/readme-images/responsive-webpage.png)

# Contents

* [**User Experience**](<#user-experience>)
  * [Wireframes](<#wireframes>)
  * [Site Structure](<#site-structure>)
  * [Design Choices](<#design-choices>)
    * [Fonts](<#fonts>)
    * [Colour](<#colour>)


* [**Existing Features**](<#existing-features>)
  * [Navigation Bar](<#navigation-bar>)
  * [Home Page](<#home-page>)
  * [Timeline](<#timeline>)
  * [Form and Contact info](<#form-and-contact-info>)
  * [Videos](<#videos>)
  * [Find out more section](<#find-out-more-section>)
  * [Footer](<#footer>)

* [**Desired Features**](<#desired-features>)

# User Experience

## Wireframes

Wireframes for Zheng Yi Sao - Pirate Queen were created using [Balsamiq](https://balsamiq.com). The frames created were for a full width display with a screen wideht of 1440 pixels. Responsive elements were adding during the design process, and future development would include mobile wireframes to improve responsive design accross the site.

![Wireframe Home Image](assets/readme-images/wireframe-home.png)

![Wireframe Timeline Image](assets/readme-images/wireframe-timeline.png)

![Wireframe Info Image](assets/readme-images/wireframe-info.png)

[Back to top](<#contents>)

## Site Structure

The website consists of four pages. Three of the pages (Home, Timeline, and Find out more) are accessed through the navigation bar and the forth is a "Thank You" page after submitting the newsletter form. All pages contain the navigation bar for in-site movement between pages.

[Back to top](<#contents>)

## Design Choices

* ### Fonts
    The font selected for the webiste is Georgia to provide a academic look to the site. This will fall back to Times New Roman and Serif sequentially.

[Back to top](<#contents>)

* ### Colour
    The colour scheme used is #ffebcd as a base background colour, with rgba(0, 0, 128, 0.9) for secondary backgrounds and borders. This is to provide a warm screen for pleasent user experience while maintaining good contrast. Text uses rgba(0, 0, 128, 1) (navy keyword) to achieve full contrast. Containers and aside columns use ##ffe5b to stand out against the background colour.

[Back to top](<#contents>)

# Existing Features

## Navigation Bar

  - Featured across all pages of the site, the banner provides the title of the website and the navigation menu. 
  - The links in the navigation menu provide the user with easy movement between pages without needing to use browser navigation tools.
  - The links respond to user hovering over them and the current page is highlighted in the navigation bar to aid user interaction.
  - The navigation bar is responsive to screen size to allow ease of use on mobile and tablet screens.

  ![Navigation Bar](assets/readme-images/nav-bar.png)

[Back to top](<#contents>)

## Home Page
  - The home page provides initial information for users.
  - Information is divided into sematic elements with a main sections and two asides.
  - A brief biography is found in the central column.
  - The aside columns contain images to provide context to main biography.
  - Images are credited and linked to original source.

  ![Home Page](assets/readme-images/home-page.png)

[Back to top](<#contents>)

## Timeline
  - The timeline displays important events in Zheng Yi Sao's life.
  - Format is clean and simple to follow, with clearly marked dates and descriptions.
  - Side margins are empty to focus on timeline.

  ![Timeline](assets/readme-images/timeline.png)

[Back to top](<#contents>)

## Form and Contact info
  - The form encourages users to sign up to a newsletter.
  - The form leads to a thank you page with navigation back to the main website.
  - Currently the form collects no data.
  - The contact info section encourages users to contact for any questions and provides a (dummy) email address as point of contact.

  ![Contact Info](assets/readme-images/sign-up.png)

[Back to top](<#contents>)

## Videos
  - The videos are embedded into the page for users to watch.
  - Channels that own the video are highlighted on the page.

  ![Videos](assets/readme-images/videos.png)
  
[Back to top](<#contents>)

## Find out more section
  - The find out more section is divided into two parts, website links and book recommendations.
  - Links provided in the section lead to the corresponding site in a new window.

[Back to top](<#contents>)

## Footer
  - The footer provides links to (dummy) social media for users to interact with.

[Back to top](<#contents>)

# Desired Features

- An interactive timeline with images displayed when hovering over dates
- Fully functuional form with newsletter delivered to users.

[Back to top](<#contents>)

# Technologies Used

*[HTML5](https://html.com/html5/)
*[CSS](https://www.w3.org/Style/CSS/Overview.en.html)
*[Balsamiq](https://balsamiq.com/wireframes/)
*[Github](https://github.com)
*[Gitpod](https://www.gitpod.io)

[Back to top](<#contents>)

# Testing

## Code Validation
All code for Zheng Yi Sao - Pirate Queen has been run throught the [W3C HTML validation](https://validator.w3.org/) and the [W3C CSS Validator](https://jigsaw.w3.org/css-validator/). Initial errors were found, removed, and corrected. The validator reported no issues following that.

[Back to top](<#contents>)

* Home Page

![W3C Validator test result](assets/readme-images/html-validator.png)

* Timeline Page

![W3C Validator test result](assets/readme-images/html-validator.png)

* Find out more page

![W3C Validator test result](assets/readme-images/html-validator.png)

* Thank you page

![W3C Validator test result](assets/readme-images/html-validator.png)

The CSS validator results are below:

![CSS Validator test result](assets/readme-images/css-validator.png)

[Back to top](<#contents>)

## Responsive Design Check

* The responsive design test was carried out successfully on all pages using [Responsive Design Checker](https://responsivedesignchecker.com)

  * Display >1200px = Pass
  * Display <1200px = Pass
  * Ipad pro (1366x1024px) = Pass
  * Ipad air (768x1024px) = Pass
  * Nexus 7 (600x900px) = Pass
  * Iphone plus (414x736px) = Pass
  * Sony Xperia (360x640px) = Pass
  * Iphone (320x480px) = Pass

[Back to top](<#contents>)

## Browser Compatibility

Zheng Yi Sao - Pirate Queen was tested on the following browsers with no issues to the user.
Opera, Google Chrome, Mozilla Firefox, and Microsoft Edge. Apprearance and responsiveness were consistent accross the browsers and different screen sizes.

## Known Bugs
* ### Resolved

  * During Validation erros on the Find out more page due to erronious code in the embedded youtube links, these were removed. 
  * Typo with incorrect start and end tags for one of the headings, this was corrected.

* ### Unresolved

  * On repsonsive design for tablet size screens on the timeline and thank you page. The aside columns are not fully hidden above the footer. Time limitations restrain correction.

[Back to top](<#contents>)

## Lighthouse