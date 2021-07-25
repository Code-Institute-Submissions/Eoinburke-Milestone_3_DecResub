Singular Artists
Code Institute MS1 Project in User-Centric Frontend Development
The brief was to develop a static front end project with a minimum of three separate page areas using HTML and CSS while following UX industry conventions. This website is created for educational purposes.

View website in GitHub Pages.

alt text

Image produced from Am I Responsive

SingularArtists.ie
The website is created to showcase Irish promoter Singular Artists' work in the event industry. The website highlights various clients the company are representing and their wealth of experience in the industry.

The site features an about section, a section listing all clients represented, an events listings section and a contact section.

The primary goal of the website is to inform and direct users to the contact form. As a B2B website, the aim is to convey credibility and assurance to the user. The website layout and navigation structure will guide the user to company information and client-list, highlighting it's reliability and expertise. These sections along with the CTA's will lead the user towards the contact form.

The business goals of this website are:

To inform users about the exciting client base.
To increase brand recognition.
To encourage potential clients to establish contact with the team.
The customer goals of this website are:

To find out more information about the company and its experience in the industry.
To seek validation that the company are reputable and credible to potentially build a long-term working relationship.
To find out which artists the company represents and venues they are currently working with in order to gauge successful ticket sales and events.
To view evidence of promotional activity such as active social media channels marketing and promoting their current clients.
To effortlessly find contact information to touch base with the promoter.
UX
Strategy
My strategy for the site was to provide reputable content and ease of access to users trying to attain information by utilising key UX principals. I wanted to incorporate the majority of elements from Peter Morville's UX Honeycomb to create a great experience for the user. In particular, I believed that the aspects of "Credible", "Valuable" and "Usable" were highly significant to implement in this project. I felt that the owner images and client list would add to the credibility of the company and the overall site.

Ideal users of this website:
Artists/Bands/Agents
Venue Managers
Ticketing Providers
These users are looking for:
An experienced, credible promoter to work with
Evidence of promotional work
This project is the best way to achieve their goals because:
Most promoter websites increase the cognitive load on the user. This website enables effortless navigation through the pages by building assurance and directing the user towards the contact elements.

User Stories
As a Venue Manager, I want to find out the artists the promoter works with so that I can decide if there is potential to reach capacity and sell-out nights at our venue.
As a Venue Manager, I want to discover what experience the company has so that I can evaluate if they have enough expertise to work with our venue.
As a Venue Manager, I want to check out their social media channels to view their current promotional activity to see if they can successfully market events.
As an Artist/Agent, I want to learn about the type of artists the promoter is working with so that I can view their previous marketing strategies and their ability to potentially promote our future gigs.
As an Artist/Agent, I want to learn about the company history as I want to work with an experienced promoter who is well connected within the industry.
As a Ticketing Agent, I want to learn about the promoter’s artists and venues so that I can evaluate ticket sales potential.
As a Ticketing Agent/Artist/Agent/Venue Manager, I want to find out if the promoter is reputable, credible and approachable to potentially be able to build a long-term relationship.
Scope
To achieve the strategic goals, I wanted to include the following features in this production release:

Header containing company logo and navigation bar
Carousel using powerful imagery of current artists at live gigs
Company image and info detailing experience in the industry
Client list with a bio and links to artist's social media and website
List of upcoming events linking to ticketing provider
Simple Contact Form
Footer containing links to social media, phone number and email
Structure
I decided to create a single-page website incorporating only the necessary actions and info required by the ideal users to reduce cognitive overload. The navigation bar would include the links to all four sections on the right and the company logo/home link placed on the left to follow industry standard and create familiarity with the user. This allows the user to easily learn and understand the structure and effortlessly navigate through the site when using it for the first time. I decided that the links would also be strategically placed in the intended user flow. i.e. About->Artists->Events->Contact. This would allow the user to learn about the experience the promoter has, their credibility in the industry with the artists they represent, the large number of events presented to gain the user's trust propelling them towards the contact form.

Skeleton
Wireframes: Website contains 4 sections; About (Who We Are), Artists (Who We Represent), Events and a Contact (Get In Touch) section. I had originally thought about creating a website with a homepage and 4 separate pages but later decided to compile all sections into a single page website to create a better flow. Please note the finalised website contains slight variations to the original wireframe
Surface
The company logo incorporates the vibrant dual colours of white and bright pink. The promoters selected striking colours to convey a sense of confidence and excitement as a reflection of their industry. I wanted the brand colours to feature as the hover/accent colours in the Call To Action buttons to connect the brand with the actions taken by the user. To allow the CTA's and brand colours to stand out and gain the attention of the user, I wanted to keep the majority of the site monochrome with black and white text and teal to tie the colours together. This also allows the website to appear less cluttered and minimalistic adding to the overall UX. This colour scheme was chosen to create a sleek and modern feel in keeping with the brand. I wanted to use the Montserrat font and Sans-Serif back up fonts to maintain the clean-cut image.

Features
The fully responsive website consists of the header, footer and four sections; About (Who We Are), Artists (Who We Represent), Events and the Contact Form. Each section has a H2 heading describing the section content along with a subheading directing the user how to operate the content if required. I used Hover.css on the nav links, CTA's and footer icons to create an enjoyable navigation experience for the user and to highlight that the website is functioning correctly. I used the Bootstrap​ plugin, Scrollspy, to automatically update links in the navigation list based on the current scroll position. I also wanted to highlight the colour of the current section with the accent colour to remind the user of their location on the site. I wanted to adjust the opacity of the navbar to allow it to blend in with the site and not take too much attention away from the content. On small devices, I decided to code the navbar to collapse into a hamburger menu as it is ubiquitous and users understand it's purpose on mobile sites. All sections are linked by CTA's at the bottom of their section guiding the user towards the contact form once they have learnt about the company.

Header: The header features a responsive navigation bar with links pointing to each section on the right-hand side with the company logo placed on the left to follow standard industry practice. The navbar is fixed to allow the user ease of access to the site’s core functionalities and as a result, generates high usability for the one-page website. It contains a Bootstrap carousel of three striking images of current artists performing live. This signifies the popularity of the artist and successful events run by the company. The larger the crowd displayed in the image, the greater the indication of high revenue and high success for potential clients. Each image points to the three informative sections of the website; who the company are, who the company represents and upcoming events. Each image includes a caption reflecting that particular section and a CTA. The header was intentionally designed with a monochrome theme to strategically draw the user's attention to the brand logo and accent colours on the CTA's. I applied the filter property with the values of brightness(95%) and saturate(0%) to the Carousel images to achieve this goal.

About (Who We Are): The About section features an image of the three company directors along with three reasons why potential clients should work with the company to create symmetry. Font Awesome icons and captions are used above each p to add visual meaning to the text and display the information in a way that is faster to comprehend should the user not wish to read the entire paragraphs. I used Bootstrap cards to display the content uniformly.

Artists (Who We Represent): The Artists section features a Bootstrap Modal Gallery displaying thumbnails in a grid. When the user clicks on an image, a Modal pops up displaying a YouTube link to one of their music videos, a short bio and links to their personal website and social media channels.

Events: The Events section features a Bootstrap Carousel of Cards displaying the upcoming events of the client base. Each Card features the main event info and the link to the ticketing provider. The Carousel slides automatically but can be manually selected via the controls.

Contact Form: Finally, once the user has gained knowledge and confidence from the content, they are presented with a simple Contact Form. The form is compiled of only the necessary information required to avoid the user losing interest and not making contact.

Footer: The footer section contains contact and copyright information as well as external links to the company's Social Media channels, phone number and email. The links to the phone and email make it easier to get in touch if the user does not want to fill out the contact form. I also wanted to add a link to allow the user to jump back to the top instead of scrolling to further improve the overall UX.

Features Left to Implement
Due to time restraints, I was unable to include the following features but hope to implement them in a future release:

Embed social media feeds & Spotify playlist - To showcase promotional activity and create buzz for the client base.
Blog - To provide updates and reviews of events and artists' news.
Live Chat app - To provide an instant connection between the user and company with high visibility on the site.
Technologies Used
In the construction of this project I have utilised the following languages, frameworks, libraries and tools:

HTML5, CSS3 and JavaScript programming languages
Bootstrap v4.5.3
The project used Bootstrap to simplify the website layout by integrating the Modals for further artist info and the Cards for event listings and company info. Also to provide overall responsive behaviour on all devices.
GitPod
I used GitPod as the development environment for my website. I also used Git for Version Control in the project.
GitHub
The project used GitHub to host my code that was created and pushed from GitPod.
Balsamiq
I used Balsamiq, the rapid low-fidelity UI wireframing tool during the prototyping phase to structure the website and its content following best UX practices.
Photoshop
I created the text segment of the company logo using the image graphics editor Photoshop so the website/company name would be visible to the user upon landing on the site.
Chrome Dev Tools
Chrome Dev Tools was used to consistently test the site and run reports from Lighthouse.
Google Fonts
Google Fonts was used to style the website fonts.
Font Awesome
I used the font & icon toolkit Font Awesome in the company section, artist Modals and footer links to define elements by a visual means.
TinyPNG
The TinyPNG website was used to originally reduce the file size of my image files to use less bandwidth and allow the website to load faster.
Freeformatter CSS Beautify
I used CSS Beautify to format and automatically indent my CSS file.
Freeformatter HTML Formatter
The HTML Formatter was used to format the HTML document.
Unicorn Revealer
I regularly used the Unicorn Revealer Chrome extension to inspect and locate where overflow was located making the debugging process a lot easier.
YouTube
For all my modal music video links, I used the video-sharing platform YouTube to visually showcase the artist and their genre to the user.
Favicon.io
Favicon.io was used to generate the favicons for the site.
Autoprefixer
The project used PostCSS plugin Autoprefixer which parsed my CSS and added vendor prefixes to allow cross-browser compatibility and support.
Color Contrast Accessibility Validator
The Color Contrast Accessibility Validator was used to test for colour contrast on the project.
W3C Markup Validation Service
The W3C Markup Validation Service checked the markup validity of Web documents in HTML.
W3C CSS Validation Service
W3C CSS Validation Service was used to check the validity of my CSS in the project.
WAVE Web Accessibility Evaluation Tool
I used WAVE to make my site more accessible to individuals with disabilities by detecting any potential issues.
Optimizilla Image Compressor
Optimizilla was used to further compress the images with custom compression options. alt text
Testing
UX stories testing
As a Venue Manager/ Ticketing Agent/ Artist/ Agent: I want to view the company information and experience

From first glance, there is an option in the navigation bar called "Who We Are" to learn more about the company. Also in the slider, there is a caption reading "Ireland's Leading Music Promoter" with a CTA displaying the text "Learn More About Us". Both links direct to the relevant section.

As a Venue Manager/ Ticketing Agent/ Artist/ Agent: I want to find out the artists the promoter works with

There is a clear direction in the navbar that to find out more info on the artists represented, the link for "Who We Represent" should be selected. Also in the carousel in the header, there is a caption "Artist-First Ethos" and a Call To Action button to "Check out our Artists". Both links direct to the correct section. The sub-heading text reads that the user can learn more by selecting a particular artist. Once selecting an artist, a pop up opens up to reveal a music video link, a short bio and links to the artist's social media and website.

As a Venue Manager/ Ticketing Agent/ Artist/ Agent: I want to check out their upcoming events.

At the top of the site, there is a link to events as well as a slider with an image and caption "Creating Memorable Events" and the CTA inviting the user to "Browse Our Events". Both links divert to the correct area. The sub-heading prompts the user to browse the current events. The slider can be selected by the left and right controls. The user can "Get Tickets" by clicking the link which brings them to a listing on an external ticketing site (tickets.ie) where the user can purchase tickets.

As a Venue Manager/ Ticketing Agent/ Artist/ Agent: I want to check out their social media channels

There are social media icons found in the footer which link to the company's channels.

As a Venue Manager/ Ticketing Agent/ Artist/ Agent: I want to contact the promoter about working together

There is a prominent button at the top of the page directing the user towards the contact form. The form does not allow the user to submit their enquiry until all fields are completed otherwise they will receive a prompt. This was achieved using the required attribute. There are also email and phone number contact details found in the footer which connect to the user's email service provider and keypad ready to dial.

Validation
I used the W3C Markup Validation Service to check the Markup and W3C CSS Validation Service to check the CSS validity of the site.

alt text

After fixing the errors on both testing sites, the site eventually passed the W3C Validation.

alt text

The Color Contrast Accessibility Validator was used to test for colour contrast on the project.

alt text

I found the original teal shade wasn't working from an Accessibility standpoint so I decided to change the colour to a darker shade to comply with Accessibility standards allowing no further colour contasting issues to be found on the site.

alt text

In order to have optimal user experience, the site needs to be accessible. I would continually run the URL through WAVE Web Accessibility Evaluation Tool to highlight potential issues. I continued until no further errors or alerts were given.

alt text

I constantly tested the code in Chrome Dev Tools and often ran Lighthouse audits to identify and fix issues that affected the site's performance, accessibility and user experience.

alt text

This would highlight areas that require improvement for validation. For example, performance issues pointed to large image files which would indicate further compression which I would implement with Optimizilla for custom compression. Also, a Cross-Origin security issue pertaining to Best Practices was simply resolved via adding rel= noreferrer to external links. Through constant testing, I was able to achieve over 90 on all metrics for optimum performance, accessibility and user experience.

alt text

All inbound site links with their hover functionality operate as expected and correctly navigate the user to the intended section and all external link open with target="_blank" to allow the user to return to the site conveniently and remember where they have navigated from. If the user clicks on the "Back to Top" link or the logo at any point it will bring them back to the top of the pages as intended.

I asked my family, friends and fellow students to test their site on different devices to locate potential bugs. The website was tested over multiple devices (iPhone 5, 6, 11: Safari and Chrome, iPad, Samsung Galaxy) and many browsers (Chrome, Firefox, Safari and Edge) to guarantee responsive behaviour and compatibility.

I came across several minor bugs or issues during development but the majority were easily fixed with assistance from Chrome Dev Tools and Unicorn Revealer to locate the source. However, one issue that took longer to solve was the audio issue on the Gallery Modal. When the user would play the video and then click close/off the Modal before the end of the video the audio would continue to play causing the user to reload the page to stop the audio. I was also having issues with the performace of the site due to iframes not dynamically loading. I spoke with my Mentor, Guido Cecilio, about both issues and he advised me on the use of JavaScript to solve the problem. He taught about which scripts I could use for the resolution of both issues which allowed me to dip my toes into another programming language!

Deployment
This site is hosted using GitHub pages, deployed directly from the master branch. The deployed site will update automatically upon new commits to the master branch. For the site to deploy correctly on GitHub pages, the landing page must be named index.html.

To run locally, you can clone this repository directly into the editor of your choice by pasting git clone https://natashaclerkin.github.io/singularartistsMS1 into your terminal. To cut ties with this GitHub repository, type git remote rm origin into the terminal.

My project was developed using the IDE, Gitpod. I deployed my website from the GitHub repository to GitHub Pages using the following steps:

I selected the Settings tab in my GitHub repository. alt text

I located the GitHub Pages section and chose the Master branch as the source to enable GitHub Pages. alt text

Once I saved the Master Branch as the source, the page refreshed and I located the URL to the deployed website. alt text

I then followed the link to observe and verify the published GitHub page. alt text

Credits
Content
The text for the About Section was adapted from:

the Nialler9 article
the Pollstar article
the IQ article
Media
The images used in this site were obtained from the following sources:

Singular Artists Company Logo - from Singular Artists' Facebook Page
Singular Artists Company Directors Image - from Pollstar
Dermot Kennedy Carousel Image - from Ambient Light
Picture This Carousel Image - from Golden Plec
Fontaines DC Carousel Image - from Pollstar
Fontaines DC Gallery Image - from The Face
Dermot Kennedy Gallery Image - from Irish Central
Picture This Gallery Image - from Official Charts
Sam Wickens Gallery & Event Listing Image - from Sam Wickens Twitter Account
Ailbhe Reddy Gallery & Event Listing Image - from Read Dork
Boy Pablo Gallery & Event Listing Image - from Teco Apple
Reevah Gallery & Event Listing Image - from XS Noise
Novo Amor Gallery & Event Listing Image - from Mr Life Day
Pillow Queens Gallery & Event Listing Image - from Giglist
Elderbrook Gallery & Event Listing Image - from Official Charts
Maija Sofia Gallery & Event Listing Image - from Strange Brew
Rhys Lewis Gallery & Event Listing Image - from The Evening Standard
Fontaines Gallery & Event Listing Image - from Pollstar
The video links used in this site were obtained from the following sources:

Fontaines DC Modal Video - from Youtube
Dermot Kennedy Modal Video - from Youtube
Picture This Modal Video - from Youtube
Sam Wickens Modal Video - from Youtube
Ailbhe Reddy Modal Video - from Youtube
Boy Pablo Modal Video - from Youtube
Reevah Modal Video - from Youtube
Novo Amor Modal Video - from Youtube
Pillow Queens Modal Video - from Youtube
Elderbrook Modal Video - from Youtube
Maija Sofia Modal Video - from Youtube
Rhys Lewis Modal Video - from Youtube
Acknowledgements
I decided to develop this project in honour of my real-life ticketing client, Singular Artists who have yet to set up their company website.

I took inspiration from the following sources however I did implement my own custom code with each snippet also:

Bootstrap was used to implement Scrollspy for the Navigation and the Contact Form
I came across MD Bootstrap when I was searching for inspiration for the Artists' Gallery Modal as well as the Event's Carousel
I found a code snippet for the Navbar and Carousel from Divenector
During development I found solutions to my coding queries in Stack Overflow when I had difficulties maintaining equal height in the Bootstrap Cards and when I wanted my carousel to take on a black and white effect.
In order to follow footer conventions, I wanted to take inspiration from Bootstraptor
Finally, I would like to thank Jim Morel on Slack for his assistance with the active link issue and of course my mentor Guido Cecilio for his JavaScript wisdom and overall support throughout the project.