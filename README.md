# Milestone Project 1 - N-skala Väst / N-scale West

## Introduction to project

N-scale West is an organization, not formally founded or with statues, that are interested in different aspects of model railroading, mainly in n-scale (1:160). Many members build modules to bring to meetings. Meetings can have different themes, like public display, internal meetings, traffic simulation or emphasis social aspects. 
<br><br>
As an organization, N-scale West have not participated in any public shows since the outbreak of covid, but late march 2025 they will be attending a hobby show during two days. They see this as an opportunity to both entertain the visitors and attract new people interested in the hobby. The previous webpage was old and the domain has expired, but for this meeting they want a new and inspiring homepage, both for people visiting the hobby show and want more information as well as attract those that make online searches about related topics.


## Goals

**Primary:** Attract people interested in the model railroad hobby to become active within the module community. The ultimate goal would be to have more modules to bring to meetings and shows.
<br>

**Secondary:**  Inspire people to make them more interested in model railroading in general and modules in particular. Helping newcomers to the hobby to sites with more detailed information, or other organizations that might be better suited depending on specific interests, for the greater good of the hobby.

## Overview of users and needs

### Who will be using it?
People who get in contact with N-scale West on hobby shows, and people who make online searches about relevant topics. Visitors will most likely already possess some interest in trains, model railroads, models in general, diorama, rail traffic or similar subjects.

### What do the primary users need from the website?
A way to get in contact with N-skala Väst and sign up for more information, first to familiarize themselves with the group but in long term participate in the hobby. The website should be responsive and user friendly, without to many technical and constructional detail that scare people away.

## Specified User stories
User stories are ranked in order of priority, and marked according to must- should- and could-have practice. Github Project was used to keep track of tasks during development. The status of the tasks in this ReadMe is consistent with Github Project at the time of project submission.

### User story, Responsiveness and accessibility
As a visitor, the site needs to be responsive and easy to navigate regardless of if I use a phone, tablet or computer.  
Priority: must-have
#### Acceptance criteria
- [X] The website needs to be responsive to make it easily accessible on several different platforms
- [X] Navigation must be easy
#### Tasks
- [X] Build a responsive website using Bootstrap Grid
- [X] Add intuitive navigation, to make all important information easily accessible regardless of where the user is on the site.

### User story, contact information
As a visitor just getting in contact with N-skala Väst, I would like a way to get in contact with the organization to learn more and attend activities.  
Priority: must-have
#### Acceptance criteria
- [X] Find a way to easily get in contact with N-skala Väst for questions, or join the group for activities
#### Tasks
- [X] Provide contact form to get in touch N-skala Väst

### User story, find additional resources
As a visitor for the first time coming into contact with N-skala Väst or modules, I would like to find inspirational pictures and information about how to get started, either with resources on the site or links to appropriate pages  
Priority: must-have
#### Acceptance criteria
- [X] Inspirational content that makes me want to learn more
- [X] Links or resources that will help me get started if I decide to build my own module
#### Tasks
- [X] Add pictures and/or videos showing module meets, building, trains running and landscaped scenes etc
- [X] Provide links to other resources that can be helpful for both newcomers and more experienced module builders.

### User story, social media
As an organization, N-skala Väst want links to their social media platforms to encourage visitors to see more of our work.  
Priority: should-have
#### Acceptance criteria
- [X] Links to social media (currently Facebook and Youtube) should be added to footer/other convenient place and social media material should be integrated in other parts of the site
#### Tasks
- [X] Provide links to social media at footer/other convenient place
- [X] Provide links or embedded social media content as a integrated part of the site

### User story, additional pictures
Aside from pictures (or other media) illustrating the different sections, N-skala Väst would like to present a pcitures showing modules and activites. This expands on the content needed to complete the user story *find additional resources*.  
Priority: should-have
### Acceptance criteria
- [X] Provide pictures showing modules and model railroading

### Tasks
- [X] Construct a photo gallery or image carousel for additional pictures

### User story, membership area part 1
N-skala Väst would like a private part of the site for internal purposes, like presentation of members and their contact information. At first this information can be static and updated by the webmaster since it is a fairly small community  
Priority: could-have
#### Acceptance criteria
- [ ] Being able to log in and see contact information to members
#### Tasks
- [ ] Provide login to membership area and supply a list of members (name, phone, email), updated by webmaster

### User story, membership area part 2
As an organization, N-skala Väst would like to let members log in and update their own information, upload pictures, provide links to their own pages/media etc.  
Priority: could-have
#### Acceptance criteria
- [ ] Let users update their own information
#### Task
- [ ] Build update forms in the membership area for users to create/update/delete information about themselves.

## Discussion of user stories
Since this website will be used by the real-life organisation N-skala Väst there have been discussions among the members. At the moment, although we had the user story Membership area part 1 implemented on a previous site, the organisation now leans towards a closed Facebook group for discussions. Until a desicion has been made, the could-have user stories will not be implemented regardles of time available.

## Basic design of website and page requirements
From the user stories, and for technical requirements, five pages was constructed:
- index.html, index page with three different sections, each section being a preview for the following three pages
- modules.html, describing advantages of building model railroad modules and participating in groups / meetings
- resources.htm, a link library for those who want to read more or be inspired. The link library should contain the following headlines, with at least three items each:
    - specifications for module standards
    - guide to construction, both frame construction and scenery
    - inspirational videos and articles
- contact.html, a brief introduction to N-skala Väst as well as a contact form. For the scope of this project, the form will have validation of required fiels and email type validation, but it will will not be an acutal working contact form.
- success.html, to display a simple confirm message after filling out the contact form

**Note:** Since it outside the scope of MileStone Project 1, the contact page does not feature a working contact form. This will be adjusted after submission of the project but before the web page goes live.

### Alternative outlines considered or tried
- Instead of success-html, experiments were made with a modal message within contact.html to inform that the message had been sent. However, the modal message was triggered before the form submit-event, leading to the success message being shown regardless of the form validation outcome. Therefore, success.html was added as an functional alternative.  

- After completing all must-have stories, attention was turned to the social media and additional picture features. Social media was integrated from the beginning in the wireframes, but designing picture gallery/carousel wasn't done until late in the project. It was decided to integrate this feature last into modules.html as a picture carousel, rather than construct a separate page. The thought was that after reading about different aspects of module railroading the visitor would have a greater understanding of what might be going on in the pictures, or how they fit together. Also, there was no need to adjust the navbar and copy that to existing pages, with the extra testing and validation that would need to follow.

## Wireframes
Wireframes were constructed for the four main pages (not sucess.html). Though lacking in styling they gave a clear view of how menu and content could be displayed at different screen sizes.
<br>
**Design summary:** 
- On phones the menu is collapsable, and all content is listed in a column, pictures first and text afterwards.
- On tablets (768 pixels or wider) there is room for the entire menu in the header. 
- On computer screens (992 pixels or wider) screens are wide enough to display images and text content next to each other.

### index.html
Basic outline of index.html for phones, tablets and computers  
![Wireframe for index.html, on phone.](/assets/project/wireframes/index_phone_v1.png)
![Wireframe for index.html, on tablet.](/assets/project/wireframes/index_tablet_v1.png)
![Wireframe for index.html, on computer.](/assets/project/wireframes/index_computer_v1.png)
<br><br>
After initial testing and watching the home page being developed, it was clear that there was a headline missing for the different sections. A read-more button was added to take visitor to other pages. Also, the text displayed in the menus was changed to shorter versions without affecting the actual content behind the links. These changes were not deemed large enough to make new Wireframes.

### modules.html
Basic outline of modules.html for phones, tablets and computers  
![Wireframe for modules.html, on phone.](/assets/project/wireframes/modules_phone_v1.png)
![Wireframe for modules.html, on tablet.](/assets/project/wireframes/modules_tablet_v1.png)
![Wireframe for modules.html, on computer.](/assets/project/wireframes/modules_computer_v1.png)
<br><br>
Since this page is very similar to the index page, the only adjustment made at the time of design were omitting an introductionary paragraph under the first headline. As with index.html, this page also got a small headline above each picture (or picture/text if displayed next to each other).  
Later adding a picture carousel last at the page didn't add sufficient to the design to warrant a new Wireframe. It was placed in the already existing grid outline.

### resources.html
Basic outline of resources.html for phones, tablets and computers  
![Wireframe for resources.html, on phone.](/assets/project/wireframes/resources_phone_v1.png)
![Wireframe for resources.html, on tablet.](/assets/project/wireframes/resources_tablet_v1.png)
![Wireframe for resources.html, on computer.](/assets/project/wireframes/resources_computer_v1.png)
<br><br>
A decision to use Bootstrap Accordion for the different link sections was made early. Not shown in the wireframes, the idea was to use tables for the different sections to display links and descriptions about pages refered to. However, it turned out quickly that the tables wasn't responsive enough and the tables were replaced with Bootstrap Grid/Columns instead. Since the wireframes wasn't detailed enough to show the tables, no new versions were produced. This is also documented in the Testing section.

### contact.html
Basic outline of contact.html for phones, tablets and computers<br>
![Wireframe for contact.html, on phone.](/assets/project/wireframes/contact_phone_v1.png)
![Wireframe for contact.html, on tablet.](/assets/project/wireframes/contact_tablet_v1.png)
![Wireframe for contact.html, on computer.](/assets/project/wireframes/contact_computer_v1.png)
<br><br>
No major changes were made to the about us / contact us section

## Colors and fonts
### Colors
[Coolors.co](https://www.coolors.co) was used to find suitable colors. The first color chosen was the Barn red since it reminded of older Swedish enginges and passenger cars. The rest of the colors were chosen to match and provide pleasing tones.  
Color Copper was chosen to fill the main area of the pages, with rounded elements containing the main content being color Vanilla. The idea was to be looking in through windows at the different content section, an effect enhanced with the Boxshadow effect suggested by mentor Spencer Barriball.  
Most text is plain black while headlines have a slightly lighter color called Bistree. Bistree is also used for buttons and the footer.
The chosen colors called for some changes in other colors to increase contrast (see testing). In the Bootstrap navbar White or Near-white was used. In the accordion used in modules.html, white and bistree was used to override Bootstrap defaults.

### Fonts
Fonts were choosen from Google Fonts. A simple sans-serif called Montserrat was choosen as the primary font, with standard sans-serif if Montserrat fail to load. Fraunces was chosen for headlines, with a cursive font being used if font is unable to load.

## Deployment
Deployment to Github was done early, and frequent commit and updates have been made. Commit history and changes are stored in Github repository. The project is available at  
https://github.com/Daniel-R-ci/msp1/tree/main

## Testing
The following testing methods were used frequently after major additions or changes, both locally and after deployment.

- Manual testing
    - Testing all links in navbar, content and footer on all pages
    - Observing responsiveness change, both using Chrome Developers tool and manually adjusting window size
    - Testing responsiveness of deployed page on mobile phone, tablet and another computer using Microsoft Edge
- HTML validation, at https://validator.w3.org/
- CSS autoprefixer, at https://autoprefixer.github.io/
- CSS validation, at https://jigsaw.w3.org/css-validator/
- WAVE web accessibility evaluation tool, at https://wave.webaim.org/
- Lightroom evaluations in Google Chrome

## Bugs, validation and testing errors

### Resolved issues

- [X] **HTML validation error:** (read more-buttons in index.html)  
Incorrectly used button within a-elements instead of making a-element a button
- [X] **HTML validation error:** (embedded youtube-iframe in modules.html)  
Attribute *frameborder* was marked as obsolete. Attribute could be removed without affecting design or performance. W3 Validator says to use CSS styling instead if needed.
- [X] **HTML validation error:** (accordion in resources.html)  
Wrong id in one accordion-body. Not changed from Bootstrap example when customized. Other accordion-body functioned as they should.
- [X] **Lightroom SEO score:** (all pages)  
Added meta keywords and description to all pages 
- [X] **Wave:** (all pages)  
Adjusted navbar colors for better contrast
- [X] **Wave:** (contact.html)
Adjusted link colors in contact.html for better contrast and added labels to form
- [X] **Manual testing:** (resources.thml)
Resources page was first constructed with tables within the accordion-items. This didn't give very good responsivness and was replaced with Bootstrap Grid Columns.
- [X] **Manual testing:** (contact.html)  
Modal window triggered by submit-button was activated before input field validation. I was unable to work around this so the modal window was dropped and replaced with the new page success.html to show a confirmation of a sent field
- [X] **Manual testing:** (modules.html)  
Gallery carousel in modules.html didn't function as intended. After an hour of troubleshooting and googling I contacted student tutoring. Rebecka at Code Institute spotten an older method used, probably an older version of Bootstrap Carousel had been used by accident. After copying a code example from 5.3.3 everything worked and customization could begin.

### Remaining issues

- [ ] **Lightroom SEO score:** (modules.html)  
The page gets a SEO score of 91%. This can be brought up to 100% by adding text to the three Read more-buttons. Lightroom wants to see some descriptive texts on those buttons. However, that detracts from the simple visual styling of the buttons. In tests the buttons doesn't seem as good looking when text is added to them, therefore, it is a trade-off willing to be made. From a contextual point, the it is very clear to what section the buttons belong to, and Aria-labels are in place.

- [ ] **Lightroom SEO score:** (modules.html)
The page get a Best Practice score of 78%. This is due to 3rd party cookies and issues coming from the embedded Youtube player. The embedded code is coming from Youtube and is not being able to handle here, short of removing the embedded material. It should be noted, that when performing the test in Incognito mode the score rises to 100%.
<br><br>
No other *known* bugs or issues remaining...
## Credits

- [Fontawesome](https://www.fontawesome.com), for Icons
- [Bootstrap](https://getbootstrap.com/), for a lot things like (but not limited to) Navigation Bar, Column Grid Accordion, Button and Form styling and functionality
- [Google Fonts](https://fonts.google.com/), for fonts used
- [Coolors.co](https://coolors.co/), for helping with matching color palette
- [Footor.com](https://www.fotor.com/), for picture editing
- [Tinypng.com](https://tinypng.com/), for reducing size of images
- Spencer Barriball, mentor, for support, usefull links and important guidance
- Code Institute Tutoring (Rebecca Tracey-Timoney) for help with Bootstrap Carousel not working
- Jere Huttinen, fellow Code Institute Student, for sharing how he aligned navbar text
- Members of N-skala Väst for discussions about the requirements of the new website providing help with images
- All pictures used with approval of the photographer and with the consent of the people shown in the pictures

