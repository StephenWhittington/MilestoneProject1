# Thrash Band

# by Stephen Whittington

This website is based on a Thrash metal band called Mutually Assured Destruction short for M.A.D, It was built for user purpose to see upcoming
tour dates and new band material when available, Also to get the band hired for events such as weddings and birthdays. It contains a simple layout and navigation
for the user to navigate their way through a 5 page responsive website that not only looks good on mobile first but desktop as well.

The Web page is mainly aimed at the fan base and shows the bands most recent recordings/Music with a video file and youtube footage of the band playing live and
recording in the studio, It also shows information on all dates and venues for the bands upcoming UK tour in june/july 2019. 

## UX process for my Website

I started with a desktop layout for the website using figma, The site is aimed at the fan base so i wanted the user to be able to navigate easily
to each page without any hesitation. The fan wants to be able to see the latest recordings or music the band has made, So by a page link to music they can see
the latest uploads from the band with a sign up form to the site to let them know of any updates ASAP. This website helps the user achieve what they need
with its simple layout style and colours, The user wants to get as much information as possible with little effort and this website helps them achieve that goal.

#### Color Scheme

I decided after my wireframe layout that i just wanted a simple colour base that was eye catching my mentor recommended (https://material.io/tools/color/#!/?view.left=0&view.right=0),
using this i was able to find the perfect color layout i wanted my website to have. I am very happy with the basic color scheme i have selected.

 * Grey <code>#343a40</code>
 * Red <code>#ff4141</code>

### List of user Stories

* As a user/fan, I want to hear and view the latest content, so i can be notified of the bands newest releases.
* As a user/fan, I want to see information on the next tour/event, so i can choose dates and buy tickets.
* As a customer, I want to be able to fill out a book-ins form, so i can hire the band for a wedding or birthday party.
* As a user/fan, I want to be able to access the bands social pages, so i can communicate by social media.
* As a user/fan, I want to be able to see information and pictures of the band/members, so i can find out more about them.

[This is a link to my wireframe figma](https://github.com/StephenWhittington/thrashband/blob/master/assets/images/Stephen%20Wireframe.pdf)


# Features

## Existing Features

* **Band Logo/Name** - Visual representation on the band that is unique, And eye catching to the user.

* **Book-ins Form** - Allows users to see the bands availability to perform, by having them fill a form in with their information.

* **Collapsing Navbar** - Allows the mobile user to access the website pages easily, by clicking the dropdown menu.

* **Video on Home Page** - The user can see the bands latest recording in the studio, and watch in fullscreen if they want to.

* **Social Media links/Icons** - Allows users to easily follow the band, by clicking on the icons in the footer.

* **Band Information/Photos** - Allows the user to scroll through images of the band and read about the members.

* **Added Navigation on Home Page** - Allows users to access the tour page and see dates, by clicking on the button link.

## Features left to implement

* Adding a merchandise link with a drop down menu in the navbar.

* Implementing a carousel of live band images on home page maybe 3-5 pictures.


# Technologies Used

* [HTML5](https://en.wikipedia.org/wiki/HTML5)
    
     * The website uses Semantic Markup Language as its foundation.

* [CSS3](https://en.wikipedia.org/wiki/Cascading_Style_Sheets)
   
     * The website uses Cascading Style Sheets to implement design and customization. 
     
* [JQuery](https://jquery.com/)
   
     * The website uses JQuery The Document Object Model (DOM) to simplify manipulation.
     
* [Bootstrap v4](https://getbootstrap.com/)
     
     * This website uses bootstrap, To add HTML and CSS-based templates for typography,forms,buttons,navigation
       and other interface components.

* [Font Awesome](https://fontawesome.com/)
     
     * The website uses fontawesome, Because icons are a visual way to help add meaning to elements.
     
* [Fancybox3](https://fancyapps.com/fancybox/3/)
    
     * Recommended by my Mentor, The website uses fancybox to help images stand out from the rest and save time.

# Testing

### User Story Tests Completed
 
* **Music Page**

  1. Go to the "Music" page
  2. Try to play the audio and video links and test their controls
  3. Verify that both audio and video links play with controls
  4. Confirmed that the user can hear and view latest music/videos

* **Sign up Form**
  
  1. On the same page Scroll to the bottom
  2. Try to submit empty form without any information and verify that an error message about required fields appears
  3. Try to submit the form with all inputs filled in and verify that clicking sign up works
  4. Confirmed that the user can create a password to sign up to the site
    
* **Tour page / Buy Tickets**
  
  1. Click on view dates button on home page and verify that it takes you to the tour page
  2. Go to the "Tour" page
  3. Scroll to view dates of next tour and venues
  4. Click on "buy tickets" enter each form field with information verify that it works
  5. Confirm that the user can submit and cancel the modal

* **Book-ins Page for Hire**
  
  1. Go to "Book-ins" page
  2. Try to sumbit the empty form and verify that an error message about required fields appears
  3. Try to enter Name,Email,Date,Size,Message (verify that calendar works to pick dates)
  4. Try to click send with all information entered and confirm that the form works

* **Band Social Footer Icons**
   
  1. Scroll to the "Footer" of every page
  2. Try to click on all of the social media icons and verify that they take the user to the right site
  3. Confirmed that the links take the user to were they want to go

* **Band Page Pictures / Members**
  
  1. Go to the "Band" page
  2. Verify that each band member has a profile picture/Bio on themselves
  3. Try to click on images of the band playing and verify that it opens a slide to view them
  4. Confirm that the user can view/read the information they want

### How My Website Works On Different Browsers And Screen Sizes

I have tested my project in different screen sizes, and i am happy of how it works from mobile first set up to desktop.
After finishing most of my project i was advised by my mentor to hide some content on mobile first, So with CSS and media
queries i found out ways to hide content on mobile but show it on bigger devices. The home page for example shows the text
with the picture on bigger devices but on smaller it is hidden also my navbar was a little messy so i hid the icons on smaller devices.
I used a lot of rows and columns to make my webpage as responsive with little effort as possible and i am happy of how it looks.
I tested my website on chrome/IE/FireFox and it looks good on both when expanding and closing screen size for each page,
With Internet explorer i noticed that some things are different, like the audio links on the music page have a black background and
different style layout to chrome. I also noticed that forms when entering no information have a different error message to chrome. 
Overall i am happy with how my website looks on mobile,tablet and desktop screen sizes.

### Bugs And Problems

I discovered a few problems one mainly with my images on the band page and iframes on the music page, on IE/Firefox when stretched to full screen the
height media querie i added for 1200px doesn't seem to work. I found that if i remove the style media querie the pictures look
a little better, But it works fine on chrome and i was happy with how they looked.

* I fixed this by adding container to my section element instead of container-fluid, I removed all of the CSS media queries for
  height at 1200px.

I found one main bug with my page and its my modal on the tour page, i have "required" coded in but it doesn't seem to work
for the form field when i submit the form. This Bug/Problem i haven't fixed yet but the modal works when selecting the form fields
and entering the information required, and closes when cancel and buy are selected.

* I have made changes but not fixed this "required" bug.

I found another bug with the £ sign, when i enter this into my cloud9 code it has this outcome Â£15 after i save it and view it in the
browser, But if i change it in the browser with dev tools it doesn't have the same problem. 

* I managed to fix this by research and i needed to add <meta charset="UTF-8"> to my head element.

### Compatibility

To make sure users have a broad range of accessibility, i have tested my project on 3 major browsers in both desktop and mobile size.

* Chrome
* Mozilla Firefox
* Internet Explorer

# Deployment 

This project does not require any local deployment

My deployment and source code was all done via GitHub, You can find my repository here:

* **Repository**:(https://github.com/StephenWhittington/thrashband)

I have uploaded the source code using the master branch to **GitHub Pages.**

The live version of my site can be found here:

* **GitHub Pages**:(https://stephenwhittington.github.io/thrashband/)

I can confirm that there are no differences from the deployed and the development version.

# Credits

**Media**

* The images i used for my site are royalty free and only used for educational purposes only and can be found (https://pixabay.com/).

* The band photos are obtained from my computer/facebook and i have permission to use them.