# Trossachs Ski School

## Project Description
This project is a website developed for a fictional organisation, Trossachs Ski School, which has the primary business goal of attracting new customers and encouraging people to book ski instruction with the school. The site is targeted at ski enthusiasts who are interested in improving their skills with targeted tuition. The site is fully responsive so users can have a positive experience on any device, and it allows them to learn more about the school, the options on offer, and has a clear process for booking.

## Project Principles
1. **Mobile-first development:** The website has been designed with responsiveness in mind. All elements and structures were first created to fit mobile screens, with additional styling and classes to ensure responsiveness on larger screens. 
2. **User-centric development:** The user’s experience is taken into consideration at every step in the development process in order to make the end product as convenient and efficient as possible. 
3. **Accessibility:** Code used within the project is compliant with best practice for accessibility e.g. including alt values on all images, ensuring comments are used appropriately to provide context
4. **Navigability:** Clear navigation is present on all pages of the site, allowing users to move to different areas within a single click
5. **Visual hierarchy:** Visual design of the site clearly delineates different elements like headers, footers, forms etc. and is consistent across all pages

## Business Goals
The primary business goal for the company is to increase the number of bookings they receive through the website. <br>
A secondary business goal for the company is to utilise the site to attract and hire new staff.

## User Stories
A series of user stories have been created to facilitate the development of the project. Acceptance criteria and tasks were assigned to each story which allows these to serve as a series of milestones which much be achieved to reach a minimum viable product.<br>
Priority tags (i.e. "must have", "should have" and "could have") were added to each user story to help prioritise the order in which these were tackled. 


### 1. As a holidaymaker on a budget, I want to see a list of the types of lessons available and their prices so that I can determine the best lesson option for my child. (Must Have)

**Acceptance Criteria:**
- The home page displays a list of the different types of lessons and instruction available, sorted by level.
- Each item in the list includes the name, price, and a brief description. 
- The list is responsive and looks good on all devices

**Tasks:**
- Add an HTML section on the homepage dedicated to lesson types available.
- Display pricing for different options
- Style the events using Bootstrap (cards, grid)
- Populate cards with details


### 2. As a local business owner, I would like to be able to quickly identify the contact details and information about the ski school so I can include this in recommendations to my own customers. (Must Have)

**Acceptance Criteria:**
- The site has a dedicated section for contact details, address and opening hours.
- This section is visible and accessible from anywhere on the website.

**Tasks:**
- Develop a section for contact details, address and opening hours 
- Ensure this section is visible on all pages, adhering to common design standards. 


### 3. As a potential booker, I want to see good quality images and descriptions about what is on offer so I can determine whether this is the school I want to commit to. (Must Have)

**Acceptance Criteria**
- Homepage features a hero image relevant to ski holidays/instructio
- Engaging descriptions of all lessons and clinics are displayed clearly and concisely 
- The pages are uncluttered and attractive

**Tasks:**
- Add high-quality hero image, and images for lesson/clinic cards
- Embed descriptions about the school and the lessons/clinics on offer within the site content
- Design and implement homepage layout with prominently featured images and descriptions

### 4. As a holidaymaker, I need a clear and easy-to-use form to book lessons for multiple people so that I can book lessons for our family. (Must Have)

**Acceptance Criteria:** 
- Add a booking form section to the homepage (or make it a separate page?) with fields for name, email, date and preferred type of instruction. 
- Accessed via button on main page - Call to Action. 
- Link the form to a success page to let customers know they have filled it out successfully. 
- The booking form and success page must be responsive and look good on all devices.

**Tasks:**
- Create booking.html form section OR page with relevant input fields for name, email, date and a select drop-down list for instruction type.
- Link output from form to a simple success page confirming form submission. 
- Utilise Bootstrap grid and classes to make the form responsive on all screen sizes.

### 5. As a holidaymaker, I want to be able to navigate through the site easily on all types of devices so I can make bookings quickly. (Must Have)

**Acceptance Criteria:**
- Create navigation section within the header for each site page which allows users to click to navigate to various pages/sections, including “Home”, “Hiring”, “Lessons”
- “Book Now” call to action button
- When in a particular page, the name of the page stands out compared to other navigation links. Navigation is intuitive. 

**Tasks:**
- Develop a Bootstrap navbar which is responsive on various screen sizes.
- Ensure all pages and key sections are easily accessible from anywhere on the site.

### 6. As a holidaymaker looking to book lessons, I want to read testimonials from others who have used the ski school so that I can feel confident when booking. (Should have)

**Acceptance Criteria:** 
- Website includes a testimonials section on the main page which displays past customer reviews.
- The testimonials are clearly visible and are presented in a format that is easy to read, with key info (e.g. name, quote)

**Tasks:**
- Create section on homepage for customer testimonials
- Style the testimonials using Bootstrap (cards, grid) to ensure responsiveness 
- Add samples


### 7. As a qualified ski instructor, I want to see any employment opportunities and how to apply so that I can secure work with the ski school. (Should have)

**Acceptance Criteria:**
- Site has a dedicated “Hiring” page which provides information on the type of placements/work currently available
- Instructors interested in applying can submit their details via form to initiate a job application process

**Tasks:**
- Develop separate html page for Hiring
- Create and populate list of work placements open for application using Bootstrap cards
- Make list responsive


### 8. As a solo holidaymaker, I want to see a list of social events or group lessons open to singles so that I can have a good social experience. (Could have)

**Acceptance Criteria:** 
- The homepage has a dedicated section for social events with relevant details

**Tasks:**
- Create static section for a list of upcoming events/socials on the homepage
- Develop list with Bootstrap 
- Make list responsive


### 9. As a physically-impaired skier with specific needs related to the instruction, I want to see a list of the staff and their qualifications to determine whether the school can cater to my needs. (Could have)

**Acceptance Criteria:**
- Site has a dedicated “Our Staff” section or page which clearly displays the details of individual staff members and their training level.
- Staff information is laid out in an easily readable format which is responsive on all devices.

**Tasks:**
- Create separate “Our Staff” page 
- Make list responsive

## Features

### Existing Features
#### 1. Navigation bar
The navigation bar appears at the top of the screen on all pages and contains links to major areas including the Lessons and Clinics sections on the homepage, as well as links to the Hiring and Booking forms and the Testimonials page. Where appropriate, the `active` class has been used to ensure that the current page is highlighted on the navigation bar. The navigation bar collapses into a drop-down menu on screens with lower than 992px (below desktop size).

Up to 992px <br>
![NavBar Collapsed Screenshot](assets/screenshots/screenshot-navbar-collapsed.png)

992px+ <br>
![NavBar Screenshot](assets/screenshots/screenshot-navbar.png)

#### 2. Homepage header & hero section
Directly below the navigation bar at the home page, a header and hero image area has been created. This area is covered by a responsive, high-quality hero image that stretches to fit the screen size. This image was used as a source for selecting a colour scheme for the website as a whole. The area also contains a title, subtitle and lead text intoducing the school at a glance, and this is imposed over a semi-transparent colour block to make it readable against the image in the background. The font size of the lead text decreases below 768px screen size in order to prevent overflow.

![Hero Area Screenshot](assets/screenshots/screenshot-hero-area.png)

#### 3. Homepage reasons section
The first element within the main area of the home page is the "Reasons" section, which provide users with several benefits of booking with this ski school. The reasons are kept punchy and concise, one short sentence each, with icons for visual guidance. The reasons section is responsive - on screens below 1200px the items appear stacked vertically, while on larger screens they split into two columns to better utilise space. 

Up to 1200px <br>
![Reasons Area Screenshot ](assets/screenshots/screenshot-reasons-small.png)

Over 1200px <br>
![Reasons Area Screenshot ](assets/screenshots/screenshot-reasons-large.png)



#### 4. Homepage lessons section
#### 5. Homepage clinics section
#### 6. Booking form
#### 7. Hiring form
#### 8. Form success page
#### 9. Testimonials page

### Features to implement
1. Our staff page
2. Social events page
3. Testimonials carousel (potentially amend to include this on homepage rather than separate page)
4. Key information page


## Testing

### Validator Outcomes

### Resolved Bugs

### Unfixed Bugs

### Deployment


## Credits

### Content
Bootstrap was used extensively across the site, both in terms of bootstrap structures (e.g. grid, table, form) copied directly from Bootstrap guidance and customised, as well as the use of general Bootstrap classes (e.g. my-4). Utilisation of bootstrap classes allowed me to reduce the amount of custom CSS styling required. 
Google Fonts for custom fonts used throughout site. Link to embed code used: 
Favicons from ??? for browser icons
Reference to Love Running and Boardwalk Games modules from CI full stack course were used for guidance on general structure and layout.
W3C HTML & CSS validators
Icolour pallete

### Media
Images were sourced from Pexels and Pixabay. All images used within the site are free-use, no royalties.
Font Awesome for iconography, link to personal kit:




![CI logo](https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png)

Welcome David Thomson,

This is the Code Institute student template for Gitpod. We have preinstalled all of the tools you need to get started. It's perfectly ok to use this template as the basis for your project submissions.

You can safely delete this README.md file or change it for your own project. Please do read it at least once, though! It contains some important information about Gitpod and the extensions we use. Some of this information has been updated since the video content was created. The last update to this file was: **June 18, 2024**

## Gitpod Reminders

To run a frontend (HTML, CSS, Javascript only) application in Gitpod, in the terminal, type:

`python3 -m http.server`

A blue button should appear to click: _Make Public_,

Another blue button should appear to click: _Open Browser_.

To run a backend Python file, type `python3 app.py` if your Python file is named `app.py`, of course.

A blue button should appear to click: _Make Public_,

Another blue button should appear to click: _Open Browser_.

By Default, Gitpod gives you superuser security privileges. Therefore, you do not need to use the `sudo` (superuser do) command in the bash terminal in any of the lessons.

To log into the Heroku toolbelt CLI:

1. Log in to your Heroku account and go to *Account Settings* in the menu under your avatar.
2. Scroll down to the *API Key* and click *Reveal*
3. Copy the key
4. In Gitpod, from the terminal, run `heroku_config`
5. Paste in your API key when asked

You can now use the `heroku` CLI program - try running `heroku apps` to confirm it works. This API key is unique and private to you, so do not share it. If you accidentally make it public, you can create a new one with _Regenerate API Key_.

### Connecting your Mongo database

- **Connect to Mongo CLI on a IDE**
- navigate to your MongoDB Clusters Sandbox
- click **"Connect"** button
- select **"Connect with the MongoDB shell"**
- select **"I have the mongo shell installed"**
- choose **mongosh (2.0 or later)** for : **"Select your mongo shell version"**
- choose option: **"Run your connection string in your command line"**
- in the terminal, paste the copied code `mongo "mongodb+srv://<CLUSTER-NAME>.mongodb.net/<DBname>" --apiVersion 1 --username <USERNAME>`
  - replace all `<angle-bracket>` keys with your own data
- enter password _(will not echo **\*\*\*\*** on screen)_

------

## Release History

We continually tweak and adjust this template to help give you the best experience. Here is the version history:

**June 18, 2024,** Add Mongo back into template

**June 14, 2024,** Temporarily remove Mongo until the key issue is resolved

**May 28 2024:** Fix Mongo and Links installs

**April 26 2024:** Update node version to 16

**September 20 2023:** Update Python version to 3.9.17.

**September 1 2021:** Remove `PGHOSTADDR` environment variable.

**July 19 2021:** Remove `font_fix` script now that the terminal font issue is fixed.

**July 2 2021:** Remove extensions that are not available in Open VSX.

**June 30 2021:** Combined the P4 and P5 templates into one file, added the uptime script. See the FAQ at the end of this file.

**June 10 2021:** Added: `font_fix` script and alias to fix the Terminal font issue

**May 10 2021:** Added `heroku_config` script to allow Heroku API key to be stored as an environment variable.

**April 7 2021:** Upgraded the template for VS Code instead of Theia.

**October 21 2020:** Versions of the HTMLHint, Prettier, Bootstrap4 CDN and Auto Close extensions updated. The Python extension needs to stay the same version for now.

**October 08 2020:** Additional large Gitpod files (`core.mongo*` and `core.python*`) are now hidden in the Explorer, and have been added to the `.gitignore` by default.

**September 22 2020:** Gitpod occasionally creates large `core.Microsoft` files. These are now hidden in the Explorer. A `.gitignore` file has been created to make sure these files will not be committed, along with other common files.

**April 16 2020:** The template now automatically installs MySQL instead of relying on the Gitpod MySQL image. The message about a Python linter not being installed has been dealt with, and the set-up files are now hidden in the Gitpod file explorer.

**April 13 2020:** Added the _Prettier_ code beautifier extension instead of the code formatter built-in to Gitpod.

**February 2020:** The initialisation files now _do not_ auto-delete. They will remain in your project. You can safely ignore them. They just make sure that your workspace is configured correctly each time you open it. It will also prevent the Gitpod configuration popup from appearing.

**December 2019:** Added Eventyret's Bootstrap 4 extension. Type `!bscdn` in a HTML file to add the Bootstrap boilerplate. Check out the <a href="https://github.com/Eventyret/vscode-bcdn" target="_blank">README.md file at the official repo</a> for more options.

------

## FAQ about the uptime script

**Why have you added this script?**

It will help us to calculate how many running workspaces there are at any one time, which greatly helps us with cost and capacity planning. It will help us decide on the future direction of our cloud-based IDE strategy.

**How will this affect me?**

For everyday usage of Gitpod, it doesn’t have any effect at all. The script only captures the following data:

- An ID that is randomly generated each time the workspace is started.
- The current date and time
- The workspace status of “started” or “running”, which is sent every 5 minutes.

It is not possible for us or anyone else to trace the random ID back to an individual, and no personal data is being captured. It will not slow down the workspace or affect your work.

**So….?**

We want to tell you this so that we are being completely transparent about the data we collect and what we do with it.

**Can I opt out?**

Yes, you can. Since no personally identifiable information is being captured, we'd appreciate it if you let the script run; however if you are unhappy with the idea, simply run the following commands from the terminal window after creating the workspace, and this will remove the uptime script:

```
pkill uptime.sh
rm .vscode/uptime.sh
```

**Anything more?**

Yes! We'd strongly encourage you to look at the source code of the `uptime.sh` file so that you know what it's doing. As future software developers, it will be great practice to see how these shell scripts work.

---

Happy coding!
