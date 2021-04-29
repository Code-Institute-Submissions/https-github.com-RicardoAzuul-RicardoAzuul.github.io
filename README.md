# Roleplay Cafe

This project is for a static website for a non-existing cafe: the Roleplay Cafe.
The Roleplay Cafe specializes in providing a venue and resources for roleplaying enthousiasts. 

As such, the site needs to meet the needs of both visitors and owners:
- new visitors need to be able to quickly learn about the Roleplay Cafe.
- returning visitors need to quickly find relevant information, for instance about events.
- the owners want to convert new visitors into recurring visitors and have recurring visitors return to the cafe.

To visit the site, click [https://ricardoazuul.github.io](https://ricardoazuul.github.io/)

---

## Table of Contents
1. [UI and UX](#ui-and-ux)
    1. [The 5 Planes of Design](#the-5-planes-of-design)
        1. [Strategy Plane](#strategy-plane)
        2. [Scope Plane](#scope-plane)
        3. [Structure Plane](#structure-plane)
        4. [Skeleton Plane](#skeleton-plane)
        5. [Surface Plane](#surface-plane)
1. [Features](#Features)
    1. [Existing Features](#existing-features)
    1. [Features Left To Implement](#features-left-to-implement)
1. [Technologies Used](#technologies-used)
1. [Responsiveness of Pages](#responsiveness-of-pages)
1. [Testing](#Testing)
1. [Deployment](#Deployment)
1. [Credits](#Credits)
    1. [Content](#Content)
    2. [Media](#Media)
    3. [Acknowledgements](#Acknowledgements)

---

## UI and UX
 
 User stories:
- As a potential customer of the cafe, I want to visit the site and quickly determine if the cafe is suitable for me, so I can decide to visit. I will look at location, opening times and the menu. Some photos to give a sense of the ambience would be nice too.
- As a recurring customer of the cafe, I want to visit the site to see what events are on and when, so I can decide which events to go to. I want to see when these events are planned, if they recur, and a brief description of these events.
- As a potential customer of the cafe who wants to be a game master for a roleplaying game, I want to visit the site to see what resources the cafe provides for hosting my game, so I can decide to host my game at the cafe. I want to have an overview of the resources provided - dice, character sheets, a sound system, perhaps a booth? - any possible costs associated with them and when the resources are available.
- As a potential customer of the cafe who wants to be a player in a roleplaying game, I want to visit the site to see if there are any games for me to join, so I can decide to go to the cafe.
- As a potential customer of the cafe who is new to roleplaying games, I want to visit the site to see what the cafe offers to help me learn about this hobby, so I can decide to go to the cafe.

---

### The 5 Planes of Design

I've used Jesse James Garret's 5 planes of UX design to design the site. I started off at the Strategy Plane.

#### Strategy Plane

For the owners of the Roleplay Cafe, the site needs to achieve the following:
- inform site visitors what the Roleplay Cafe offers.
- turn visitors to the site into visitors of the cafe, and ideally recurring visitors too.

The value of the site for the owners: the number of visitors to the Cafe increases, website visitors register their games and more games are being offered by the Cafe, building a tribe of like-minded visitors.

For the visitors, the site needs to achieve the following:
- allow them to quickly figure out what the Roleplay Cafe offers.
- find out about roleplaying games they can join.
- submit a game they want to run as game master.
- find out about events.

The value of the site for site visitors: quickly learn about a cool new cafe in town and get to meet people with similar interests.

The owners of the Roleplay Cafe want to have a website designed in order to reach more potential customers and to keep their customers.

The goals of the website are thus:
- inform potential customers of what the Roleplay Cafe has on offer.
- inform returning customers of what the Roleplay Cafe has on offer.

The users I am focusing on:
- players of roleplaying games who are looking for a place to socialize with others like them, try out new roleplaying games, find new groups to play with.
- gamemasters of roleplaying games, who are looking for a place to host their games and find new players.
- people who are interested in roleplaying games, but have little to no experience and are looking to learn more.

The tasks that I will help users solve:
- find the basic details of the Roleplay Cafe: opening times, location, an idea of the menu, social media.
- find events that are hosted at the Roleplay Cafe.
- for the gamemasters: submit their game idea, so the Roleplay Cafe can add it to the regular games.
- for the gamemasters: find out the resources the Roleplay Cafe has on offer, and if necessary reserve them.
- for people curious about roleplaying games: discover what the Roleplay Cafe and roleplaying is about, using photos of the Roleplay Cafe and perhaps some videos about roleplaying games.

Why will users use this solution:
- it's the easiest way to find out what the Roleplay Cafe is about and what is on offer. Walking in might be confusing, and you would have to find the Roleplay Cafe first.

---

#### Scope Plane

The functional specifications of the site:
- A responsive website, mobile first design - for users on the move or who happen to find themselves near or in the Cafe - with at least the following content:
    - a Home section to give a quick overview of the Roleplay Cafe: menu, photos, opening times, location.
    - a section for players to give an overview of games and events on offer.
    - a section for gamemasters to give an overview of the resources on offer and a form to submit their game idea.
    - a section for newbies, that tries to quickly explain what roleplaying and the Roleplay Cafe is about.
    - a section for the drinks and food menu.
    - a section with instructions how to get to the Roleplay cafe.
    - a section with a brief history of the Roleplay Cafe and its owners, the About page.
    - the Home page has a Jumbotron featuring the next event.
    - the players' page has a Jumbotron featuring the next event.
    - the gamemasters'  page has a Jumbotron featuring new resources on offer.
    - the newbies' page has a Jumbotron featuring the next event for beginners.

Content requirements:
- Photos of the Roleplay Cafe and its facilities.
- A list of events.
- A list of resources for gamemasters. 
- Inspirational images and texts to entice users to come visit.
- A short text about roleplaying and the Roleplay Cafe to entice new visitors.    

---

#### Structure Plane
All pages should have the same navigation bar and footer:
- the navigation bar contains links to all the pages, as well as the home page.
- the footer contains the Roleplay Cafe's address and social links.

Initially I was going to have separate pages for the information for players, gamemasters and newbies, but I've decided to combine those into one page, using tab navigation to switch between the sections.

<ins>The Home Page</ins>
- a hero image to inspire visitors of the site to visit the Cafe.
- a short text about the Roleplay Cafe.
- the next upcoming event, and a link to the agenda.
- more photos of the Cafe/roleplaying.
- a short text about the menu, and a link to it.
- a form to sign up for the newsletter.

<ins>Why Visit Us</ins>
- more in-depth information for players of roleplaying games why they should visit.
- a list of events.
- more in-depth information for gamemasters why they should visit.
- a form for gamemasters to submit their game idea.
- more in-depth information for newbies why they should visit.

<ins>Menu</ins>
- photos of food and drinks.
- an overview of the food and drink menu.

<ins>Directions</ins>
- a text on how to get get to the Roleplay Cafe.
- a link that opens a well-known website for planning your public transport route.
- an embedded Google Maps map indicating the location.

<ins>About</ins>
- a brief history of the Roleplay Cafe and why it was opened.
- a brief history of the owners.

---

#### Skeleton Plane

Website visitors have come to expect certain layouts from websites. As such, I will add a navigation bar to the top of every page, that will always remain visible, even when scrolling down. This navigation bar contains links to all the different pages. 
On the left will be the logo, which when clicked upon will take the user back to the home page.

The active page is indicated with a line under the navigation item. When hovering over navigation items, a blue line will appear under the navigation item.

At the bottom of every page will be the same footer, with the following information: opening hours, contact details, links to the Roleplay Cafe's social media accounts (in this case links to the home pages of said social media sites) and a form to sign up for a newsletter.

Text will also go from top to bottom, with images between pieces of text to break it up and add variation. Only on the menu page will the food and drinks menu appear next to each other, but only on the larger breakpoints.

On smaller breakpoints the flow of text will be the same, but with less white space on left and right. Images, embedded Youtube videos and the embedded Google Maps map will disappear on smartphone screens, to save space.

---

#### Surface Plane

For the color palette I wanted something that makes one think of an old bar or cafe, but with a little bit of magic injected. I found concept art of a bar in the Dungeons & Dragons world of Eberron, which had both: lots of dark browns, but also magical colours. I used [this image](https://www.artstation.com/artwork/nQXmye).

I used EyeDropper to create these palettes:

#542C23
#6B382D
#EB7B63
#F78268
#D16E58

And for contrast:

#FFFE97
#858319
#EBD68A
#C7D5ED
#5A94B8

In the end, I only used a few colours though: #542c23 as the background colour for the nav bar and the footer, and borders around images, and #5A94B8 to color buttons, for the line under hovered over nav items and as the color for the social media icons. For white text and the main background I went for #fefefe as an off-white color.

The icons are sourced from Font Awesome, as icons to link to various social media channels.
Fonts are sourced from Google Fonts. I decided on New Tegomin: I felt it simulated an old type-writer, and the cozy antique feeling it evoked fits with the concept of the Cafe. The Montserrat offset that by being clean and modern. New Tegomin is used for H1 headers, the logo and for the titles in the footer, while everything else is Montserrat.

<ins>Wireframes</ins>

- [Home](/assets/readme-assets/Home.png)
- [Home tablet version](/assets/readme-assets/Home_tablet.png)
- [Home Mobile Version](/assets/readme-assets/Home_mobile_view.png)
- [Why Visit Us Players](/assets/readme-assets/Why_Visit_Us_Players.png)
- [Why Visit Us Players tablet](/assets/readme-assets/Why_Visit_Us_Players_tablet.png)
- [Why Visit Us Players Mobile Version](assets/readme-assets/Why_Visit_Us_Players_mobile_view.png)
- [Why Visit Us Gamemasters](/assets/readme-assets/Why_Visit_Us_Gamemasters.png)
- [Why Visit Us Gamemasters tablet](/assets/readme-assets/Why_Visit_Us_Gamemasters_tablet.png)
- [Why Visit Us Gamemasters Mobile Version](assets/readme-assets/Why_Visit_Us_Gamemasters_mobile_view.png)
- [Why Visit Us Newbies](/assets/readme-assets/Why_Visit_Us_Newbies.png)
- [Why Visit Us Newbies tablet](/assets/readme-assets/Why_Visit_Us_Newbies_tablet.png)
- [Why Visit Us Newbies Mobile Version](assets/readme-assets/Why_Visit_Us_Newbies_mobile_view.png)
- [Menu](/assets/readme-assets/Menu.png)
- [Menu](/assets/readme-assets/Menu_tablet.png)
- [Menu Mobile Version](/assets/readme-assets/Menu_mobile_view.png)
- [Directions](/assets/readme-assets/Directions.png)
- [Directions tablet](/assets/readme-assets/Directions_tablet.png)
- [Directions Mobile Version](/assets/readme-assets/Directions_mobile_view.png)
- [About](/assets/readme-assets/About.png)
- [About Mobile Version](/assets/readme-assets/About.png)

---

## Features

### Existing Features
- Navigation bar: contains links to all the pages and allows users to browse to pages.
- Footer: contains practical information about the Cafe: opening hours, contact details, social media icons, and a newsletter form.
- Home page: has an enticing background image of a cafe bar, a short text about the Cafe, evocative images about roleplaying, food and drinks, buttons that take you to either the upcoming events or the food and drink menu, and short texts about the next upcoming event and food and drinks.
- Why Visit Us page: has tabbed navigation to allow switching between the section for players, the section for gamemasters and the section for newbies.
- The Players section: has text about why you should visit the Cafe if you're a player, an evocative image, and a list of upcoming events.
- The Gamemasters section: has text about why you should visit the Cafe if you're a gamemaster, an evocative image, a list of resources, and a form to submit your game.
- The Newbies section: has text about why you should visit the Cafe if you're new to roleplaying, an evocative image (only on small screens) and links to two Youtube videos meant to encourage roleplaying.
- The Menu page: has a food and drinks menu, and images to go with them.
- The Directions page: has an embedded Google Maps map (only show up on breakpoints md and larger) and texts on how to get to the Cafe by car or public transport.

---

### Features Left to Implement

As I was working on the project, I realized that I was too ambitious. The project requirements specify a minimum of 3 pages, but I have 5 pages. This, coupled with the difficulty of finding suitable free stock images to use, meant that I didn't have the time or resources to implement these features:
- A Jumbotron on the main page, to highlight the next upcoming event
- A photo gallery or carousel, to add more images and thus variation to the pages. This could go on the Menu page
- Calls to action, such as:
    - for players a call to action: perhaps a weekly tournament?
    - for game masters: sign your game up and win
    - for newbies: join this weekly newbie friendly game.

---

## Technologies Used

- [HTML5](https://en.wikipedia.org/wiki/HTML5): provides the content and structure of the site.
- [CSS3](https://en.wikipedia.org/wiki/CSS3): provides the formatting, layout and styling of the site.
- [Visual Studio Code](https://code.visualstudio.com/): a free IDE with enough features to be useful but not so many features as to confuse you.
- [Live Server](https://ritwickdey.github.io/vscode-live-server/): a Visual Studio Code extension that allows you to run your site on your local machine, for quick debugging, testing and developing.
- [GitHub](https://github.com): for hosting the git repository and providing the GitHub pages static site hosting functionality.
- [git](https://git-scm.com/): as one of the most popular source code management tools.
- [Balsamiq](https://balsamiq.com): for creating wireframes of all the pages.
- [Chrome Developer Tools](https://developer.chrome.com/docs/devtools/): for quick debugging and testing of HTML and CSS. 
- [Hover.css](https://ianlunn.github.io/Hover/#effects): to add hover effect to nav links and buttons.
- [Placeholder.com](https://placeholder.com/): to add placeholder images that help with the layout of the pages.
- [WAVE - web accessibility evalution tool](https://wave.webaim.org/): to check the accessibility of the pages.
- [Accessible Color Generator](https://learnui.design/tools/accessible-color-generator.html): to generate colors that contrast better.
- [Am I Responsive?](http://ami.responsivedesign.is/): to generate screenshots of the site at various viewpoints, indicating responsiveness.

---

## Responsiveness of Pages

These screenshots indicate the responsiveness of the pages on various screens.

- [Index.html](/assets/readme-assets/home_responsive.png)
- [Visit.html](/assets/readme-assets/visit_responsive.png)
- [Menu.html](/assets/readme-assets/menu_responsive.png)
- [Directions.html](/assets/readme-assets/directions_responsive.png)

---

## Testing
Test for Readme.md:

:heavy_check_mark: When you click on the links in the TOC, you navigate to the section you clicked on.


Code validation:
[HTML validation](https://validator.w3.org/nu/)
:heavy_check_mark: index.html: the validator indicated a warning: section lacks heading. Changed section to div. Validated again without issue.
:heavy_check_mark: visit.html: the validator 7 errors and 1 warning. Made changes to the HTML. Validated again without issue.
:heavy_check_mark: menu.html: validation without issue.
:heavy_check_mark:  directions.html: the validator indicated a stray end tag div. Validated again without issue.

[CSS validation](https://jigsaw.w3.org/css-validator/)
The validator found 4 errors and 755 warnings. A lot of warnings for Bootstrap: unknown vendor extension.

Navigation Links in the nav bar:
:heavy_check_mark: When you click on the Roleplay Cafe logo, you go back to the Home page and the Home page is marked active.
:heavy_check_mark: When you click on Home, you go back to the Home page and the Home page is marked active.
:heavy_check_mark: When you click on Why Visit Us, you go to the Why Visit Us page the Why Visit Us page is marked active.
:heavy_check_mark: When you click on Menu, you go to the Menu page and the Menu page is marked active.
:heavy_check_mark: When you click on Directions, you go to the Directions page the Directions page is marked active.
:heavy_check_mark: When you click on About, you go to the About page and the About page is marked active.

:heavy_check_mark: Hovering over navigation items in the nav bar should show a blue line under the nav item.

Buttons
:heavy_check_mark: When you click on the "Check our agenda" button, you go to the Why Visit Us page, to the section with the list of events.
:heavy_check_mark: When you click on the "Check our menu" button, you go to the Menu page.
:heavy_check_mark: Hovering over the "Check our agenda" button should show a page curl in the bottom right corner.
:heavy_check_mark: Hovering over the "Check our menu" button should show a page curl in the bottom right corner.
:heavy_check_mark: Hovering over "Submit" buttons should change the buttons color to #fefefe.

:heavy_check_mark: When you click on the phone number in the footer, it opens a phone application.
:heavy_check_mark: When you hover over the phone number, a line appears under it.
:heavy_check_mark: When you click on the email address in the footer, it opens an email application.
:heavy_check_mark: When yhou hover over the email address, a line appears under it.

Social Media Links in the footer:
For each link (icon):
1. Click on the icon.
1. See if it opens in a new tab and goes to the expected page (the respective social media's home page)
:heavy_check_mark: Facebook
:heavy_check_mark: Twitter
:heavy_check_mark: Instagram
:heavy_check_mark: Discord

:heavy_check_mark: When you hover over a Social Media icon, the colors invert.

Newsletter signup in the footer:
:heavy_check_mark: Signup for the newsletter without filling in an email address. This gives a popup that an email address is required.
:heavy_check_mark: Signup for the newsletter after filling in an incorrect email address. This gives a popup that the email address is incorrect. 
:heavy_check_mark: Signup for the newsletter after filling in a correct email address. This reloads the page: expected behaviour, as there is no server that the data is POST-ed to. 

The "Why Visit Us?" page:
:heavy_check_mark: When you hover over the nav tabs, borders appear around it.
:heavy_check_mark: When you click on a nav tab, the correct content is shown.

Submit your game form on the "Why Visit Us?" page:
:heavy_check_mark: Submitting the form without filling in the game description should prompt that the game description is required.
:heavy_check_mark: Submitting the form without filling in the email address should prompt that an email address is required.
:heavy_check_mark: Submitting the form with an incomplete email address should indicate that the email addres is not correct.
:heavy_check_mark: Submitting the filled in form should reload the page, as the submit button has not been linked up to anything.

The YouTube videos in the Gamemasters tab on the "Why Visit Us?" page:
:heavy_check_mark: When you click the Youtube start button, the video starts playing.

The "Directions" page
:heavy_check_mark: When you click on the link to the GVB website, the website opens in a new tab.

---

## Deployment

This site is deployed to Github Pages. If you want to deploy it yourself:
1. On GitHub, navigate to the [RicardoAzuul/RicardoAzuul.github.io repository](https://github.com/RicardoAzuul/RicardoAzuul.github.io)
2. In the top-right corner of the page, click Fork.
3. GitHub will fork the repository with the same name under your GitHub profile.
4. Rename the repository on your own Github profile, with a specific name: %YourGitHubUserName%.github.io.
5. Go to the Settings of this repository.
6. Scroll all the way down, to right above the Danger Zone.
7. Here you can set the repository up to serve as the source for your GitHub Pages. In order to do so, choose a theme.
8. Choosing a theme will apply one of several themes available. This add a _config.yml file to the repository.
9. After the theme has been applied, simply delete _config.yml from the repository to delete the theme and you'll have a GitHub Pages of Roleplay Cafe just like mine!

### Run locally

1. If you want to run the project locally, simply clone the repository: git clone https://github.com/RicardoAzuul/RicardoAzuul.github.io.git
2. Using Visual Studio Code, search for the [Live Server](https://ritwickdey.github.io/vscode-live-server/) extension by Ritwick Dey and install it.
3. Press F1 in Visual Studio Code and in the search bar that pops up look for Live Server and start it.
4. This will start a browser on your own machine hosting the website locally. 

---

## Credits

### Inspiration
I used the following website for inspiration:
- https://ranked.bar/

### Content
All text content is written by myself.

### Media
I sourced almost all images from [Unsplash](https://unsplash.com), except for one which I source from [Pexels](https://www.pexels.com)

### Acknowledgements

- My wife Elizabeth Lane gave me the idea for this project. She knows I'm enthousiastic about roleplaying games, and she suggested creating this site as a suggestion for my first Milestone Project for Code Institute's Diploma in Software Development.
- I also received help and support from my mentor at Code Institute, [Jack Wachira](https://github.com/iamjackwachira). Using the tabbed navigation on the visit.html page was his suggestion for instance.
- I would also like to thank to all the people at [Code Institute](https://codeinstitute.net/) for providing the Diploma in Software Development course and giving me the tools and guidance to create this site.