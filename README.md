# A Kayakers Guide To The French Alps

The kayakers guide to the French Alps aims to inform and guide users who are looking to paddle abroad; more specifically in the French Alps. It aims to be responsive across a range of viewing devices.

![A Kayakers Guide To The French Alps show on a range of devices](docs/images/am-i-responsive.png)

[View A Kayakers Guide To The French Alps on Github](https://github.com/ClaraR93/paddle-adventures/)

- - -

## CONTENTS

- [A Kayakers Guide To The French Alps](#a-kayakers-guide-to-the-french-alps)
  - [CONTENTS](#contents)
  - [User Experience (UX)](#user-experience-ux)
    - [Initial Discussion](#initial-discussion)
      - [Key Information for the site](#key-information-for-the-site)
    - [User Stories](#user-stories)
      - [Client Goals](#client-goals)
      - [First Time Visitor Goals](#first-time-visitor-goals)
      - [Returning Visitor Goals](#returning-visitor-goals)
      - [Frequent Visitor Goals](#frequent-visitor-goals)
  - [Design](#design)
    - [Colour Scheme](#colour-scheme)
    - [Typography](#typography)
    - [Imagery](#imagery)
    - [Wireframes](#wireframes)
    - [Features](#features)
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
    - [W3C Validator](#w3c-validator)
    - [Solved Bugs](#solved-bugs)
    - [Known Bugs](#known-bugs)
    - [Testing User Stories](#testing-user-stories)
    - [Lighthouse](#lighthouse)
      - [Index Page](#index-page)
      - [About Page](#about-page)
      - [Explore Page](#explore-page)
      - [Sign Up Page](#sign-up-page)
      - [Thank You Page](#thank-you-page)
    - [Full Testing](#full-testing)
  - [Credits](#credits)
    - [Code Used](#code-used)
    - [Content](#content)
    - [Media](#media)
    - [Acknowledgement](#acknowledgement)

## User Experience (UX)

### Initial Discussion

The kayakers guide to the French Alps provides a brief overview of paddleable rivers, places to visit, and stay within the area. The website displays information for a user to plan their kayaking holiday accordingly and connect with other like minded paddlers.

The sign up page provides a way for the user to register to an online paddling community where they can share experiences. Albeit just a concept page for the purpose of this website, the paddling community is an online social media site that allows users to access more information and connect with other users to share stories and advice.

#### Key Information for the site

- Featured rivers that are accessible to paddlers of most abilities.
- An example of places to visit, stay at, and experience within the area. External links are also provided here with more information on where to look and book.
- A sign up form allowing people to register and connect with others, followed by a thank you page when the user inputs their details.

### User Stories

#### Client Goals

- To be able to view the site on a range of device sizes.
- To provide easy to understand, and accessible information for people planning a kayaking holiday.
- To provide a means to a platform where the paddling community can connect and grow.

#### First Time Visitor Goals

- I want to know where to start when planning my first paddling holiday.
- I want to be greeted with visually exciting imagery that appeals to the adventurous paddler and explorer.
- I want to be able to navigate through the website with ease and find the information I require quickly.
- I want to be able to easily navigate to external links provided that will give me further detailed information on how to plan my holiday.

#### Returning Visitor Goals

- I want to be able to sign up to the online paddling community to connect with others and share potential holiday adventures of my own.

#### Frequent Visitor Goals

- I want to see regular updates to potential new places to paddle, places to visit, and things to do.

## Design

### Colour Scheme

![Matching gradient from ColorSpace](docs/images/matching-gradient.png)

The website uses this matching gradient scheme, pulled from [ColorSpace](https://mycolor.space/?hex=%23000000&sub=1), and generated from #000 (black). I chose this option, as it has similarities to alpine blue rivers, which ties in with the theme of the website. Providing this consistency across all 4 pages, contributes to a positive user experience.

### Typography

I used Google Fonts for the following fonts:

- Roboto Condensed for all headings, and subheadings across the site. This is a sans-serif font.
- Roboto for the body text across the site. This is a sans-serif font.
- Shadow into Light for the ‘Paddle Adventures’ logo font. This is a cursive font.

### Imagery

All digital images, (excluding two images in the [credit](#media) section), were taken by myself. I converted these from jpeg to webp using [BIRME](https://www.birme.net/).
The logo image featuring a paddle outline, was created by myself using the ‘Paintbrush’ application on my laptop.

### Wireframes

Wireframes were created for mobile, tablet and desktop.

### Features

The website consists of five pages, four of which are accessible from the navigation menu throughout the website and logo in the header. A final thank you page is accessible once the user submits the sign up form.

*All pages on the website have:*

- A responsive navigation bar which includes the website logo “Paddle Adventures” and navigation links across the header from left to right as followed - Home, About, Explore, and Sign up!

- The logo is also encompassed within a link tag that navigates you back to the home page from each page. The logo is centered, and features a simple sketch of a kayak paddle to the left, creating a minimalistic, but striking look.

- Each navigation link will display a bottom border when you hover over it, mimicking an underline to signify what page the user is about to click on.

- On a screen size of less than 786px wide, the header remains in a sticky position at the top. This allows users on mobile and tablet devices to scroll down a page and access the navigation bar easily and immediately.

- The footer consists of a headline of “Follow us!”, followed by font awesome icons to 3 social media websites - Facebook, Instagram and Youtube. These icons are universally recognised and when clicked on, open up in a separate browser to the page. When hovered over, these links display the colour #82A0AA, keeping in theme with the matching gradient.

- Displayed on the far right is the copyright content in small font. On a mobile device the headline, social media links, and copyright content are stacked vertically and centered, so the footer doesn't appear cluttered and the links are easily displayed and accessible to the user.

*Home Page:*

- A Hero image of an Alpine River in the mountains is displayed across the screen with a central heading in the foreground. This image is fixed to the screen, allowing the user to scroll down and view more of the picturesque mountains and river below. A black background with a transparency of 0.5 is laid over the image so the heading is legible, but the image is still clear and appreciated.
  
- The second heading, 'Plan your adventure starting right here!', features a link over the word 'here' that takes the user directly to the About page. 'Here', also increases slightly in size when the user hovers their mouse over the word. This gives the user a positive experience as they are encouraged to start planning their holiday as they navigate through the website, following clear instructions.

- Directly below in the 'What We Do' section, another full width background image is featured with a translucent background of #82a0aa placed over it. (This colour also matches the social media links below, when hovered over). The text container colour is a dark shade of gray, #4B4A54, which is also used across all pages to box off information, keeping to a consistent theme colour.

- The information featured gives the user a brief overview of what the website provides and a link (represented with a font-awesome icon of a globe), to the sign up page as well. When hovered over, the globe changes from white to black to signify to the user where to click.

*About Page:*

- The about page consists of two summaries that lets the user know the benefits of paddling in France, and travel information.
'Getting there' includes a link to an external page for users to book a Ferry crossing. This helps the user with travel and booking logistics. The link is represented as a font-awesome icon of a ship, which when hovered over, changes from white to black.

- Two appealing images are featured adjacent to each summary, giving the user a visual idea of what to expect on a kayaking holiday.

*Explore Page:*

- This page contains two featured rivers, presented with a photo and summary of each river and what to expect. Each feature river layout displays an image of a river, adjacent to the information presented on it.
The text consists of the name, brief summary and informative links on the river. These include a 'Put in' and 'Take out' link that takes the user to an external page displaying maps with a pin, and a final link to youtube, so the user can watch POV videos of the rivers displayed. All links open on an external page so the user doesn't “get lost” navigating their way through the site.

- Below this, there are three equal sections inline with one another displaying information about where to visit, stay, and other nearby experiences. Each is accompanied with a photo and link to an external site with more information. These provide informative links for the user, pointing them out to helpful sources so they are able to structure and plan their holiday easily.

- The links provided are represented by font-awesome icons, giving a visual cue for the user to click on. Again, when hovered over, these turn from white to black.
The images under each heading here are also wrapped in these external links, allowing the user to quickly navigate to this page by simply clicking on the image.

*Sign Up:*

- This page consists of a full width image in the French Alps, with a form overlaid in the centre.
The form simply asks users to fill in a name, email, and password, in order to create an account for the 'online paddling community' with 'Paddler's adventures'. A quick note below these reassures the user that personal information is not shared with third parties.

- When the user hovers over the 'create account' button, the font switches to white, whilst the background colour switches to white. This provides a visual queue for the user to submit their details.

*Thank You Page:*

- When the user submits their details on the Sign Up page, this automatically navigates them to the Thank You page, with a simple message to the user thanking them, and then a prompt below, reminding the user to check their inbox for further instructions. This elicits a positive emotional response from the user, as they have successfully submitted their details without any issues.

- There is a further 'return to home' button below this information, to guide the user back to the index page.

*Future Implementations:*

- The long-term goal is to update the feature rivers regularly to entice returning users to check up on other rivers they may not have considered. This would also apply to the 'Explore more' section in the Explore page to advertise places to stay, visit, and experience. The aim behind this is to not only encourage returning users to try different things, but to support and promote local businesses within the area by having them featured on this site.

- The paddling-community will provide regular alerts that tell the user of new features on the Explore page, encouraging them to revisit the website. All previous features will remain in the paddling-community, so users can access this information at any time.

### Accessibility

I have ensure that this website is as accessible friendly as possible, I have done the following to achieve this:

- Used semantic HTML.
- Included aria-label for website navigation to describe to the screen reader where the user is being taken to.
- Used alt attributes to images in HTML to describe them.
- Used visually hidden text to describe background images in CSS, where an alt attribute cannot be supplied.
- Using the WebAIM colour contrast checker to ensure all body text is legible with sufficient contrast.
  
## Technologies Used

### Languages Used

HTML and CSS were used to create this website.

### Frameworks, Libraries & Programs Used

Pencil - Used to create wireframes.

Git - For version control.

Github - To save and store the files for the website.

Google Dev Tools - To troubleshoot and test various features, and solve issues with responsiveness and styling.

[Google Fonts](https://fonts.google.com/) - To import and use the fonts from the website.

[Font Awesome](https://fontawesome.com/) - For the iconography on the website.

[My Color Space](https://mycolor.space/) - To choose the colours used for the website.

[Contrast Checker](https://webaim.org/resources/contrastchecker/) - Ran tests on all text against background colour to ensure contrast checker past.

[RGBA to HEX converter](https://simplecss.eu/rgbatohex.html) - To convert RGBA to HEX to use Contrast Checker when required.

[BIRME](https://www.birme.net/) - To convert images from jpeg to webp images to improve lighthouse performance.

[TinyPNG](https://tinypng.com/) - To compress large image files on website.

[Am I Responsive](https://ui.dev/amiresponsive?url=https://clarar93.github.io/paddle-adventures/index.html) - To show the website on a range of devices.

## Deployment & Local Development

### Deployment

Github Pages was used to deploy the live website. The instructions are as followed:

1. Log in (sign up) to Github.
2. Search for this repository, paddle-adventures.
3. Navigate to the settings tab.
4. On the left hand menu click on the pages link.
5. In the source section, select main from the drop down menu under Branch.
6. Select root from the drop down folder and click save.
7. Your live Github pages site is now deployed at the following: [ClaraR93](https://clarar93.github.io/paddle-adventures/index.html)

### Local Development

#### How to Fork

To fork the paddle-adventures repository:

1. Go to the GitHub repository.
2. Click on Fork button in the upper right-hand corner.

#### How to Clone

## Testing

### W3C Validator

### Solved Bugs

### Known Bugs

### Testing User Stories

### Lighthouse

#### Index Page

#### About Page

#### Explore Page

#### Sign Up Page

#### Thank You Page

### Full Testing

## Credits

### Code Used

### Content

### Media

### Acknowledgement
