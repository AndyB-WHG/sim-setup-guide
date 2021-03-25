# Sim Setup World

Project - User Centric Frontend Development - Code Institute

Most modern racing games allow users to change almost every aspect of a car's setup.  Whether this be simple adjustments to fuel levels or tyre type, or more complex changes such as suspension stiffness and differential lock. The number of options available 
can be both bewildering and overwhelming, with in-game explanations often unclear or unhelpful. 

This project aims to act as an educational 'hub', to pull together a variety of excellent YouTube resources to give sim racers the knowledge and confidence to make positive improvements to their sim racing car setups.  

## Showcase

A deployed link to the website can be found here.

![Site Preview](/assets/img/site-preview.png)

## UX
 
This website initially aims to fulfil three needs:

* Act as a setup 'knowledge hub' to provide users with a comprehensive source of setup information.
* Provide an easily understandable process for users/racers to follow in order to improve lap times, car handling, consistency, race-ability and competitiveness.
* Provide multiple 'lessons' for each component, from a variety of experts, to allow for differing learning styles and preferences and to give a variety of viewpoints to improve understanding.  

The site therefore acts as an organising database to pull together knowledge and information from various sources to give the user access to a large volume of information in an easily digestible and logical format.

### User Stories

The end users of the project are sim racers looking to understand all, some or just a single adjustable component within a virtual racing car.  

* As a user I want to learn how to improve my laptimes.
* As a user I would like a process to methodically set up every aspect of my car for a given track in given conditions.
* As a user I want to understand how to make my car more stable and manageable for longer races.

    In the instances above the user will click on the 'Full Setup Guide' option from the Home Page. The user is presented with five mentors - each mentor having a series of videos devoted to the various components found on a racing car.  The user will start at video 1, and work their way through the series in a logical order to methodically build up their knowledge and setup their car.

* As a user I want to understand what each car/setup component does.
* As a user I want to know how changing a component will alter the drving characteristics of my car.

    In these final two instances the user will choose the 'Component Guide' from the Home Page.  An array of car components appears from which the user selects the component they want to learn about. A list of videos appears on screen from the various Mentors for the user choose from.

### Strategy

Guide the user to the relevant video series in no more than two clicks.

Home page, Full Guides page, Component Chooser page, plus pages for each of the components.

### Scope

Five setup guides initially, each with a video series of it's own.  
13 car components - within which the relevent videos for that component are listed together.

### Structure

1. 1 x Home Page:  has two main choices/links:

* Full Setup Guides
* Component Guides

2. 1 x Full Setup Guide Page:  has 5 setup guides to choose from, each created by a different expert.  

3. 5 x Setup Guide Pages

3. Component Selector Page:  has 13 component links to choose from.  Each link leads to a separate page for each component.

4. Components Pages x 13:  each component has a page of it's own, within which the video links for that component are listed.

### Skeleton

The choices on each page will be listed vertically for mobile devices. The user will scroll down to select the relevant option.

For larger devices, the options will be displayed in a grid pattern for quicker selection 

#### Wireframes

[Wireframes link - click to view](https://github.com/AndyB-WHG/sim-setup-guide/blob/master/wireframes-sim-setup-world.pdf)

## Features

In this section, you should go over the different parts of your project, and describe each in a sentence or so.
 
### Existing Features
- Feature 1 - allows users X to achieve Y, by having them fill out Z
- ...

For some/all of your features, you may choose to reference the specific project files that implement them, although this is entirely optional.

In addition, you may also use this section to discuss plans for additional features to be implemented in the future:

### Features Left to Implement
- Another feature idea

## Technologies Used

In this section, you should mention all of the languages, frameworks, libraries, and any other tools that you have used to construct this project. For each, provide its name, a link to its official site 
and a short sentence of why it was used.

- [JQuery](https://jquery.com)
    - The project uses **JQuery** to simplify DOM manipulation.


## Testing

In this section, you need to convince the assessor that you have conducted enough testing to legitimately believe that the site works well. Essentially, in this part you will want to go over all of your user stories 
from the UX section and ensure that they all work as intended, with the project providing an easy and straightforward way for the users to achieve their goals.

Whenever it is feasible, prefer to automate your tests, and if you've done so, provide a brief explanation of your approach, link to the test file(s) and explain how to run them.

For any scenarios that have not been automated, test the user stories manually and provide as much detail as is relevant. A particularly useful form for describing your testing process is via scenarios, such as:

1. Contact form:
    1. Go to the "Contact Us" page
    2. Try to submit the empty form and verify that an error message about the required fields appears
    3. Try to submit the form with an invalid email address and verify that a relevant error message appears
    4. Try to submit the form with all inputs valid and verify that a success message appears.

In addition, you should mention in this section how your project looks and works on different browsers and screen sizes.

You should also mention in this section any interesting bugs or problems you discovered during your testing, even if you haven't addressed them yet.

If this section grows too long, you may want to split it off into a separate file and link to it from here.

## Deployment

This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub Pages or Heroku).

In particular, you should provide all details of the differences between the deployed version and the development version, if any, including:
- Different values for environment variables (Heroku Config Vars)?
- Different configuration files?
- Separate git branch?

In addition, if it is not obvious, you should also describe how to run your code locally.


## Credits

### Content
- The text for section Y was copied from the [Wikipedia article Z](https://en.wikipedia.org/wiki/Z)

### Media
- The photos used in this site were obtained from ...

### Acknowledgements

- I received inspiration for this project from X
