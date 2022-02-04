# Waterford Hiking Club - Official Website

This is a static website for the Waterford Hiking Club. Our club was founded in 1987 by a group of friends. This site was created to allow people to find details about the club, its background, guidelines around how to join the club itself, and to get in touch with the club in advance of joining any planned walks. 

## UX

This website is for both current members and also prospective members that might like to find out more about joining the club. 
On the site, people can find out details about the club, read about it and its policies, see photos taken on previous walks by club members, and also get in touch either through a Contact Us form on the site itself, or by clicking through to club social media accounts.

On the site itself, we have navigation links that take us directly to the section that the user wants to navigate to. We have both a site title with the name of the club and also a text area overlaying the banner, that includes the name of the club, making it easy for someone landing on the site for the first time to identify what the site is about.

* As a long-time club member, I'm interested in viewing newly-added items to the gallery. This area is updated on a regular basis so I'm interested in keeping an eye on this area. I also want easy access to the club's social media profiles, for updates on upcoming walks etc. 
* As a possible new club member, I want an area where I can read basic details about the club (provided in the "About Us" section) as well as ways to contact the club itself, which I can do either via the Contact form, or by visiting the linked social media profiles.
* I want to be linked to social media accounts regardless of whether I'm a long-term or new club member, for the most up-to-date information on up and coming events.
* As someone who just happens upon the site, I want to know what this club is about. This website achieves this, with a text area and a gallery area.

## Features

### Existing Features

* Feature 1: Navbar - Allows the user to clearly see what pages are part of the website and can be clicked, which will take them to the section of the page. Fixed nav bar gives people the option to click to different sections without having to scroll back to the top.
* Feature 2: Banner section - Includes a background image of the Comeragh Mountains, and also a text overlay to inform the visitor about the purpose of the site.
* Feature 3: About Us section - Gives a brief blurb about the history of the club, and also sections with the equipment required in order to join one of our hikes, and also some brief guidelines around what to expect when taking part in one of our hikes.
* Feature 4: Contact form - Allows the user to get in touch with the club by encouraging visitors to leave their name, email address and a custom messsage, along with providing their current hiking ability. Users have to add information in the "Subject" line that summarises their message.
* Feature 5: Linked social icons - Allows the user to reach social media profiles managed by the group, including Instagram, Facebook and Twitter.

### Features Left to Implement

In the future, we are looking to add a dynamic section that auto-populates with upcoming events, both hiking and social. We have a plan in place to embed Facebook events to the site using the Facebook Page Plugin Widget. 

## Technologies Used

Below is a list of languages, plugins and other tools used to create and develop this website. 

* HTML5: To structure the website and the content included on the website. Semantic tags were used to make each section and code's used obvious.
* CSS3: To style the features used throughout the website to achieve design and placement targets e.g. adding padding, a background image, margins, fonts, and changing colors.
* [Google Fonts:](https://fonts.google.com/)
    - Google fonts were used to import the 'Open Sans' and 'Playfair Display' fonts into the style.css file which is used on all pages throughout the project.
* [Font Awesome:](https://fontawesome.com/)
    - Font Awesome was used in the footer section to create the social media icons used in the site.
* [Balsamiq:](https://balsamiq.com/)
    - Balsamiq was used to create a mock-up of the site to show to my mentor, prior to the site build.

## Testing

1. Navbar: Go to the website and click each item to go to the right section. You can also do this through mobile. Nav bar remains fixed at the top of the page, to allow easy navigation between sections.
2. Banner section - banner image is of sufficient resolution that it doesn't noticeably pixelate on larger screens. I have used a media query to resize the text within the banner text div, so that it remains readable 
3. About Us section - paragraphs are evenly spaced across the page, and are responsive to mobile through the use of media queries. Unordered list bullet points are aligned with text using the list-style-position property.
4. Gallery section - images are added and arranged into a masonry column layout. This area is also responsive to mobile through the use of a media query.
5. Contact form: In the contact form section, the email address field will return an error if you don't enter an email address in the expected format. If you do not fill in a cell you cannot send your message and will receive an error asking you to fill in the relevant field. Each cell input is set to required, as all information requested through the form is important for the walking club.
6. Linked social icons: In the footer there are social buttons linked to the relevant social networks. When clicked the user will be directed to other sites in a new open tab, to ensure that our site remains open and a click of the "Back" button is not required.