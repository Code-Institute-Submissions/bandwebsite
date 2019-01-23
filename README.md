# The Monkees Website

This project displays my HTML and CSS capabilities. The project is a website site for the 1960’s rock band, The Monkees.
The site covers a number of essential elements a rock band’s website should contain, enabling users to engage with the artist's content. This content includes music video, a music player to listen to the band’s songs, various images of the band and has the option for purchasing concert tickets. 
The site also has the ability to showcase any up and coming music from the band and publicises their availability to perform at events such as weddings and Christmas parties, which can be booked through the website.


# UX

The intended users of the project are as follows:
•	Users who are familiar with The Monkees looking to quickly find specific content they wish to engage with.
•	Users who wish to learn more about The Monkees. 
•	Users who want to find the latest music of The Monkees.
•	Users who wish to use the website on multiple platforms.

The project helps to satisfy each user group's request; it does this through a number of ways, explained as follows:
•	**Users who are familiar with the band looking to quickly find specific content they wish to engage with**
  o	This user group may wish to listen to a song from the artist.
  o	The video offers the opportunity for users to see a music video of the band.
  o	The tour page is a great place to see where the band are performing live and indicates whether tickets are sold out or available in their city. The ticket purchasing information is also prominent for each location.
•	**Users who are aware of the band and do not have an extensive knowledge of their work, but wish to learn more about them**
  o	The Band page has a short history on the band. It also has a feature where if you click on each band member’s photo, it displays a pop up underneath stating what instrument they play.
  o	Links to social profiles are displayed in the footer on every page, helping users to learn more about the artist and engage with them on social media channels easily.
  o	The images of the band help users to visually engage with the band quickly.
  o	The carrousel on the Home page shows the user recent live shows the band has performed at. 
•	**Users who want to find the latest music of The Monkees**
  o	Users will be visiting the site to see the band's latest work; the media page is one example of how this desire is satisfied. Again, the carousel on the Home page shows images of the latest performances and also the Social Media links in the footer of every page will take the user to the latest news about the band.
•	**Users who wish to use the website on multiple platforms**
  o	The site is fully responsive so that all user groups may use the website.
  
Wireframes of the website’s pages can be found [here](https://imgur.com/a/vOm5fUC)

 The following alterations were made after the mock-up phase:
•	The removal of a scrolling website.
•	Media page was added.
•	Contact page was added.
•	Changes to the style of the Tour page.
•	The addition of the ticket modal.
•	Changes to the layout of the Band page.

## Features

**Existing Features**
•	The carousel on the Home page displays photos taken of the band’s live performances, with the name of the City at the bottom.
•	The carousel also has right and left indicators which are clickable, and when hovering over them, the hovered area changes color and the mouse icon changes to a pointer indicating to the user that they can click there.
•	There are also 3 small circular tabs at the bottom of the carousel for the user to also use to select the different images.
•	The hamburger menu appears when the resolution is less than 767px. It allows mobile users to browse the menu with ease.
•	Footer and menu links change color on hover and the mouse icon changes to a pointer, informing users they can click there.
•	Clicking the ‘Bookings for Weddings & Parties’ button in the footer takes the user directly to the Contact page where they can fill out their enquiries.
•	Email sign up and Send Request buttons return ‘This is a required Field’ message if the user presses the buttons without entering any information.
•	Clicking the Social Media links in the Footer takes the user to the band’s Social Media pages.
•	The Monkees logo in the top left-hand corner on every page is clickable. Clicking it takes the user back to the Home page. The cursor changes to pointer on hover.
•	On the Band page, when you click on a band member’s picture a drop-down toggle appears informing the user what instrument each band member plays.
•	On the Media page, view a video directly on the page. 
•	Also on the Media page, users are able to enjoy listening to the band’s Greatest Hits on the mp3 players.
•	On the Tour page, users can click a button to buy tickets to available shows. Clicking the ‘Buy’ button enables a pop up modal where they can type in the amount of tickets they want to buy, enter their email address and then submit.
•	A back to top button allows users to quickly navigate back to the top of the page for all pages. This is especially useful for mobile and tablet users.

**Features Left to Implement**
•	Add additional images and create a gallery modal for users to navigate through.
•	Enable users to play music through different means, such as Spotify and Apple Music. Or have one mp3 music player with the option to select a wide range of tracks to play.

## Technologies Used

•	HTML
•	CSS
•	Bootstrap 3.3.7 library was used to aid development with its grid system, navigation menu and modals.
•	Used Font Awesome icons for social media links.
•	jQuery was used to aid the implementation of Bootstrap (e.g. the hamburger menu) and to assist in the ticketing modal.
•	Google Fonts was used for the implementation of the font Montserrat.

## Testing

|Test| Status |
|----|--|
 **Desktop Menu**   |
|Buttons react on hover| Successful|
|Buttons take users to respective page| Successful
|Active page is visually clear| Successful
|**Mobile Menu**	
|Mobile menu appears on screen widths 767px and below| Successful
|Menu appears after selecting burger icon| Successful
|Menu closes after selecting burger icon| Successful
|**Footer**
|Footer links take users to respective site| Successful
|Footer links change colour when hovered on| Successful
|Mailing list Submit, Bookings Button and Social Media links on Footer, stack when resolution is 767px and below| Successful
|Try to submit an empty Mailing List form and verify a relevant error appears| Successful
|**Video**
|Featured video playable and has full functionality| Successful
|
|Video is responsive to different screen resolutions| Successful
|**Images**	
|All images load| Successful
|Images take up one column on Media page when screen widths are 767px and below| Successful
|When clicking band member images on Band page, toggle shows band members instrument played| Successful
|All band images have rounded corners| Successful
|The text on the Carousel disappears on screen widths 600px and below| Successful
|Carousel is responsive to different screen resolutions| Successful
|**Tour Page**
|Selecting 'Buy now' opens up ticket modal| Successful
|Ticket counter increasing and decreasing the amount of tickets, works in ticket modal| Successful
|Ticket modal is responsive to different screen resolutions| Successful
|Ticket Locations stack when screen widths are 767px and below| Successful
|**Contact page**
|Error message appears when summit is pressed without any information in all fields| Successful
|**Back to Top**
|Back to top button stays in fixed location on scroll| Successful
|When selected, back to top button takes users to top of page| Successful


## Deployment

Project has been deployed to GitHub Pages and is accessible [here](https://richdevelopments.github.io/bandwebsite/) 
The process for deployment was as follows:
•	Project pushed to GitHub repository
•	Navigated to Settings in relevant GitHub repository
•	Under GitHub Pages, selected relevant branch (master branch) and saved

## Credits

•	Ticket modal is Bootstrap and jQuery
•	Responsive embedded video help provided by https://themeskills.com/ - I needed to add in/change part of the code to ?start=20, for the video to start 20 seconds in. This was to cut out a big blank gap at the start of the video.
•	Carousel was made with the help of www.w3schools.com.
•	Mp3 players were made with the help of www.w3schools.com.


## Media

•	Music mp3’s are from the material provided in the milestone project brief.
•	Video shared from the official YouTube channel of The Monkees (WMG (on behalf of Rhino (Pure)); UBEM, SOLAR Music Rights Management, CMRRA, EMI Music Publishing, and 7 music rights societies.
•	Image content provided by: 
o	Band page background photo is a still from the closing title sequence of the TV series 'The Monkees' [Credit: Columbia Pictures Television] 
o	Band pictures from material provided in the milestone project brief.
o	Tour page, Media page and Contact page background pictures and also the location pictures on Tour page are all ‘free to use images’ from google search.

## Disclaimer

This is for educational purposes only.


