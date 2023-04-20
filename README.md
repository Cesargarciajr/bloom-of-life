![Alt text](assets/images/Wireframes.png "wireframes")

# Bloom of Life

Welcome,

This website was developed to create a *Brazilian community* of new moms or pregnant women in Ireland, and was called **Bloom of Life**. The aim of the project is **connect, inspire, and share** experiences with each other. Provide shelter for those insecure mothers in a different country and away from family, and care for those who feel alone throughout the challenges of maternity.

## User Experience (UX)

### User Stories

  - #### First-Time Visitor Goals
    1. As a First Time Visitor, I want to know more about what the community can offer.
    2. As a First Time Visitor, I want to have a clear understanding of where everything is located so that I can quickly access it.
    3. As a First Time Visitor, I want to have to able to access the menu so that I can decide what I want before attending the community.

  - #### Returning Visitor Goals
    1. As a Returning Visitor, I want to check for any updates on the schedules.
    3. As a Returning Visitor, I want to be able to find the contact information.

  - #### Frequent User Goals
    1. As a Frequent User, I want to check for any updates on the schedules.
    2. As a Frequent User, I want to use the map on the contact page to add to the route of my GPS.

  - ### Color Scheme
    - The colors were chosen to remind Brazilian flag with a variation of greens and yellow as the image below

    ![Alt text](assets/images/colour-pallete.png "colour pallete")

    
    ### Typography
    - The website uses three different fonts in a consistant distribution for better experience:
        1. Send Flowers or fallback cursive (from google fonts)
        2. Indie Flower or fallback cursive (from google fonts)
        3. Sans- Serif or fall back Times New Roman

  - ### Site Structure
    - The site structure consist in a **"one-page"** with a "stiky" menu to make navigation easier through the website. The different sections are:

        #### Landing Section ####
        - Here the user can clearly see the name of purpose of the community as well as the Nav Menu which allows the user to go a specific content related to the community. The landing page is the Hero Image of two pragnant women holding flowers matching the name of the community.

        ![Alt text](assets/images/hero-section.png "Hero Section") 

        #### About Us Section ####
        - Here the user gets to know more about the organizer of the community and what she can offer as well as a little bit about her background and experiences. Also includes a picture of her to create some affection with the user.
        
        ![Alt text](assets/images/about-us-section.png "About Us Section")

        #### Our Community Section ####
        - This section is desgined as a gallery and some of the "pilar words" of the community so the user can relate and get a a a better understanding of what to expect and what can contribute to the community.

        ![Alt text](assets/images/our-community-section.png "Our Community Section") 

        #### Join Us Section ####
        - In this section, the user can find useful information about time, location, and also how to subscribe to the community. Also were allocated a mini Google maps for a better experience if the user needs to get direction
        
        ![Alt text](assets/images/join-us-section.png "Our Community Section") 

        #### Footer ####
        - And finally a footer with some useful links for social media and email.

        ![Alt text](assets/images/footer.png "Footer")

## Responsiveness
- The site was designed to be responsive and function on a range of screen sizes.

## Future Features
There are a number of features that would improve the User Experience that I would like to implement in the future:
- Have a Portuguese and English version of the website so the user can choose which language is preferable.
- Implement some of the lates content published in some of the social media such as Instagram of Facebook so the user might feel intrested and follow the social platforms as well.
- Comments and reviews would allow users to engage with the content and provide recommendations to other users.

___

## Technologies Used
I used the following technologies, platforms and support in building my project:
- Wireframes and mockups were designed in Balsamiq (https://balsamiq.com/wireframes/desktop/#)
- The website is built with HTML and CSS only.
- The Code Institute modules/lessons aided my learning and many of the concepts learned were applied in this project
- GitHub was used for the project repository (https://github.com/Cesargarciajr/bloom-of-life)
- Google Fonts was used for all fonts on the site (https://fonts.google.com/)
- FontAwesome was used for the social media icons which then had additional styling applied to them (https://fontawesome.com/v4/)
- Colors CO was used to create a colour pallete for this readme file (https://coolors.co/)
- Adobe Colors and contrast was used to pick color and check if the contrast was good enough for users (https://color.adobe.com/pt/create/color-contrast-analyzer)
- Also had to learn how to use flexbox which plays a important role in positioning the sections and elements in the website which I learned from W3 Schools (https://www.w3schools.com/default.asp)

___

## Testing
- Tested in differents mobile devices and chrome web browser
- Tested using the CCS validador (https://www.w3.org/)
- Tested using the HTML validator (https://validator.w3.org/nu/)

![Alt text](assets/images/css-checker.png "CSS report")
![Alt text](assets/images/html-checker.png "HTML report")

## Testing Process
| Test                | Action                   | Success Criteria  |
| -------------       |-------------             | -----|
| Landingpage loads      | Navigate to website URL  | Page loads < 5s, no errors |
| Links            | Click on each Navigation link  | Correct section is redirected action performed |
| Form validation  | Enter data into each input field, ensure only valid data is accepted | Form doesn't submit until correct data entered, error message shown |
| Responsiveness | Resize viewport window from 320px upwards with Chrome Dev Tools. Use Responsive Design Checker to test various mobile, tablet and large screen sizes | Page layout remains intact and adapts to screen size as intended except from footer |

--------

# Bugs/Issues
Debugging and troubleshooting were done constantly throughout development, however still two main problems with the website:

1. The Sticky menu at the top of the page was designed to facilitate the navigation during the user experience however when clicked any of the sections, it crops a little bit the top of the section


![Alt text](assets/images/cropped-top.png "cropped section")

- But it was supposed to look like this:


![Alt text](assets/images/about-us-section.png "Section")

2. Another bug I notice is when the website is in mobile version the footer goes behind my content but only when mobile:


![Alt text](assets/images/footer-mobile-bug.png "Footer bug")
