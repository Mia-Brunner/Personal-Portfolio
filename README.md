# T1A3 Portfolio
_______

#### Published Porftolio Website:
https://modest-cray-86f927.netlify.com/index.html
#### GitHub Repository:
https://github.com/Mia-Brunner/Personal-Portfolio 
### Purpose 

The purpose of this assignment is to create a portfolio in the form of a website that can be used as a resource for potential employers during my job application process in the tech industry. This Portfolio provides a reference of my skills as a web developer, along with my work and study history. Unlike a generic resume, this portfolio will be able to portray my personality and interests through my choice of colours, aesthetics and styling throughout the website. This portfolio will also convey my current skillsets in creating a responsive website by using the tech stack of HTML and CSS. 

### Features/Functionality
##### 1. Responsive navigation using the 'burger' style drop-down menu
A responsive navigation menu was created to ensure ease of accessibility for smaller screens including tablets and phones. This was created using a media query for screens that are below the max width of 780px. This ensures that a burger style drop down menu will be created to adjust for both tablet and phone sizes. 
##### 2. Use of animations
I have applied the use of animations on both the Home page and About page. Blink-caret, a typewriter style animation was created for the welcome text in the home page which is also responsive to tablets and phones. 
For the about page, the use of fading animations were applied by setting delays on the opacity of 5 seperate texts over a specified time-frame to create a cinematic experience over the animation box. 
##### 3. Use of hover effects 
Hover effects were used throughout all pages of the website as it has been applied on the navigation menu and the list of icons on the left side of the screen linking to socials such as GitHub, LinkedIn and also the contact page on the website. These features are available on every page due to its fixed/static design.

A hover effect was also applied to the 'enter' and 'next page' buttons allowing users to access the following pages. These are available on the Home page and the About page. 

Another hover effect was added to the images found on the Skills page. This allowed the user to hover over the existing images to access additional information about work and study history. 

##### 4. Responsive website 
Media queries were applied throughout all the pages of the website to allow accessibility for users who are on tablets or phones. 

##### 5. Branch for dark-mode 
A second branch was created for dark-mode allowing for a contrast in concept and aesthetics from the original website. This allows users to navigate through the same original layout with minor differences of colour and images to assist with the concept of dark-mode.

The use of low saturated colours such as light greys were applied to all texts and icons to ease the readability for users. If a high contrast colour was applied such as a white over a black background, it would be too sharp for the eyes making it more difficult to read for longer periods of time. 

### Sitemap
![Sitemap](/docs/ReadMe-docs/Sitemap.png)

#### Home Page
The home page is purely meant as an introduction with an added welcome animation using blink-caret to entice the user to delve deeper into the website. A large image of a flower fills half of the body space setting the theme for the rest of the website. An 'enter' button eases accessibility and navigation into the rest of the website. The home page uses flex. 

#### About Page
The about me page follows the same theme of the home page with the use of similar pastel colours such as pinks and oranges. These provide a minimalist style further supporting the structure of the web page. 

The animation on the right hand side provides minimal explanation of who I am and my current interests, delving a little further gain a sense of my personailty. This page was also created using flex. 

#### Skills Page 

The skills page follows the minimalist and pastel styles and structures as previously seen in the other pages. Hover effects allows for increased user interaction towards the web page. Each hover over the images provided allows the user to gain a glimpse of my current skills as a web developer and further insight into my previous work history. 
Links to my mockup resume is also available on this page. 

The skills page used both a grids and flex to structure the page. The general layout of the page uses a grid with separate containers with varying sizes, colours, and contents. For each image flex was used to add the hover effects desired.

#### Contact Page

The contact page has a slightly different structure to the pages seen peviously but still follows the same styling towards pastel colours. This page uses a grid structure with a series of hover and click effects to add more depth to the elements within the contact section. 

#### Blog Page

The blog page features 6 latest posts with a relevant image provided for each article. All snippets allow users to see a glimpse of the article and it's contents. 

A read more button allows users to gain access to the posts provided. 

#### Articles Page 
The articles page is a separate page from the blog page and provides the full version of each article for the reader to view. The article is attached to the blog page with the use of the read more button. This button uses an anchor to link to each article within different parts of the page. 

Grid columns were used to create the articles page separating the sections vertically. 

#### Sidebar links

Sidebar links for my profiles in LinkedIn and GitHub are accessible on every page of the website. This is accompanied by another icon for contact which links to the contact page. This sidebar icons were retrieved from font awesome. 

### Wireframes
Each page of this website encompasses a similar layout due to the static header, footer and side bar. These allow each page to have a similar aesthetic and creates an easy flow from one page to another. Any changes were only conducted within the main body of the page. 

![wireframe](/docs/ReadMe-docs/Wireframe.png)

### Mood Board

From endlessley looking throughout pinterest for style ideas, I came up with the conclusion to follow a minimal structure using lighter colours at lower saturation levels to create an ethereal feel for the website. I originally saw the image below of the flower on a stem and instantly knew that I wanted to use these images colours and feel as the basis for my website. This image had to be on my home page. The majority of styling concepts was based around this image particularly the colour scheme. 

![mood-board](/docs/ReadMe-docs/moodboard.png)

### Screenshots

I originally started planning out my home page and concept without code to gain a general idea of the layout I wanted. I knew that I wanted a fixed navigation bar at the top, with my name on the left hand side linking back to the home page. The other menu items on the right hand side needed to have a minimal look and be able to convert to a burger menu for smaller screen sizes. Another component that I also wanted was the fixed side bar for icons which would remain there at all screen sizes. 

A style that I enjoyed seeing while I was exploring my options was having text over the images and not separated from them. This led me to look into CSS components such as negative margins and transform/translate structures so that I could go over the margins and into the next flex. 

![Screenshot of initial draft](/docs/screenshots/initial.png)

The image below shows all the fixed structures that I would have on every web page. 

![Screenshot of layout idea](/docs/screenshots/original-layout-idea.png)

This is the final screenshot of all my web pages. You can see a consistent theme throughout all pages as it uses the same components, text design and colours. This unifies the entire website and creates the effect of a clean and minimal style.

![Screenshots of master document](/docs/screenshots/pc-final-group.png)

These images are screenshots of the mobile version of my website. As you can see changes have been made to the layout such as the navigation bar being altered to a drop down burger menu. The side icons have a reduced left-side margin bringing it closer to the lefts side of the page. The Footer has also been removed as it's height would be large on a smaller scale such as mobile. 

![Screenshots of master document mobile version](/docs/screenshots/mobile-final-group.png)

The below images consist of my dark mode branch. The main changes to create this look are adjusting the colours to deep greys and blacks with contrasting text colours to achieve a minimal ans sleek design. Images and font styles have also been adjusted to reflect the mood of the website.

![Screenshots of dark-mode document](/docs/screenshots/pc-dark-mode.png)

These images below follows the concept of modern design for my second branch. I have altered the home page so that the main component is the background image which also follows through to the rest of the pages. As the background image consisted of numerous colours I had to create a background area for the text for it to be more visible. As a block background colour would reduce the impact of the background image I instead decided to reduce the transparency, allowing the image to be partially visible and also the text more defined. This also follows the dark mode theme with minor changes being made to its images. 

![Screenshots of modern-design document](/docs/screenshots/pc-modern-design.png)

### Target Audience
- The main target audience for this website would be for future employers as this acts as an online resume for me to share my skills as a web developer. 
- Another audience that I am trying to target would be the assessors of this assessment. 
- The final target audience is current or aspiring web developers. Once this website is completed and finalised in the near future I would love to use this porfolio as a form of inspiration for other aspiring students who wish to create their own portfolio based website.

### Tech Stack
- HTML-5
- CSS-3
- GitHub
- Netlify
