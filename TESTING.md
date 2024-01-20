# Grizk Art Gallery -  Testing

![Grizk Art Gallery shown on a variety of screen sizes](documentation/features/home-page.PNG)

Visit the deployed site: [Grizk Art Gallery](https://gokwori.github.io/Grizk-Gallery/)

- - -

## CONTENTS

* [Feature Testing](#feature-testing)
* [User Story Testing](#user-story-testing)
* [Browser Compatibility](#browser-compatibility)
* [Responsiveness Testing](#responsiveness-testing)
* [Code Validation](#code-validation)
* [Lighthouse](#lighthouse)

Testing occurred continuously throughout the entire development process. I employed Chrome Developer Tools extensively during the build to identify and resolve issues promptly.

Throughout the development phase, I incorporated Google Developer Tools to verify the proper functioning of elements and to aid in diagnosing problems when they arose.

The console within the developer tools was instrumental in dissecting and validating small sections of JavaScript code. It served not only to confirm the functionality of the code but also to troubleshoot any encountered issues.

To guarantee responsiveness across diverse screen sizes and devices, I meticulously reviewed each page using both Google Chrome Developer Tools and the Microsoft Edge Inspector tool.

- - -

## Feature Testing

I tested each feature of my website to make sure that user interactions, forms, navigation, and any implemented functionalities work seamlessly. This involves checking the accuracy, reliability, and user-friendliness of each feature.

`Generic Features`

| Feature | Expected Outcome | Testing Performed | Result | Pass/Fail |
| --- | --- | --- | --- | --- |
| The Site's title | Link directs the user back to the home page | Clicked title | Home page reloads | Pass |
| Navigation menu | Switches to the selected menu tab with the selected tab highlighted | Clicked on menu tabs  | Switches between different pages with the current page tab being highlighted | Pass |
| Social-media links| Link directs the user to the art gallery's social media page in a new tab | Clicked on each link | Redirected to the gallery's social media page | Pass |
| Social-media links - hover effect| All social-media icons with white background and purple font should change to purple and white | Hover over each icon | Each icon displayed the correct styling when hovered over | Pass |

| Site Title | Navigation Menu | Social Media Links |
| --- | --- | --- |
| ![Site Title](testing/features/title-test.gif)| ![Nav Menu](testing/features/nav-test.gif) | ![Social Media](testing/features/media-links.gif)|

- - -

`Home Page`

| Feature | Expected Outcome | Testing Performed | Result | Pass/Fail |
| --- | --- | --- | --- | --- |
| Autoplaying Carousel | Automatically starts slideshow or manually move between slides| Refreshed page & clicked on Prev and Next buttons | Carousel played automatically upon refresh and able to navigate between slides using buttons | Pass |
| Thumbnail Images - hover effect | All thumbnail images should zoom in when hovered on | Hover over each thumbnail on the page | Each image displayed the right transition when hovered on | Pass |
| Thumbnail Images | Link directs the user back to an enlarged image in a new tab | Click each thumbnail on the page | Each image displayed an enlarged portrait in a new tab | Pass |
| Exhibition list items - hover effect | All list items images should zoom in when hovered on | Hover over each item in the upcoming exhibition section on the page | Each item displayed the right transition when hovered on | Pass |
| Exhibition item Buttons | Directs the user to the coming-soon page | Clicked on all buttons | Directs to the coming-soon page | Pass |
| All headings - hover effect | All headings should zoom in when hovered on  | Hover over every heading on the page | Each heading displayed the right transition when hovered on | Pass |
| All buttons - hover effect | All transparent buttons with white text should change to white with purple text when hovered over. | Hover over each button on the page | Each button displayed the correct styling when hovered over | Pass |
| Location thumbnail | Directs the user to the coming-soon page | Clicked on each location thumbnail | Directs to the coming-soon page | Pass |
| Location thumbnail - hover effect| All location thumbnails should zoom in when hovered on  | Hover over each location thumbnail | Each item displayed the right transition when hovered on | Pass |

| Carousel | Image Thumbnail | Exhibition items |
| --- | --- | --- |
| ![Carousel](testing/features/carousel.gif)| ![Image Thumbnail](testing/features/thumbnail-images.gif) | ![Exhibition Items](testing/features/exhibition-items.gif)|

| Location Thumbnail | Headings | 
| --- | --- |
| ![Location Thumbnail](testing/features/location-thumbnail.gif)| ![Headings](testing/features/headings.gif) |

- - -

`Gallery Page`

| Feature | Expected Outcome | Testing Performed | Result | Pass/Fail |
| --- | --- | --- | --- | --- |
| All headings - hover effect | All headings should zoom in when hovered on  | Hover over every heading on the page | Each heading displayed the right transition when hovered on | Pass |
| Thumbnail Images - hover effect | All thumbnail images should zoom in when hovered on | Hover over each thumbnail on the page | Each image displayed the right transition when hovered on | Pass |
| Thumbnail Images | Link directs the user back to an enlarged image in a new tab | Click each thumbnail on the page | Each image displayed an enlarged portrait in a new tab | Pass |

| Thumbnail Images | Clickable Images | 
| --- | --- |
| ![Thumbnail Images](testing/features/thumbnail-hover.gif) | ![Clickable Images](testing/features/clickable-images.gif) |

- - -

`Exhibition Page`

| Feature | Expected Outcome | Testing Performed | Result | Pass/Fail |
| --- | --- | --- | --- | --- |
| All headings - hover effect | All headings should zoom in when hovered on  | Hover over every heading on the page | Each heading displayed the right transition when hovered on | Pass |
| Thumbnail Images - hover effect | All thumbnail images should zoom in when hovered on | Hover over each thumbnail on the page | Each image displayed the right transition when hovered on | Pass |
| Thumbnail Images | Link directs the user back to an enlarged image in a new tab | Click each thumbnail on the page | Each image displayed an enlarged portrait in a new tab | Pass |
| Exhibition list items - hover effect | All list items images should zoom in when hovered on | Hover over each item in the upcoming exhibition section on the page | Each item displayed the right transition when hovered on | Pass |
| Exhibition item Buttons | Directs the user to the coming-soon page | Clicked on all buttons | Directs to the coming-soon page | Pass |
| All buttons - hover effect | All transparent buttons with white text should change to white with purple text when hovered over. | Hover over each button on the page | Each button displayed the correct styling when hovered over | Pass |

| Hover Effect | Clickable Links | 
| --- | --- |
| ![Thumbnail Images](testing/features/exhibition-hover.gif) | ![Clickable Images](testing/features/exhibition-clicks.gif) |

- - -

`Booking Page`

| Feature | Expected Outcome | Testing Performed | Result | Pass/Fail |
| --- | --- | --- | --- | --- |
| Heading - hover effect | Heading should zoom in when hovered on  | Hover over the heading on the page | Heading displayed the right transition when hovered on | Pass |
| Submit button | Directs the user to the Thank-you page | Clicked on the submit button | Directs to the Thank-you page | Pass |
| Submit button - hover effect | Transparent button with white text should change to white with purple text when hovered over.| Hover over each button on the page | Each button displayed the correct styling when hovered over | Pass |

| Form Validation | Form Submission | 
| --- | --- |
| ![Form Validation](testing/features/form-validation.gif) | ![Form Submission](testing/features/submit-form.gif) |

- - -

`Thank-you Page`

| Feature | Expected Outcome | Testing Performed | Result | Pass/Fail |
| --- | --- | --- | --- | --- |
| Heading - hover effect | Heading should zoom in when hovered on  | Hover over the heading on the page | Heading displayed the right transition when hovered on | Pass |
| Close button | Directs the user to the Home page | Clicked on the submit button | Directs to the Home page | Pass |
| Close button - hover effect | Transparent button with white text should change to white with purple text when hovered over.| Hover over each button on the page | Each button displayed the correct styling when hovered over | Pass |

- - -

`Coming-soon Page`

| Feature | Expected Outcome | Testing Performed | Result | Pass/Fail |
| --- | --- | --- | --- | --- |
| Heading - hover effect | Heading should zoom in when hovered on  | Hover over the heading on the page | Heading displayed the right transition when hovered on | Pass |
| Close button | Directs the user to the Home page | Clicked on the submit button | Directs to the Home page | Pass |
| Close button - hover effect | Transparent button with white text should change to white with purple text when hovered over.| Hover over each button on the page | Each button displayed the correct styling when hovered over | Pass |

- - -

## User Story Testing

I validated that my website meets the needs and expectations of different user groups. I tested scenarios based on user stories to ensure that the features align with the goals and requirements of first-time visitors, returning visitors, frequent users, art lovers, artists, and general users.

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

## Browser Compatibility

I confirmed that my website performs consistently across various web browsers. Testing on popular browsers like Google Chrome, Safari, and Microsoft Edge was crucial to ensure a consistent and reliable user experience.

| Browser Tested | Intended Appearance | Intended Responsiveness | 
| --- | --- | --- | 
| Google Chrome | Good  | Good | 
| Safari | Good  | Good | 
| Microsoft Edge | Good  | Good | 

- - -

    Google Chrome

| Home Page |  |  |
| --- | --- | --- |
| ![Home Page](testing/browser/c1.png) | ![Home Page](testing/browser/c2.png) | ![Home Page](testing/browser/c3.png) | 

| Gallery Page |  |  
| --- | --- | 
| ![Gallery Page](testing/browser/c4.png) | ![Gallery Page](testing/browser/c5.png) | 

| Exhibition Page | Booking Page |
| --- | --- | 
|![Exhibition Page](testing/browser/c6.png) | ![Booking Page](testing/browser/c7.png) | 

    Safari

| Home Page |  |  |
| --- | --- | --- |
| ![Home Page](testing/browser/s1.png) | ![Home Page](testing/browser/s2.png) | ![Home Page](testing/browser/s3.png) | 

| Gallery Page |  |  
| --- | --- | 
| ![Gallery Page](testing/browser/s4.png) | ![Gallery Page](testing/browser/s5.png) | 

| Exhibition Page | Booking Page |
| --- | --- | 
|![Exhibition Page](testing/browser/s6.png) | ![Booking Page](testing/browser/s7.png) | 

    Microsoft Edge

| Home Page |  |  |
| --- | --- | --- |
| ![Home Page](testing/browser/m1.png) | ![Home Page](testing/browser/m2.png) | ![Home Page](testing/browser/m3.png) | 

| Gallery Page |  |  
| --- | --- | 
| ![Gallery Page](testing/browser/m4.png) | ![Gallery Page](testing/browser/m5.png) | 

| Exhibition Page | Booking Page |
| --- | --- | 
|![Exhibition Page](testing/browser/m6.png) | ![Booking Page](testing/browser/m7.png) | 

- - -

## Responsiveness Testing

I evaluated how well my website adapts to different devices and screen sizes. Testing the responsiveness of my design ensured that the layout, images, and features adjust appropriately for optimal viewing on desktops, tablets, and mobile devices.

| Device Tested | Screen  | Site Response | Renders as intended |
| --- | --- | --- | --- | 
| iPhone 12 Pro | 390px * 844px  | Good | Yes |
| iPhone 14 Pro Max | 430px * 932px  | Good | Yes |
| iPad Mini | 768px * 1024px  | Good | Yes |
| iPad Air | 820px * 1180px  | Good | Yes |

- - -

    iPhone 12 Pro

| Home Page | Gallery Page | Exhibition Page  | Booking Page |
| --- | --- | --- | --- |
| ![Home Page](testing/responsiveness/i1.png) | ![Gallery Page](testing/responsiveness/i2.png) | ![Exhibition Page](testing/responsiveness/i3.png) | ![Booking Page](testing/responsiveness/i4.png) |

    iPhone 14 Pro Max

| Home Page | Gallery Page | Exhibition Page  | Booking Page |
| --- | --- | --- | --- |
| ![Home Page](testing/responsiveness/f1.png) | ![Gallery Page](testing/responsiveness/f2.png) | ![Exhibition Page](testing/responsiveness/f3.png) | ![Booking Page](testing/responsiveness/f4.png) |

   iPad Mini

| Home Page | Gallery Page | Exhibition Page  | Booking Page |
| --- | --- | --- | --- |
| ![Home Page](testing/responsiveness/d1.png) | ![Gallery Page](testing/responsiveness/d2.png) | ![Exhibition Page](testing/responsiveness/d3.png) | ![Booking Page](testing/responsiveness/d4.png) |

  iPad Air

| Home Page | Gallery Page | Exhibition Page  | Booking Page |
| --- | --- | --- | --- |
| ![Home Page](testing/responsiveness/e1.png) | ![Gallery Page](testing/responsiveness/e2.png) | ![Exhibition Page](testing/responsiveness/e3.png) | ![Booking Page](testing/responsiveness/e4.png) |

Full testing was also performed on the following devices with the same test outcome as above:

* Laptop:
  * Macbook Pro 2017 13"
  * Hp Spectre x360
  * HP EliteBook 830 G10 13.3"
  * Dell Latitude 5530 15"

* Mobile Devices:
  * iPhone 13 Pro Max
  * Samsung S10+

Each device tested the site using the following browsers:

* Google Chrome
* Safari
* Microsoft Edge

- - -

## Code Validation

I validated my website's code to ensure it adheres to industry standards and best practices. Using tools like W3C validators, I checked for HTML, CSS, and accessibility compliance to maintain a clean and error-free codebase.

[W3C](https://validator.w3.org/) was used to validate the HTML on all pages of the website. It was also used to validate the CSS.

| Page Tested | Validation Output |
| --- | --- |
| Home Page | ![index.html](testing/w3/index-w3.png) | 
| Gallery Page | ![gallery.html](testing/w3/gallery-w3.png) | 
| Exhibition Page | ![exhibition.html](testing/w3/exhibition-w3.png) | 
| Booking Page | ![booking.html](testing/w3/booking-w3.png) | 
| Thank-you Page | ![thank-you.html](testing/w3/thank-you-w3.png) | 
| Coming-soon Page | ![coming-soon.html](testing/w3/coming-soon-w3.png) | 
| CSS |![style.css](testing/w3/css-validator.png) | 

- - -

## Lighthouse

I utilised Lighthouse within Chrome Developer Tools to assess my website's performance, accessibility, best practices, and SEO. Leveraging Lighthouse reports, I optimised my website for speed, user experience, and search engine visibility.

### Desktop Results

All pages of the site are achieving a score of above 90 across the 4 categories.

| Page Tested | Validation Output |
| --- | --- |
| Home Page | ![index.html](testing/lighthouse/desktop-home-page.png)| 
| Gallery Page | ![gallery.html](testing/lighthouse/desktop-gallery-page.png) | 
| Exhibition Page | ![exhibition.html](testing/lighthouse/desktop-exhibition-page.png)| 
| Booking Page | ![booking.html](testing/lighthouse/desktop-booking-page.png) | 
| Thank-you Page | ![thank-you.html](testing/lighthouse/desktop-thank-you-page.png) | 
| Coming-soon Page | ![coming-soon.html](testing/lighthouse/desktop-coming-soon-page.png) | 

  
- - -






