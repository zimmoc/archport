# Archport

Archport is a site made to showcase my sisters ARCHitecture PORTfolio while she progresses through the courses. The site targets potential employers to showcase how her talents have progressed through the courses.

![Responsive Mockup](/assets/images/readme/mockup.png)

## Features

- __Navigation Bar__

  - The navbar present on all pages is fully responsive on all devices. Including a "drawer" navbar on mobile devices.
  - The navbar includes links to the different pages, the active page is always highlighted.

  ![Big navbar](/assets/images/readme/small-navbar.png)

  ![Big navbar](/assets/images/readme/navbar.png)


 - __Landing section__

    - The landing section is a fully responsive section including a image and text box to welcome the user to the website and instantly convey any information you would find important.
    - It's fully responsive even on mobile devices where the text box and image will display in a column instead

    ![Landing section](/assets/images/readme/herosection.png)

- __Projects section__
    - Fully responsive cards to showcase some projects, complete with a image, heading and small text box.
    - Also features a interactive button that will take you to the full project page.

    ![Landing section](/assets/images/readme/projects-section.png)

- __Bio section__

    - Biography section with a image module and a text box.
    - This section will allow the user to get to know the architect and make it feel more personal.
    - Here you can showcase your deegre or any other important information you want the user to read.

    ![Bio section](/assets/images/readme/bio.png)

    - __Projects Page__
        - Here the user can see all the projects that's being showcased on the site
        - Here they can also read any short information about the project before clicking on it.

    ![Projects page](/assets/images/readme/portfolio-page.png)

## Project showcase

The project showcase pages are made using pre-created modules, since this site will feature a wide variety of projects it had to be able to adapt to showcase information the way it was intended.

- __Modules__

    - Hero module made for the same reasons as the landing section, convey any important information instantly and a hero image to pull you in.

    ![Hero module](/assets/images/readme/project-hero.png)

    - Simple text module with a heading

    ![Text module](/assets/images/readme/text-module.png)

    - Module with a image and text box, fully responsive on all screens.

    ![Text and image module](/assets/images/readme/text-img-module.png)

    - The modules also feature a class to make it the color desired, on this one the img and text order is reversed, same with the color.

    ![Reversed text and image module](/assets/images/readme/text-img-blue-module.png)

    - No portfolio showcase would be complete without a module to display a big image that stretches all across the screen and impresses everyone looking at it. 

    ![Full width image module](/assets/images/readme/img-module.png)

- __Navigation__

    - Making a site easy to understand and easy to navigate really makes a huge difference. Therefore this site features a "breadcrumb" to take you back to the projects page from the full project showcase page.

    ![Breadcrumb bar](/assets/images/readme/breadcrumb.png)

    - The thing with breadrumbs is that they are at the top and a user that's scrolled to the bottom of a long page really doesnt wanna scroll back up. Thats why there's a "Take me to the top" arrow.

    ![Jump to top arrow](/assets/images/readme/top-arrow.png)


## Contact form

Here the user can contact the architect with a message, they can also leave their name and email so the architect can contact them back to answer any questions.


![Contact form](/assets/images/readme/contact-form.png)

    


## Testing

I have tested all pages on this website both on a local deployment and a live deployment. I did not find any site or function breaking bugs but i did come accross some responsiveness problems that were easy to fix.

The website have been tested on several devices with different screens including, iPhone 14 pro, 2022 iPad pro landscape and portrait mode, laptop connected to a full hd 16:9 monitor and lastly a 16:10 laptop screen.

The site has worked flawlessly on all of them but there was a need for improved QoL when it comes to mobile devices.

So i sat my sister down infront of the website and asked her to navigate to a certain project, contact page and just the general feel of the website flow. 
Since she's an architect student she knows her way around the computer so this feedback is not that of a regular non-tech person but it still contained some value.

The ease of navigation and flow of the website was great according to her, and it was all easy to read and navigate around without having to scan the whole website. Things were in their "natural" position so to speak.

The only problem she had was that there was no "take me to the top" arrow after she had scrolled all the way down on a project showcase. I could duplicate the breadcrumb bar and put it at the bottom of the page aswell, but i wanted to try making a functional arrow.
So i added a "take me to the top" arrow but i did have trouble to make it send the user to the absolute top of the page, it stopped right under the breadcrumb which felt really bad. I managed to solve this problem on my laptop and iphone using a chrome based browser, for some reason safari on the ipad still wouldn't send me to the absolute top. I blame Apple and their inferior browser.

I was happy with this feedback and felt that i had made a good site thats easy to understand and navigate. I'm not a designer so there is much left to work on with the design but i feel happy with how it turned out.

### Validator

#### HTML

When running the HTML validator i found that i had done some small errors on a few pages.
They were all stray tags or unclosed tags. 
Except for the index.html where i have wrapped all my buttons in anchor tags with a href attribute to send the user to that page. This is apparently not good practice but i've left it like this for now since it doesnt cause any problems.

#### CSS

There were 3 errors in the css which all were values that didnt exist for that specific rule, so nothing site breaking but redundant code that doesnt do anything.

I also know for a fact that there is a lot of redundant code in the stylesheet but sometimes i really got lost when trying to fix a problem and wrote a lot of different things trying to reach my goal. And sometimes i forgot to go back and clean it up.
I would like to clean it up to also give me a better understanding of what works and what doesnt, but i will not do it now since i dont have the time for it if anything breaks.

## Validator testing


- HTML
  - 1 (4 times) error were returned when passing through the official [W3C validator](https://validator.w3.org/nu/?doc=https%3A%2F%2Fzimmoc.github.io%2Farchport%2Findex.html)

- CSS
  - No errors were found when passing through the official [(Jigsaw) validator](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fzimmoc.github.io%2Farchport%2Fassets%2Fcss%2Fstyle.css&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en)

### Unfixed Bugs

I have not found any unfixed bugs that change how the website looks or works.

## Deployment

- The site was deployed on GitHub pages
    - Main branch of repository always deployed
 
The live link can be found here - https://zimmoc.github.io/archport/

### Performance

- __Tests performed using [Pagespeed](https://pagespeed.web.dev/)__

- Mobile test

![mobile pagespeed](/assets/images/readme/reports/mobile.png)
![mobile pagespeed settings](/assets/images/readme/reports/mobile-settings.png)

- Desktop test

![desktop pagespeed](/assets/images/readme/reports/desktop.png)
![desktop pagespeed settings](/assets/images/readme/reports/desktop-settings.png)


## Credits 

All the code is written by me with the exception for some love-running code.
Whenever i got stuck or didnt understand how to implement something i used [w3schools](https://www.w3schools.com/) and [w3docs](https://www.w3docs.com/) to understand attributes and values.

I also used google whenever i couldnt make something work which sent me to different forums and help sites where people were asking about the same problem, I used that information to create my own solution.

### Content 

- The collapsible nav bar was mostly taken from the love-running project but modified to fit my page
- The icons used were taken from [Font Awesome](https://fontawesome.com/)
- Favicon by [Icons8](https://icons8.com/)

### Media

- All the photos used on this website were taken from my sisters school portfolio projects
