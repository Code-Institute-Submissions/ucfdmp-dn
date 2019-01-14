# User Centric Frontend Development Milestone Project  

This is a frontend-only website built for a 1960's rockband The Monkees.
 
## UX
 
Use this section to provide insight into your UX process, focusing on who this website is for, what it is that they want to achieve and how your project is the best way to help them achieve these things.

In particular, as part of this section we recommend that you provide a list of User Stories, with the following general structure:
- As a user type, I want to perform an action, so that I can achieve a goal.

This section is also where you would share links to any wireframes, mockups, diagrams etc. that you created as part of the design process. These files should themselves either be included in the project itself (in an separate directory), or just hosted elsewhere online and can be in any format that is viewable inside the browser.


- The Monkees - project [PDF](../dev/the_monkees_project.pdf) with sketches and wieframes included in dev folder.
    - or locate manually in folder ../dev/the_monkees_project.pdf

## Features

- **News page** provides option to show news using bootstrap cards.

- **Listen page** provides option to view embeded youtube videos and listen to spotify albums. Both options redirect to reevant official pages.

- **Band page** provides some description of band itself and it's members.

- **Book event page** provides option to send request to book event with short description and preferred date.

- **Contact page** provides option to send any question using simple form.

In this section, you should go over the different parts of your project, and describe each in a sentence or so.
 
### Existing Features
- Feature 1 - allows users X to achieve Y, by having them fill out Z
- ...

For some/all of your features, you may choose to reference the specific project files that implement them, although this is entirely optional.

In addition, you may also use this section to discuss plans for additional features to be implemented in the future:

## Technologies Used

In this section, you should mention all of the languages, frameworks, libraries, and any other tools that you have used to construct this project. For each, provide its name, a link to its official site and a short sentence of why it was used.

- [HTML](https://w3c.github.io/html/)
    - The project uses **HTML** as core language.

- [CSS](https://www.w3.org/Style/CSS/Overview.en.html)
    - The project uses **CSS** to describe colors, layout, and fonts.

- [JavaScript](https://www.javascript.com/)
    - The project uses **JQuery** as part of **bootstrap** and **gijgo**.

- [Bootstrap](https://getbootstrap.com/)
    - The project uses **Bootstrap** to build responsive web site and utilise it's components.

- [gijgo](https://gijgo.com/)
    - The project uses **gijgo**. Datepicker by Gijgo.com is a plug-in for the jQuery Javascript library. It is a very fast and extandable tool, and will add advanced interaction controls to any date field. This plugin allows you to create datepickers using bootstrap or material design styles. Free open source tool distributed under MIT License.


## Testing

- HTML validated - [Markup Validation Service](https://validator.w3.org/)

- CSS validated - [CSS Validation Service](https://jigsaw.w3.org/css-validator/)

1. Tested on various browsers and devices:
    1. Chrome, Firefox, Edge on windows PC and Tablet;
        1. general resiszing and using developer tools.
        2. tablet rotation
        3. screen resolution from 2560x1440 down to 1280x800
    2. Chrome, Firefox, Safari on MAC
        1. general resiszing and using developer tools
    3. Iphone SE, 6S Plus
        1. Chrome, Safari
    4. Galaxy S3
        1. Built-in android browser, Chrome, Firefox

2. All links where checked manually and using [checker tool](https://www.deadlinkchecker.com/website-dead-link-checker.asp)
    > 100% scanned - 36/36 URLs checked, 36 OK


3. Contact form:
    1. /contact.html
    2. Empty form submission highlights that Name field is required
        1. required warning appears for any field that was left empty on time of submission - Name, email, message
    3. Submitting form with incorrect email format will produce warning message **please include an @ in the email address**
    4. Submitting form with all correct fields produces no error, as there is no post method implemented, page simply refreshes to empty form.

4. Book event form:
    1. /book-event.html
    2. Empty form submission highlights that Name field is required
        1. required warning appears for any field that was left empty on time of submission - Name, email, phonr number, message, date pick
    3. Submitting form with incorrect email format will produce warning message **please include an @ in the email address**
    4. Submitting form with all correct fields produces no error, as there is no post method implemented, page simply refreshes to empty form.

### Bugs / Issues

Font awesome "bars" icon is used instead of bootstrap standard toggler. Standard toggler icon appers only if navbar **.bg-** utility is used. Using **.bg-** overrides bg color defined in css. It was decided to use fontawesome icon instead.

## Deployment

This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub Pages or Heroku).

In particular, you should provide all details of the differences between the deployed version and the development version, if any, including:
- Different values for environment variables (Heroku Config Vars)?
- Different configuration files?
- Separate git branch?

In addition, if it is not obvious, you should also describe how to run your code locally.


## Credits

- Social link icon style taken from - [mdbootstrap](https://mdbootstrap.com/docs/jquery/components/buttons-social/)

- [BootstrapCDN](https://www.bootstrapcdn.com/) and [BootstrapCDN](https://www.bootstrapcdn.com/fontawesome/) for fontawesome

- Examples used for menu toggler:
    - How TO - [Make a Website with Bootstrap 4](https://www.w3schools.com/howto/howto_website_bootstrap4.asp)
    - Bootstrap official [Navbar](https://getbootstrap.com/docs/4.1/components/navbar/) page

- [Hover CSS](https://github.com/IanLunn/Hover) for navigation hover effects:
    - [Preview](http://ianlunn.github.io/Hover/)


- Font awesome [bars](https://fontawesome.com/icons/bars?style=solid) icon used instead of bootstrap standrd toggler: 

- [Color picker](https://htmlcolorcodes.com/color-picker/)

- [Date picker](https://gijgo.com/datepicker/example/bootstrap-4) for Bootstrap 4

### Content

- The text for Band page copied from:
    - [The Monkees biography](https://www.biography.com/people/groups/the-monkees)
    - [Peter Tork Biography](https://www.biography.com/people/peter-tork-20758183)
    - [Michael Nesmith Biography](https://www.biography.com/people/michael-nesmith-20757957)
    - [Micky Dolenz biography](https://www.biography.com/people/micky-dolenz-16730294)
    - [Davy Jones biography](https://www.biography.com/people/davy-jones-377858)
 
- The text for News page copied from [Official Monkeys web page](https://www.monkees.com/news)



### Media
- The photos used in this site were obtained from:
    - [The Monkees](https://www.monkees.com/) official website
    - [Peter Tork Biography](https://www.biography.com/people/peter-tork-20758183)
    - [Michael Nesmith Biography](https://www.biography.com/people/michael-nesmith-20757957)
    - [Micky Dolenz biography](https://www.biography.com/people/micky-dolenz-16730294)
    - [Davy Jones biography](https://www.biography.com/people/davy-jones-377858)
- The Monkees [Youtube](https://www.youtube.com/channel/UCv1oY0OLtsEySHeP1TkYNqA) channel used to embed videos
- The Monkees [Spotify](https://open.spotify.com/artist/320EPCSEezHt1rtbfwH6Ck) used to embed albums
  

### Acknowledgements

- I received inspiration for this project from:
    - https://getbootstrap.com/docs/4.2/examples/album/
    - https://getbootstrap.com/docs/4.2/examples/pricing/
