# PETRA Website
The Petra website is designed to be a responsive website allowing visitors to view it on a range of devices. It allows visitors to find information about the ancient city of Petra.

![preview of the site](documentation/preview.jpg)
[View Petra on Github Pages](https://ahmadalmasridev.github.io/petra/)

---

## CONTENTS

- [PETRA Website](#petra-website)
  - [CONTENTS](#contents)
  - [**User Experience (UX)**](#user-experience-ux)
    - [**Initial Discussion**](#initial-discussion)
    - [**User Stories**](#user-stories)
  - [**Design**](#design)
    - [**Colour Scheme**](#colour-scheme)
    - [**Typography**](#typography)
    - [**Imagery**](#imagery)
    - [**Features**](#features)
    - [General features on each page](#general-features-on-each-page)
    - [Accessibility](#accessibility)
  - [Technologies Used](#technologies-used)
    - [Languages Used](#languages-used)
    - [Frameworks, Libraries \& Programs Used](#frameworks-libraries--programs-used)
  - [Deployment \& Local Development](#deployment--local-development)
    - [Deployment](#deployment)
    - [Local Development](#local-development)
      - [How to Fork](#how-to-fork)
      - [How to Clone](#how-to-clone)
  - [Testing](#testing)
  - [Credits](#credits)
    - [Code Used](#code-used)
    - [Content](#content)
    - [ Media](#media)
    - [ Acknowledgments](#acknowledgments)

---

## **User Experience (UX)**
<br>

### **Initial Discussion**

The Petra website is an information portal about the ancient city and the beautiful scenerys inside and around it, the visitor can go through the various articles and photos so that they can get a rough idea of what they can expect when they visit Petra.

Key information for the site
- Articles regarding Petra.
- Photos of variuos parts of the city.
- A virtual tour video.
- A form to contact and ask questions.
- A couple of good tours from tripadvisor.com.
- A way to check our socialmedia pages.

### **User Stories**
 **Visitor Goals**
  - To be able to view the site on a range of device sizes.
  - To be able to navigate through the website with ease.
  - To be able to ask questions through the website.
  - To provide the user with relevant information regarding Petra.
  
**First Time Visitor Goals**
  - I want to know what is Petra and where is it.
  - I want to see some photos of the city.
  - I want to see videos that contains scenes from Petra.
  - I want to ask some questions.
  - i want to check there socialmedia.

**Returning Visitor Goals**
  - I want to be able to easily ask questions.
  - I want to check the latest tours in the city.
  - I want to check the virtual tour video.
---
## **Design**
<br>

The initial design was inspired by two websites templates online,
I have credited these in the [credits](#credits) section.

### **Colour Scheme**

![the site color palette](documentation/palette.jpg)

The website uses a palette of earth sand colours that can be seen in the rocky mountains in Petra, The colour palette was created using the Coolors website.

### **Typography**

Google Fonts was used for the following fonts:

Fraunces is used for headings on the site.

![Fraunces font](documentation/font-fraunces.jpg)

Inter is used for the body text on the site.

![Inter font](documentation/font-inter.jpg)

### **Imagery**
The images used are royality free images downloaded from two photobanks, and the video is from Youtube. I have credited these in the [credits](#credits) section.

Wireframes were created with [Balsamiq](https://balsamiq.com) Wireframes program.

<details close>
<summary>Home Page Wireframe </summary>

![Home Page Wireframe Image](documentation/wireframe-index.jpg)

</details>

<details close>
<summary>Contact Page Wireframe </summary>

![Contact Page Wireframe Image](documentation/wireframe-contact.jpg)

</details>

<details close>
<summary>Photo Page Wireframe </summary>

![Photo Page Wireframe Image](documentation/wireframe-article.jpg)

</details>
<br>

### **Features**

The website is a single page design with five sections, four of which are accessible from the navigation menu (home, gallery, about, tours & contact pages). The fifth page is a contact form page which is shown once a user clicks the contact navigation button or through contact us button at the end of the home page.
And also has two seperate pages (article and photo pages) these pages are accessible once the user clicks a photo from the gallery or an article from the about sections.
<details close>
<summary>Index Page Preview</summary>

![the index page preview](documentation/page-index.jpg)

</details>



- All Pages on the website have:

  - A responsive navigation bar at the top which allows the user to navigate through the site. To the left of the navigation bar is a logo. To the right is the navigation bar with the links to the websites pages (home, gallery, about, tours, and contact). To allow a good user experience of the site. When viewing with mobile devices the navigation links change to a vertical list. This was implemented to give the site a clean look and to promote a good user experience. There is also a go to top button that appears in all the pages (exept the contact page) once you start scrolling the website and other UI interaction elements like buttons, links and images.

    <details close>
    <summary>Navigation Bar</summary>

    ![navigation bar](documentation/gif-nav.gif)
        
    </details>
 

    <details close>
    <summary>Buttons And Captions Hover Effect</summary>

    ![images hover effect](documentation/gif-button.gif)  ![images hover effect](documentation/gif-photo-captions.gif)
        
    </details>
  
  - A footer (exept the photo page) which contains social media icon links to facebook, twetter, youtube, and instagram. Icons were used to keep the footer clean and because they are universally recognisable.

    <details close>
    <summary>Social Media Links</summary>

    ![social media links](documentation/gif-media.gif)
        
    </details>

- Home Page.
  
  The home page consist of five sections:

    - **The Hero Section**  
        it contains a priview of the main article with a button that links to that article and also through clicking the hero image.

        <details close>
        <summary>Hero Section Preview</summary>

        ![hero section preview](documentation/section-hero.jpg)
            
        </details>
        <br/>
        
    - **The Gallery Section**  
        contains a virtual video tour and a photo gallery. 

        <details close>
        <summary>Gallery Section Preview</summary>

        ![video preview](documentation/section-video.jpg)
        
        ![gallery preview](documentation/section-photo-gallery.jpg)
            
        </details>

    - **The About Section**  
        contains a number of articles and information about the city. Each article is linked to a seperate html page.          

        <details close>
        <summary>About Section Preview</summary>

        ![about section preview](documentation/section-about.jpg)
        
        </details>
    
    - **The Contact Us Section**  
        contains a button that is linked to the contact html page.          

        <details close>
        <summary>Contact Us Section Preview</summary>

        ![contact section preview](documentation/section-contact.jpg)
        
        </details>
        
    - **The Tours Section**  
        contains a number of [tripadvisor](https://www.tripadvisor.com) tours. each element functions as an external link that opens in a new page.

        <details close>
        <summary>Contact Tours Preview</summary>

        ![tours section preview](documentation/section-tours-footer.jpg)
        
        </details>

- Article Page.

    Each page contains an article with a couple of images.

    <details close>
    <summary>Article Page Preview</summary>

    ![article page preview](documentation/page-article.jpg)
    
    </details>

- Contact Page.

    The contact page contains a form that allows the visitor to ask question and send messages. And also gives another way to contact through email.

    <details close>
    <summary>Contact Page Preview</summary>

    ![contact page preview](documentation/page-contact.jpg)
    
    </details>

- Photo Page.

    The photo page plays of a black canvas to the photos, also contains a button that returns the visitor back to the gallery. 

    <details close>
    <summary>Photo Page Preview</summary>

    ![photo page preview](documentation/page-photo.jpg)
    
    </details>
    
### General features on each page
    
- The website is designed to be user friendly and all the pages are responsive. The visitor can use it with a varaity of screen sizes and resolutions.
the breacking points used, are from this [article](https://testsigma.com/blog/css-breakpoints/#What_are_common_breakpoints).

    Responsivenes:
    
    -   <details close>
        <summary>992px Preview</summary>

        ![992px preview](documentation/respons-992.png)

        </details>

    -   <details close>
        <summary>768px Preview</summary>

        ![768px preview](documentation/respons-768.png)

        </details>

    -   <details close>
        <summary>480px Preview</summary>

        ![480px preview](documentation/respons-480.png)

        </details>

- When the user hovers on an image a captions appears with information about the image. each image when clicked is a link to a seperate html page. This photo gallery was made using flexbox folowing the information from these articles:
  
  - [article](https://blog.logrocket.com/responsive-image-gallery-css-flexbox/)  
  - [article](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)  

            
    <details close>
    <summary>Gallery Captions</summary>

    ![Gallery Captions](documentation/gif-gallery-hover.gif)

    </details>

- The layout for the about and the tours was made using css grid. It is also responsive, and was accomplished by the help from this [article](https://css-tricks.com/snippets/css/complete-guide-grid/)

    
   
        

- The images has a zoom hover effect similer to the one that was used in the love running project by [code institute](https://codeinstitute.net/).

    <details close>
    <summary>Images Hover Effect</summary>

    ![images hover effect](documentation/gif-image.gif)
        
    </details>

- The outline in the input fields change color when focused.

    <details close>
    <summary>Input Outline</summary>

    ![input outline](documentation/gif-contact-input-focus.gif)
        
    </details>
    
- The website dos not have a fixed header. Instead a go to top button is used with smooth scrolling inspired from this [article](https://levelup.gitconnected.com/how-to-implement-scroll-to-top-with-only-css-ae27cb9d4678).


- The embeded video iframe responsiveness was accomplished by the istructions from this [article](https://www.w3schools.com/howto/howto_css_responsive_iframes.asp)

    <details close>
    <summary>Images Hover Effect</summary>

    ![images hover effect](documentation/gif-image.gif)
        
    </details>


### Accessibility

I have been mindful during coding to ensure that the website is as accessible friendly as possible. I have achieved this by:

- Using semantic HTML.
- Using descriptive alt attributes on images on the site.
- Providing information for screen readers where there are icons used - and no text - such as the review ratings for books & footer icons.
- Ensuring that there is a sufficient colour contrast throughout the site.
- Ensuring menus are accessible by marking the current page as current for screen readers.

---
## Technologies Used


### Languages Used

HTML and CSS were used to create this website.


### Frameworks, Libraries & Programs Used

Balsamiq- Used to create wireframes.

Git - For version control.

Github - To save and store the files for the website.

Google Fonts - To import the fonts used on the website.

Font Awesome - For the iconography on the website.

Google Dev Tools - To troubleshoot and test features, solve issues with responsiveness and styling.

[online-convert](https://www.online-convert.com) To change to webp format.

[Am I Responsive?](https://ui.dev/amiresponsive) To show the website image on a range of devices.


## Deployment & Local Development

### Deployment

Github Pages was used to deploy the live website. The instructions to achieve this are below:

1. Log in (or sign up) to Github.
2. Find the repository for this project, petra.
3. Click on the Settings link.
4. Click on the Pages link in the left hand side navigation bar.
5. In the Source section, choose main from the drop down select branch menu. Select Root from the drop down select folder menu.
6. Click Save. Your live Github Pages site is now deployed at the URL shown.

### Local Development

#### How to Fork
How to Fork
To fork the petra repository:

1. Log in (or sign up) to Github.
2. Go to the repository for this project, AhmadAlmasriDev/petra.
3. Click the Fork button in the top right corner.


#### How to Clone
To clone the petra repository:

1. Log in (or sign up) to GitHub.
2. Go to the repository for this project, AhmadAlmasriDev/petra.
3. Click on the code button, select whether you would like to clone with HTTPS, SSH or GitHub CLI and copy the link shown.
4. Open the terminal in your code editor and change the current working directory to the location you want to use for the cloned directory.
5. Type 'git clone' into the terminal and then paste the link you copied in step 3. Press enter.


## Testing

Start as you mean to go on - and get used to writing a TESTING.md file from the very first project!

Testing requirements aren't massive for your first project, however if you start using a TESTING.md file from your first project you will thank yourself later when completing your later projects, which will contain much more information.
  
Use this part of the README to link to your TESTING.md file - you can view the example TESTING.md file [here](milestone1-testing.md)

## Credits

👩🏻‍💻 View an example of a completed Credits section [here](https://github.com/kera-cudmore/BookWorm#Credits)

The Credits section is where you can credit all the people and sources you used throughout your project.

### Code Used

If you have used some code in your project that you didn't write, this is the place to make note of it. Credit the author of the code and if possible a link to where you found the code. You could also add in a brief description of what the code does, or what you are using it for here.

### Content

Who wrote the content for the website? Was it yourself - or have you made the site for someone and they specified what the site was to say? This is the best place to put this information.

###  Media

If you have used any media on your site (images, audio, video etc) you can credit them here. I like to link back to the source where I found the media, and include where on the site the image is used.
  
###  Acknowledgments

If someone helped you out during your project, you can acknowledge them here! For example someone may have taken the time to help you on slack with a problem. Pop a little thank you here with a note of what they helped you with (I like to try and link back to their GitHub or Linked In account too). This is also a great place to thank your mentor and tutor support if you used them.
