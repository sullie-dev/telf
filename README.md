#  TELF

[View project here](http://sullie-dev.github.io/telf)

---

TELF consists of a landing, contact and top tefl spot pages for a newly founded TEFL company which is looking to disrupt the current TEFL market by reimagining how TEFL certification is obtained.

The landing page will show off 3 courses along with 2 internships which will include; pricing, pre registration form, some basic information on the course or internship.

![Am I responsive image](https://sullie.dev/wp-content/uploads/2021/09/Am-I-responsive-1.png)

Responsiveness was checked using [Am I responsive](http://ami.responsivedesign.is/)

## Deployment
Project is deployed using GitHub pages, to deploy projects on GitHub pages;
 1. Navigate to **Settings** in the GitHib repo
 1. Navigate to **Pages** 
 1. **Select branch** to be built from 
 1. Wait for the build to be completed.
 1. You will be provided with a link which will look like; 
 ```https://[your-github-name].github.io/[repository name]```

## Features
---
- Navigation    
  - The navigation is located at the top of the page, which shows the TEFL logo on the top left hand side of the screen which links to the home page
  - The main navigation is found to the top right of the screen and contains links to the Home, Contact, and Top spots pages
  - There is a secondary navigation located in the footer under the tile ```sitemap```

- Header
  - Contains a CTA (call to action) for the user to input their name and email address for newsletters and follow ups.
  - User is required to consent to being contacted to comply with GDPR
  ![header sign up](https://sullie.dev/wp-content/uploads/2021/09/contact-form.png)

- FAQ
  - Home page contains an expandable faq section which is a great tool to help boost SEO on a webpage as it allows web page crawlers to see there is relevant information to what is on the site.

  ![FAQ section](https://sullie.dev/wp-content/uploads/2021/09/faq.png)

- Contact
  - The contact page has a larger form in order to collect information for the user to be reached back out to as they're able to leave a specific message about courses, internships, or general queries

  ![Contact Us  form](https://sullie.dev/wp-content/uploads/2021/09/contact.png)
  - User is again required to give consent ot be contacted, as it is illegal to contact (such as cold call) without the users express permission
##Testing 
---
- The site has been tested on the desktop versions of Chrome, Safari, and firefox.
- The site tested using the dev tools device tool to make sure the breakpoints function on all sizes
- The site was tested on mobile devices of different screen sizes to check for breakpoints and responsiveness

### Validation Testing
- HTML
  - No errors returned, validation was taking place throughout the development phase to fix any validation errors which came up
  ![html validation](https://sullie.dev/wp-content/uploads/2021/09/html-validation.png)
  - Any errors which would have shown were fixed when the file was checked locally.
- CSS
  - No errors returned, validation was taking place throughout the development phase to fix any validation errors which came up.
  - 19 warnings showing for font-awsome css
  ![CSS validation](https://sullie.dev/wp-content/uploads/2021/09/CSS-Warnings.png)

- Websites performance and accessibility is checked by using lighthouse in dev tools.
![Accessibility score](https://sullie.dev/wp-content/uploads/2021/09/light-house.png)
  - accessibility could be improved by;
    - Adjust the contrast of the font color and backgrounds
    - Layout of headers and sequential ordering
## Bugs:
#### Solved bugs:
- Changes to index.html did not commit due to ```git add .``` being run inside the assets folder. 
    - This was resolved by going running ```git add .``` in the root directory
- Form inputs using incorrect styles at brea points
  - Fixed by using the id's for the form inputs rather than the input type
- Bottom FAQ overflows into the footer.
  - Fixed by adjusting height of div container for FAQ
- Images not displaying on github pages
  - Fixed by adjusting file path to not contain ```/``` at the beginning of the file path.
- Top spots nav link did not show that it was the active page like other links
  - Add ```class="active"``` to the link
#### Unsolved bugs:
- Spanish internship on mobile is floating to the right and not aligning with with the Vietnam text
- Top spots floats to the next line on small screens
## Content
---
#### Credits
- Header was inspired by the [Love running project](https://github.com/sullie-dev/love-running)
- Javascript for **Find out more** button was researched using Google and Stack Overflow to confirm it's functionality

#### Media

All images were taken from [unsplash](https://unsplash.com)
- [hero-image.jpg](https://unsplash.com/photos/uWVWQ8gF8PE)
- [vietnam.jpg](https://unsplash.com/photos/v63UL8s28Ew)
- [spain.jpg](https://unsplash.com/photos/cB4Uqoc9D9k)
- [contact-js.jpeg](https://unsplash.com/photos/UoqAR2pOxMo)
- [china.jpeg](https://unsplash.com/photos/5h_dMuX_7RE)
- [japan.jepg](https://unsplash.com/photos/8sOZJ8JF0S8)
- [italy.jpeg](https://unsplash.com/photos/cYrMQA7a3Wc)
- [online.jpeg](https://unsplash.com/photos/ylveRpZ8L1s)

<br>

- contour-bg generated using [bgjar](https://bgjar.com/)
- polygon background clip generated using [bennettfeely](https://bennettfeely.com/clippy/)

## Technologies used
- HTML 5
- CSS 3
- JavaScript
- Font Awsome
- GitHub