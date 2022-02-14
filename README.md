# Waterford Hiking Club - Official Website

Site URL: https://jburrellirl.github.io/ProjectOne/

This is a static website for the Waterford Hiking Club. Our club was founded in 1987 by a group of friends. This site was created to allow people to find details about the club, its background, guidelines around how to join the club itself, and to get in touch with the club in advance of joining any planned walks. Here's a screenshot of the site to show that it's responsive to different screen sizes:

![Responsive Screenshot](https://raw.githubusercontent.com/JBurrellIRL/ProjectOne/main/assets/images/readme/amiresponsive.png)

## UX

This website is for both current members and also prospective members that might like to find out more about joining the club. 
On the site, people can find out details about the club, read about it and its policies, see photos taken on previous walks by club members, and also get in touch either through a Contact Us form on the site itself, or by clicking through to club social media accounts.

On the site itself, we have navigation links that take us directly to the section that the user wants to navigate to. We have both a site title with the name of the club and also a text area overlaying the banner, that includes the name of the club, making it easy for someone landing on the site for the first time to identify what the site is about.

* As a long-time club member, I'm interested in viewing newly-added items to the gallery. This area is updated on a regular basis so I'm interested in keeping an eye on this area. I also want easy access to the club's social media profiles, for updates on upcoming walks etc. 
* As a possible new club member, I want an area where I can read basic details about the club (provided in the "About Us" section) as well as ways to contact the club itself, which I can do either via the Contact form, or by visiting the linked social media profiles.
* I want to be linked to social media accounts regardless of whether I'm a long-term or new club member, for the most up-to-date information on up and coming events.
* As someone who just happens upon the site, I want to know what this club is about. This website achieves this, with a site title, banner text, text area and a gallery area that all inform the user as to the purpose of the website.

## Features

### Existing Features

#### **Feature 1: Navbar** 

Allows the user to clearly see what pages are part of the website and can be clicked, which will take them to the section of the page. Fixed nav bar gives people the option to click to different sections without having to scroll back to the top.

![Navigation Bar](https://github.com/JBurrellIRL/ProjectOne/blob/fd9cb4e26c4f3a23439db94a8238e08f4bbb4c2c/assets/images/readme/navigation.png?raw=true)

#### **Feature 2: Banner section**

Includes a background image of the Comeragh Mountains, and also a text overlay to inform the visitor about the purpose of the site.

![Banner Image](https://github.com/JBurrellIRL/ProjectOne/blob/31dba48f7ab4c2dda6766f9072afec9318cd0f5f/assets/images/readme/banner-image.png?raw=true)

#### **Feature 3: About Us section** 

Gives a brief blurb about the history of the club, and also sections with the equipment required in order to join one of our hikes, and also some brief guidelines around what to expect when taking part in one of our hikes.

![About Us section](https://github.com/JBurrellIRL/ProjectOne/blob/fd9cb4e26c4f3a23439db94a8238e08f4bbb4c2c/assets/images/readme/about-us.png?raw=true)

#### **Feature 4 - Gallery section**

Allows the site visitor to view photos taken on previous walks by club members.

![Gallery section](https://github.com/JBurrellIRL/ProjectOne/blob/main/assets/images/readme/gallery.png?raw=true)

#### **Feature 5: Contact form**

Allows the user to get in touch with the club by encouraging visitors to leave their name, email address and a custom messsage, along with providing their current hiking ability. Users have to add information in the "Subject" line that summarises their message.

![Contact Us section](https://github.com/JBurrellIRL/ProjectOne/blob/fd9cb4e26c4f3a23439db94a8238e08f4bbb4c2c/assets/images/readme/contact-us.png?raw=true)

#### **Feature 6: Linked social icons**

Allows the user to reach social media profiles managed by the group, including Instagram, Facebook and Twitter.

![Site footer](https://github.com/JBurrellIRL/ProjectOne/blob/main/assets/images/readme/footer.png?raw=true)

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
2. Banner section - banner image is of sufficient resolution that it doesn't noticeably pixelate on larger screens. I have used a media query to resize the text within the banner text div at a smaller screen width, so that it remains readable.
3. About Us section - paragraphs are evenly spaced across the page, and are responsive to mobile through the use of media queries. Unordered list bullet points are aligned with text using the list-style-position property.
4. Gallery section - images are added and arranged into a masonry column layout. This area is also responsive to mobile through the use of a media query.
5. Contact form: In the contact form section, the email address field will return an error if you don't enter an email address in the expected format. If you do not fill in a cell you cannot send your message and will receive an error asking you to fill in the relevant field. Each cell input is set to required, as all information requested through the form is important for the walking club. Each form field sends its data correctly to the server. Form fields are responsive to mobile devices.
6. Linked social icons: In the footer there are social buttons linked to the relevant social networks. When clicked the user will be directed to other sites in a new open tab, to ensure that our site remains open and a click of the "Back" button is not required.

* The site was tested continuously across various modern browsers, especially in Google Chrome using the DevTools suite. I tested the site using the responsiveness tool, and the site is responsive across devices of varying screen widths. 

* The site receives a good score from the Lighthouse testing tool, as shown here: 

![Lighthouse results](https://github.com/JBurrellIRL/ProjectOne/blob/fd9cb4e26c4f3a23439db94a8238e08f4bbb4c2c/assets/images/readme/lighthouse.png?raw=true)


### Bugs

* Resolved an issue where my banner image wasn't loading in any web browser, due to incorrect file path.
* Resolved an issue with top of each page section being stuck behind the fixed header after clicking on anchor link.
* No further unresolved bugs have been detected.

## Deployment

The site was deployed to GitHub pages. The steps to deploy are as follows:

* In the GitHub repository, navigate to the Settings tab, and under the GitHub Pages section, click on the "Check It Out Here" link.
* From the source section drop-down menu, select the Master Branch
* Once the master branch has been selected, click Save to automatically publish the page.
* The live link can be found here - https://jburrellirl.github.io/ProjectOne/ 

## Validator Testing

* HTML - No errors were returned when passing through the official [W3C Validator](https://validator.w3.org/nu/?doc=https%3A%2F%2Fjburrellirl.github.io%2FProjectOne%2F).
* No errors were found when passing through the official [CSS Validator](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fjburrellirl.github.io%2FProjectOne%2Fassets%2Fcss%2Fstyle.css&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en).

## Credits

Resources used include the following:

* Code Institute - course content, Coders Coffeehouse and Love Running projects, for tutorials and help with HTML and CSS syntax.
* Udemy Web Developer Bootcamp course, which I am also taking in parallel to this Code Institute course: https://www.udemy.com/course/the-web-developer-bootcamp/
* Coding assistance was obtained from Stack Overflow, W3Schools and above developer course. Comments are in CSS file. 
* The icons in the footer are from Font Awesome - https://fontawesome.com/ 

### Content

* The text areas on the website were written by me. 
* The image media displayed on the site comes from the following third-party sources. No copyright infringement is intended:
  
 - comeragh1: https://pbs.twimg.com/media/Ewq1LPGXMAMrxsY?format=jpg&name=4096x4096 
 - comeragh2: https://outsider.ie/wp-content/uploads/2017/10/comeragh-mountains-4-1024x683.jpg
 - comeragh3: https://images.squarespace-cdn.com/content/v1/5999b55abe6594fce2334596/1554576681137-7LAGIEZ53SX0ZMRIZ74J/Coumshingaun+Lake+Swim.jpg?format=1000w 
 - comeragh4: https://www.thesun.ie/wp-content/uploads/sites/3/2019/09/mountain.png 
 - comeragh5: https://cdn.stocksnap.io/img-thumbs/960w/mountains-nature_P0ZHH10FNJ.jpg
 - comeragh6: https://res.cloudinary.com/fleetnation/image/private/c_fill,g_center,h_640,w_640/v1520006126/zx5rdnudhowmjly63bsk.jpg
 - comeragh7: https://tworockoutdoor.ie/images/Knockanaffrin_Comeraghs.png 
 - mahonfalls: https://www.independent.ie/incoming/366fe/38480744.ece/AUTOCROP/w1240h700/mahonfalls.jpg 
 - mahonfalls2: https://www.mountain-forecast.com/system/images/25620/large/Comeragh-Mountains.jpg 
 - heroimage: https://pbs.twimg.com/media/Dosb0MZWwAArUUf.jpg 

