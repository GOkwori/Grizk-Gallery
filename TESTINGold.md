# Grizk Art Gallery -  Testing

![Grizk Art Gallery shown on a variety of screen sizes](documentation/features/home-page.PNG)

Visit the deployed site: [Grizk Art Gallery](https://gokwori.github.io/Grizk-Gallery/)

- - -

## CONTENTS

* [AUTOMATED TESTING](#automated-testing)
  * [W3C Validator](#w3c-validator)
  * [Lighthouse](#lighthouse)
* [MANUAL TESTING](#manual-testing)
  * [Testing User Stories](#testing-user-stories)
  * [Full Testing](#full-testing)

Testing occurred continuously throughout the entire development process. I employed Chrome Developer Tools extensively during the build to identify and resolve issues promptly.

Throughout the development phase, I incorporated Google Developer Tools to verify the proper functioning of elements and to aid in diagnosing problems when they arose.

The console within the developer tools was instrumental in dissecting and validating small sections of JavaScript code. It served not only to confirm the functionality of the code but also to troubleshoot any encountered issues.

To guarantee responsiveness across diverse screen sizes and devices, I meticulously reviewed each page using both Google Chrome Developer Tools and the Microsoft Edge Inspector tool.

- - -

## AUTOMATED TESTING

### W3C Validator

[W3C](https://validator.w3.org/) was used to validate the HTML on all pages of the website. It was also used to validate the CSS.

* Home Page - Passed
  ![index.html](testing/w3/index-w3.png)

* Gallery Page - No errors, 1 Warning. The warning is that gallery section lacks heading
  ![gallery.html](testing/w3/gallery-w3.png) 

* Exhibition Page - Passed
  ![exhibition.html](testing/w3/exhibition-w3.png) 

* Booking Page - Passed
  ![booking.html](testing/w3/booking-w3.png) 

* Thank-you Page - Passed
  ![thank-you.html](testing/w3/thank-you-w3.png) 

* Coming-soon Page - Passed
  ![coming-soon.html](testing/w3/coming-soon-w3.png) 

* CSS - Passed, no errors found
![style.css](testing/w3/css-validator.png)

- - -

### Lighthouse

I employed Lighthouse within the Chrome Developer Tools to assess the website's performance, accessibility, adherence to best practices, and SEO.

### Desktop Results

All pages of the site are achieving a score of above 90 across the 4 categories.

* Home Page
  ![index.html](testing/lighthouse/desktop-home-page.png)

* Gallery Page
  ![gallery.html](testing/lighthouse/desktop-gallery-page.png)

* Exhibition Page
  ![exhibition.html](testing/lighthouse/desktop-exhibition-page.png)

* Booking Page
  ![booking.html](testing/lighthouse/desktop-booking-page.png)

* Thank-you Page
  ![thank-you.html](testing/lighthouse/desktop-thank-you-page.png)

* Coming-soon Page
  ![coming-soon.html](testing/lighthouse/desktop-coming-soon-page.png)

- - -

## MANUAL TESTING

### Testing User Stories

`Art Lovers`

| Goals | How are they achieved? |
| :--- | :--- |
| I want to easily access information about the gallery's objectives and mission. | To ensure easy access to comprehensive information about the gallery's objectives and mission, a dedicated "About Us" section is implemented on the website. This section serves as a central hub where art lovers can navigate to gain insights into the gallery's overarching goals and mission. | 
I want a user-friendly platform to discover and preview the latest artwork releases. | Creating a user-friendly platform for art enthusiasts to discover and preview the latest artwork releases involves the implementation of features designed to showcase these artworks prominently. The website incorporates a dedicated "New Releases" section, providing a curated space where visitors can explore and engage with the gallery's most recent additions. |
| I want to stay informed about upcoming exhibitions and events hosted by the gallery. | To ensure art lovers stay informed about upcoming exhibitions and events, the website incorporates a dedicated section that serves as a comprehensive source of information. This section may include a dynamic calendar highlighting key dates, detailed announcements about upcoming exhibitions, and a feature for newsletter subscription (which would be included in future implementations). |
| I want the ability to explore the full art catalog and conveniently purchase paintings. | The website provides a robust and user-friendly online catalog, allowing art enthusiasts to explore the complete collection. The catalog is organized in a structured manner, featuring categories, genres, and artists. |


`Artists`

|  Goals | How are they achieved? |
| :--- | :--- |
| I want a simplified and expedited process for booking exhibitions at the gallery. | The website streamlines the exhibition booking process for artists, ensuring a simplified and expedited experience. The user interface is designed with a focus on efficiency and clarity. Artists can navigate to the dedicated "Booking" section, where a user-friendly form allows them to submit essential details for exhibition consideration. |
| I want clear information about the gallery's availability for exhibitions and submission guidelines. | Comprehensive information about the gallery's availability for exhibitions and detailed submission guidelines are easily accessible on the website. A dedicated page outlines the submission process, exhibition criteria, and any specific requirements for artists. |


`General Users`

| Goals | How are they achieved? |
| :--- | :--- |
| I want a visually appealing and intuitive interface that is easy to navigate. | The website boasts a visually appealing and intuitive interface designed to enhance user experience. A clean and modern design aesthetic is implemented, ensuring that the layout is visually engaging and easy to navigate. |
| I want the website to load quickly and efficiently to access information without delays. | To meet the user's expectation of quick and efficient loading, the website is optimized for performance. Images and multimedia content are compressed without compromising quality, and the underlying code is streamlined to reduce unnecessary delays. |
| I want the website to be responsive and provide a seamless experience on various devices. | The website prioritizes a responsive design, guaranteeing a seamless experience across various devices. Whether accessed from a desktop, laptop, tablet, or smartphone, the website adapts to different screen sizes and resolutions. The responsive design is achieved through the use of flexible layouts and media queries, allowing content to adjust dynamically. |

- - -

### Full Testing

Full testing was performed on the following devices:

* Laptop:
  * Macbook Pro 2017 13"
  * Hp Spectre x360
  * HP EliteBook 830 G10 13.3"
  * Dell Latitude 5530 15"

* Mobile Devices:
  * iPhone 13 pro max.
  * iPhone 12 pro.
  * Samsung S10+

Each device tested the site using the following browsers:

* Google Chrome
* Safari
* Microsoft Edge


`Home Page`

| Feature | Expected Outcome | Testing Performed | Result | Pass/Fail |
| --- | --- | --- | --- | --- |
| The Site's title | Link directs the user back to the home page | Clicked title | Home page reloads | Pass |
| Navigation menu | Switches to the selected menu tab with the selected tab highlighted | Clicked on menu tabs | Switches between different pages with the current page tab being highlighted | Pass |
| Autoplaying Carousel | Automatically starts slideshow or manually move between slides| Refreshed page & clicked on Prev and Next buttons | Carousel played automatically upon refresh and able to navigate between slides using buttons | Pass |
| Thumbnail Images - hover effect | All thumbnail images should zoom in when hovered on | Hover over each thumbnail on the page | Each image displayed the right transition when hovered on | Pass |
| Thumbnail Images | Link directs the user back to an enlarged image in a new tab | Click each thumbnail on the page | Each image displayed an enlarged portrait in a new tab | Pass |
| Exhibition list items - hover effect | All list items images should zoom in when hovered on | Hover over each item in the upcoming exhibition section on the page | Each item displayed the right transition when hovered on | Pass |
| Exhibition item Buttons | Directs the user to the coming-soon page | Clicked on all buttons | Directs to the coming-soon page | Pass |
| All headings - hover effect | All headings should zoom in when hovered on  | Hover over every heading on the page | Each heading displayed the right transition when hovered on | Pass |
| All buttons - hover effect | All transparent buttons with white text should change to white with purple text when hovered over. | Hover over each button on the page | Each button displayed the correct styling when hovered over | Pass |
| Location thumbnail | Directs the user to the coming-soon page | Clicked on each location thumbnail | Directs to the coming-soon page | Pass |
| Location thumbnail - hover effect| All location thumbnails should zoom in when hovered on  | Hover over each location thumbnail | Each item displayed the right transition when hovered on | Pass |
| Social-media links| Link directs the user to the art gallery's social media page in a new tab | Clicked on each link | Redirected to the gallery's social media page | Pass |
| Social-media links - hover effect| All social-media icons with white background and purple font should change to purple and white | Hover over each icon | Each icon displayed the correct styling when hovered over  | Pass |

`Gallery Page`

| Feature | Expected Outcome | Testing Performed | Result | Pass/Fail |
| --- | --- | --- | --- | --- |
| The Site's title | Link directs the user back to the home page | Clicked title | Home page reloads | Pass |
| Navigation menu | Switches to the selected menu tab with the selected tab highlighted | Clicked on menu tabs | Switches between different pages with the current page tab being highlighted | Pass |
| All headings - hover effect | All headings should zoom in when hovered on  | Hover over every heading on the page | Each heading displayed the right transition when hovered on | Pass |
| Thumbnail Images - hover effect | All thumbnail images should zoom in when hovered on | Hover over each thumbnail on the page | Each image displayed the right transition when hovered on | Pass |
| Thumbnail Images | Link directs the user back to an enlarged image in a new tab | Click each thumbnail on the page | Each image displayed an enlarged portrait in a new tab | Pass |
| Social-media links| Link directs the user to the art gallery's social media page in a new tab | Clicked on each link | Redirected to the gallery's social media page | Pass |
| Social-media links - hover effect| All social-media icons with white background and purple font should change to purple and white | Hover over each icon | Each icon displayed the correct styling when hovered over  | Pass |


`Exhibition Page`

| Feature | Expected Outcome | Testing Performed | Result | Pass/Fail |
| --- | --- | --- | --- | --- |
| The Site's title | Link directs the user back to the home page | Clicked title | Home page reloads | Pass |
| Navigation menu | Switches to the selected menu tab with the selected tab highlighted | Clicked on menu tabs | Switches between different pages with the current page tab being highlighted | Pass |
| All headings - hover effect | All headings should zoom in when hovered on  | Hover over every heading on the page | Each heading displayed the right transition when hovered on | Pass |
| Thumbnail Images - hover effect | All thumbnail images should zoom in when hovered on | Hover over each thumbnail on the page | Each image displayed the right transition when hovered on | Pass |
| Thumbnail Images | Link directs the user back to an enlarged image in a new tab | Click each thumbnail on the page | Each image displayed an enlarged portrait in a new tab | Pass |
| Exhibition list items - hover effect | All list items images should zoom in when hovered on | Hover over each item in the upcoming exhibition section on the page | Each item displayed the right transition when hovered on | Pass |
| Exhibition item Buttons | Directs the user to the coming-soon page | Clicked on all buttons | Directs to the coming-soon page | Pass |
| All buttons - hover effect | All transparent buttons with white text should change to white with purple text when hovered over. | Hover over each button on the page | Each button displayed the correct styling when hovered over | Pass |
| Social-media links| Link directs the user to the art gallery's social media page in a new tab | Clicked on each link | Redirected to the gallery's social media page | Pass |
| Social-media links - hover effect| All social-media icons with white background and purple font should change to purple and white | Hover over each icon | Each icon displayed the correct styling when hovered over  | Pass |

`Booking Page`

| Feature | Expected Outcome | Testing Performed | Result | Pass/Fail |
| --- | --- | --- | --- | --- |
| The Site's title | Link directs the user back to the home page | Clicked title | Home page reloads | Pass |
| Navigation menu | Switches to the selected menu tab with the selected tab highlighted | Clicked on menu tabs | Switches between different pages with the current page tab being highlighted | Pass |
| Heading - hover effect | Heading should zoom in when hovered on  | Hover over the heading on the page | Heading displayed the right transition when hovered on | Pass |
| Submit button | Directs the user to the Thank-you page | Clicked on the submit button | Directs to the Thank-you page | Pass |
| Submit button - hover effect | Transparent button with white text should change to white with purple text when hovered over.| Hover over each button on the page | Each button displayed the correct styling when hovered over | Pass |
| Social-media links| Link directs the user to the art gallery's social media page in a new tab | Clicked on each link | Redirected to the gallery's social media page | Pass |
| Social-media links - hover effect| All social-media icons with white background and purple font should change to purple and white | Hover over each icon | Each icon displayed the correct styling when hovered over  | Pass |

`Thank-you Page`

| Feature | Expected Outcome | Testing Performed | Result | Pass/Fail |
| --- | --- | --- | --- | --- |
| Heading - hover effect | Heading should zoom in when hovered on  | Hover over the heading on the page | Heading displayed the right transition when hovered on | Pass |
| Close button | Directs the user to the Home page | Clicked on the submit button | Directs to the Home page | Pass |
| Close button - hover effect | Transparent button with white text should change to white with purple text when hovered over.| Hover over each button on the page | Each button displayed the correct styling when hovered over | Pass |

`Coming-soon Page`

| Feature | Expected Outcome | Testing Performed | Result | Pass/Fail |
| --- | --- | --- | --- | --- |
| Heading - hover effect | Heading should zoom in when hovered on  | Hover over the heading on the page | Heading displayed the right transition when hovered on | Pass |
| Close button | Directs the user to the Home page | Clicked on the submit button | Directs to the Home page | Pass |
| Close button - hover effect | Transparent button with white text should change to white with purple text when hovered over.| Hover over each button on the page | Each button displayed the correct styling when hovered over | Pass |