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
  - [Deployment \& Local Developmen](#deployment--local-developmen)
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

- Displayed on the far right is the copyright content in small font. On a mobile device the headline, social media links, and copyright content are stacked vertically and centered, so the footer doesn’t appear cluttered and the links are easily displayed and accessible to the user.

*Home Page:*

- A Hero image of an Alpine River in the mountains is displayed across the screen with a central heading in the foreground. This image is fixed to the screen, allowing the user to scroll down and view more of the picturesque mountains and river below. A black background with a transparency of 0.5 is laid over the image so the heading is legible, but the image is still clear and appreciated.
  
- The second heading, ‘Plan your adventure starting right here!’, features a link over the word ‘here’ that takes the user directly to the About page. ‘Here’, also increases slightly in size when the user hovers their mouse over the word. This gives the user a positive experience as they are encouraged to start planning their holiday as they navigate through the website, following clear instructions.

- Directly below in the ‘What We Do’ section, another full width background image is featured with a translucent background of #82a0aa placed over it. (This colour also matches the social media links below, when hovered over). The text container colour is a dark shade of gray, #4B4A54, which is also used across all pages to box off information, keeping to a consistent theme colour.

- The information featured gives the user a brief overview of what the website provides and a link (represented with a font-awesome icon of a globe), to the sign up page as well. When hovered over, the globe changes from white to black to signify to the user where to click.

*About Page:*

- The about page consists of two summaries that lets the user know the benefits of paddling in France, and travel information.
‘Getting there’ includes a link to an external page for users to book a Ferry crossing. This helps the user with travel and booking logistics. The link is represented as a font-awesome icon of a ship, which when hovered over, changes from white to black.

- Two appealing images are featured adjacent to each summary, giving the user a visual idea of what to expect on a kayaking holiday.

### Accessibility

## Technologies Used

### Languages Used

### Frameworks, Libraries & Programs Used

## Deployment & Local Developmen

### Deployment

### Local Development

#### How to Fork

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
