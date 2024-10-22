# Project Title

## Overview

### Purpose
The request was to create a website on mental health awareness that seeks to provide accessible, beginner-friendly information on mental health, including how to recognize common issues and manage stress.
I used this as my constant benchmark throughout the creating of the website, paying particular attention to, ease of use and clarity of message. 
I chose to seperate out the key areas easy to navigate

### Target Audience
As the request was for beginner level information I understood the target audience was people with limited to no existing knowledge of mental health issues.

## User Stories

### Must-Have User Stories
- **User Story 1:** Hero Section with a positive messsage.  
  **Acceptance Criteria:** Met with a nice image and positive message.
- **User Story 2:** Calming colors.  
  **Acceptance Criteria:** Nice selection of colors that create a calming feeling for those visiting the site.

### Should-Have User Stories
- **User Story 1:** Navigation Bar.  
  **Acceptance Criteria:** A standard structure to aid navigation.
- **User Story 2:** Adaptable layout.  
  **Acceptance Criteria:** Easy to use on multiple device sizes.


### Could-Have User Stories
- **User Story 1:** Videos for quotes and more information on internal pages.  
  **Acceptance Criteria:** Impliment videos alongside quotes and have links on the cards go to pages inside the site for more information instead of externally.
- **User Story 2:** Carousel.  
  **Acceptance Criteria:** Having a changing hero image showing various images.


## Design Decisions

### Wireframes
Colors were specifically chosen to match the image used in the jumbotron to have a calm, warm feeling.

The fonts were picked from [fontpair](https://www.fontpair.co/all) as nice readable fonts and icons where added from [FontAwesome](https://fontawesome.com/).

The Layout is just simple, the information cards directy under the jumbotron is because most people that search for a site would just like to see what they came to that website for and if they wish to learn more the buttons under each of the topics will take them to the relivant place. 
For the navigation bar it's simple however there is a button on the right hand side for people who might be searching for help and this might have been what they stumbled upon first.


![Home Page Wireframe](assets/images/Screenshot%202024-10-22%20113116.png)

![Mobile Wireframe](assets/images/Screenshot%202024-10-22%20122324.png)

### Accessibility Considerations
All the text on the page has been checked using [WebAIM](https://webaim.org/resources/contrastchecker/) to ensure it can be seen correctly
All links have aria labels attributed to them.
All images have their Alt tag set.

## Features Implementation

### Core Features (Must-Haves)
- **Feature 1:** Hero Section: Added a relevant large Hero Title and short positive message.
- **Feature 2:** Used calming warm colors from hero image.

### Advanced Features (Should-Haves)
- **Feature 1:** Added a simple standard navigation bar to move around the side easily.
- **Feature 2:** Made an adaptive layout that will change to suit the device size of the user.

### Optional Features (Could-Haves)
- **Feature 1:** 


## Testing and Validation

### Testing Results
I attempted to start from mobile first and work up screen sizes, with bootstrap it's rather simple as most of the moving is done for you so long as you set the columns correctly. (Foreshadowing)
Most issues I ran into where columns not being defined for particular screen sizes.
I also added media queries to change the size of the text dependant on screen size. 
Summarize the results of testing across different devices and screen sizes.  
I also frequently used the eyedropper tool to test the background color againt the text color for WCAG.

### Validation
I just copied my code into [W3C HTML](https://validator.w3.org/) [W3C CSS](https://jigsaw.w3.org/css-validator/) to check.

### Errors:

### HMTL
Stray end li and i tag. Simply removed from code.
Warning: "Consider using the h1 element as a top-level heading only" Seems to have occured due to the H1 being inside multiple divs and a section.

### CSS

Forgot to add a unit measure to a max-width: 268; just needed to add px to it.

## Deployment

### Deployment Process
Went into the project repository, Settings -> Pages.
Selected main branch and pressed save.

## AI Tools Usage

### Reflection
I mostly used AI for the content of the page as I'm not the best with words I didn't use any for code.

## Reflection on Development Process

### Successes
It writes nice short paragraphs.

### Challenges
Trying to describe what I want from it.

### Final Thoughts
It was just a fun project that I went about focusing on what was asked of me rather than what I thought I could do.
The main goal of this was to stick as closly to what was asked as possible to prevent me from trying to do things I didn't really know how and wasting time before actually getting done what needed to be and I believe I did okay at that.

## Code Attribution
Properly attribute any external code sources used in the project (excluding GitHub Copilot-generated code).  
  [Bootstrap](https://getbootstrap.com/docs/5.3/getting-started/introduction/font): Modal, Navbar, Cards, Buttons, Page Structure
  [FontAwesome](https://fontawesome.com/): Text Icons and social media Icons
  H2s : Post found on [StackOverflow](https://stackoverflow.com/questions/55233092/css-pseudo-element-underline-on-centered-header)
  Jumbotron, Quotes: Based on our [Building with Bootstrap](https://github.com/Code-Institute-Solutions/BootstrappingYourNextBigIdea-BS4/tree/master/04-BeyondBootstrap/03-cleaning_up_our_content)
  Main Header: Inspired from our [Love running project](https://github.com/Code-Institute-Solutions/love-running-v3/tree/main/8.1-testing-and-validation)
**Guidance:** Document any external code sources used throughout the entire project, especially during Phase 2 and Phase 3. Exclude GitHub Copilot-generated code from attribution.

## Future Improvements
Briefly discuss potential future improvements or features that could be added to the project.  
**Guidance:** Reflect on potential enhancements that could be made to the project after Phase 4: Final Testing, Debugging & Deployment. These could be Could user story features you didn’t have time to implement or improvements based on testing feedback.