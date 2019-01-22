---


---

<h1 id="the-monkees-website">The Monkees Website</h1>
<p>This project displays my HTML and CSS capabilities. The project is a website site for the 1960’s rock band, The Monkees.<br>
The site covers a number of essential elements a rock band’s website should contain, enabling users to engage with the artist’s content. This content includes music video, a music player to listen to the band’s songs, various images of the band and has the option for purchasing concert tickets.<br>
The site also has the ability to showcase any up and coming music from the band and publicises their availability to perform at events such as weddings and Christmas parties, which can be booked through the website.</p>
<h1 id="ux">UX</h1>
<p>The intended users of the project are as follows:<br>
•	Users who are familiar with The Monkees looking to quickly find specific content they wish to engage with.<br>
•	Users who wish to learn more about The Monkees.<br>
•	Users who want to find the latest music of The Monkees.<br>
•	Users who wish to use the website on multiple platforms.</p>
<p>The project helps to satisfy each user group’s request; it does this through a number of ways, explained as follows:<br>
•	<strong>Users who are familiar with the band looking to quickly find specific content they wish to engage with</strong><br>
o	This user group may wish to listen to a song from the artist.<br>
o	The video offers the opportunity for users to see a music video of the band.<br>
o	The tour page is a great place to see where the band are performing live and indicates whether tickets are sold out or available in their city. The ticket purchasing information is also prominent for each location.<br>
•	<strong>Users who are aware of the band and do not have an extensive knowledge of their work, but wish to learn more about them</strong><br>
o	The Band page has a short history on the band. It also has a feature where if you click on each band member’s photo, it displays a pop up underneath stating what instrument they play.<br>
o	Links to social profiles are displayed in the footer on every page, helping users to learn more about the artist and engage with them on social media channels easily.<br>
o	The images of the band help users to visually engage with the band quickly.<br>
o	The carrousel on the Home page shows the user recent live shows the band has performed at.<br>
•	<strong>Users who want to find the latest music of The Monkees</strong><br>
o	Users will be visiting the site to see the band’s latest work; the media page is one example of how this desire is satisfied. Again, the carousel on the Home page shows images of the latest performances and also the Social Media links in the footer of every page will take the user to the latest news about the band.<br>
•	<strong>Users who wish to use the website on multiple platforms</strong><br>
o	The site is fully responsive so that all user groups may use the website.</p>
<p>Wireframes of the website’s pages can be found <a href="https://imgur.com/a/vOm5fUC">here</a></p>
<p>The following alterations were made after the mock-up phase:<br>
•	The removal of a scrolling website.<br>
•	Media page was added.<br>
•	Contact page was added.<br>
•	Changes to the style of the Tour page.<br>
•	The addition of the ticket modal.<br>
•	Changes to the layout of the Band page.</p>
<h2 id="features">Features</h2>
<p><strong>Existing Features</strong><br>
•	The carousel on the Home page displays photos taken of the band’s live performances, with the name of the City at the bottom.<br>
•	The carousel also has right and left indicators which are clickable, and when hovering over them, the hovered area changes color and the mouse icon changes to a pointer indicating to the user that they can click there.<br>
•	There are also 3 small circular tabs at the bottom of the carousel for the user to also use to select the different images.<br>
•	The hamburger menu appears when the resolution is less than 767px. It allows mobile users to browse the menu with ease.<br>
•	Footer and menu links change color on hover and the mouse icon changes to a pointer, informing users they can click there.<br>
•	Clicking the ‘Bookings for Weddings &amp; Parties’ button in the footer takes the user directly to the Contact page where they can fill out their enquiries.<br>
•	Email sign up and Send Request buttons return ‘This is a required Field’ message if the user presses the buttons without entering any information.<br>
•	Clicking the Social Media links in the Footer takes the user to the band’s Social Media pages.<br>
•	The Monkees logo in the top left-hand corner on every page is clickable. Clicking it takes the user back to the Home page. The cursor changes to pointer on hover.<br>
•	On the Band page, when you click on a band member’s picture a drop-down toggle appears informing the user what instrument each band member plays.<br>
•	On the Media page, iFrames allow the user to view a video directly on the page. The iFrame also allows users to select similar videos, play and pause, adjust settings, play full screen and share online.<br>
•	Also on the Media page, users are able to enjoy listening to the band’s Greatest Hits on the mp3 players.<br>
•	On the Tour page, users can click a button to buy tickets to available shows. Clicking the ‘Buy’ button enables a pop up modal where they can type in the amount of tickets they want to buy, enter their email address and then submit.<br>
•	A back to top button allows users to quickly navigate back to the top of the page for all pages. This is especially useful for mobile and tablet users.</p>
<p><strong>Features Left to Implement</strong><br>
•	Add additional images and create a gallery modal for users to navigate through.<br>
•	Enable users to play music through different means, such as Spotify and Apple Music. Or have one mp3 music player with the option to select a wide range of tracks to play.</p>
<h2 id="technologies-used">Technologies Used</h2>
<p>•	HTML<br>
•	CSS<br>
•	Bootstrap 3.3.7 library was used to aid development with its grid system, navigation menu and modals.<br>
•	Used Font Awesome icons for social media links.<br>
•	jQuery was used to aid the implementation of Bootstrap (e.g. the hamburger menu) and to assist in the ticketing modal.<br>
•	Google Fonts was used for the implementation of the font Montserrat.</p>
<h2 id="testing">Testing</h2>

<table>
<thead>
<tr>
<th>Test</th>
<th>Status</th>
</tr>
</thead>
<tbody>
<tr>
<td><strong>Desktop Menu</strong></td>
<td></td>
</tr>
<tr>
<td>Buttons react on hover</td>
<td>Successful</td>
</tr>
<tr>
<td>Buttons take users to respective page</td>
<td>Successful</td>
</tr>
<tr>
<td>Active page is visually clear</td>
<td>Successful</td>
</tr>
<tr>
<td><strong>Mobile Menu</strong></td>
<td></td>
</tr>
<tr>
<td>Mobile menu appears on screen widths 767px and below</td>
<td>Successful</td>
</tr>
<tr>
<td>Menu appears after selecting burger icon</td>
<td>Successful</td>
</tr>
<tr>
<td>Menu closes after selecting burger icon</td>
<td>Successful</td>
</tr>
<tr>
<td><strong>Footer</strong></td>
<td></td>
</tr>
<tr>
<td>Footer links take users to respective site</td>
<td>Successful</td>
</tr>
<tr>
<td>Footer links change colour when hovered on</td>
<td>Successful</td>
</tr>
<tr>
<td>Mailing list Submit, Bookings Button and Social Media links on Footer, stack when resolution is 767px and below</td>
<td>Successful</td>
</tr>
<tr>
<td>Try to submit an empty Mailing List form and verify a relevant error appears</td>
<td>Successful</td>
</tr>
<tr>
<td><strong>Video</strong></td>
<td></td>
</tr>
<tr>
<td>Featured video playable and has full YouTube Functionality</td>
<td>Successful</td>
</tr>
<tr>
<td>Video highlights play icon on hover</td>
<td>Successful</td>
</tr>
<tr>
<td>Video is responsive to different screen resolutions</td>
<td>Successful</td>
</tr>
<tr>
<td><strong>Images</strong></td>
<td></td>
</tr>
<tr>
<td>All images load</td>
<td>Successful</td>
</tr>
<tr>
<td>Images take up one column on Media page when screen widths are 767px and below</td>
<td>Successful</td>
</tr>
<tr>
<td>When clicking band member images on Band page, toggle shows band members instrument played</td>
<td>Successful</td>
</tr>
<tr>
<td>All band images have rounded corners</td>
<td>Successful</td>
</tr>
<tr>
<td>The text on the Carousel disappears on screen widths 600px and below</td>
<td>Successful</td>
</tr>
<tr>
<td>Carousel is responsive to different screen resolutions</td>
<td>Successful</td>
</tr>
<tr>
<td><strong>Tour Page</strong></td>
<td></td>
</tr>
<tr>
<td>Selecting ‘Buy now’ opens up ticket modal</td>
<td>Successful</td>
</tr>
<tr>
<td>Ticket counter increasing and decreasing the amount of tickets, works in ticket modal</td>
<td>Successful</td>
</tr>
<tr>
<td>Ticket modal is responsive to different screen resolutions</td>
<td>Successful</td>
</tr>
<tr>
<td>Ticket Locations stack when screen widths are 767px and below</td>
<td>Successful</td>
</tr>
<tr>
<td><strong>Contact page</strong></td>
<td></td>
</tr>
<tr>
<td>Error message appears when summit is pressed without any information in all fields</td>
<td>Successful</td>
</tr>
<tr>
<td><strong>Back to Top</strong></td>
<td></td>
</tr>
<tr>
<td>Back to top button stays in fixed location on scroll</td>
<td>Successful</td>
</tr>
<tr>
<td>When selected, back to top button takes users to top of page</td>
<td>Successful</td>
</tr>
</tbody>
</table><h2 id="deployment">Deployment</h2>
<p>Project has been deployed to GitHub Pages and is accessible <a href="https://richdevelopments.github.io/bandwebsite/">here</a><br>
The process for deployment was as follows:<br>
•	Project pushed to GitHub repository<br>
•	Navigated to Settings in relevant GitHub repository<br>
•	Under GitHub Pages, selected relevant branch (master branch) and saved</p>
<h2 id="credits">Credits</h2>
<p>•	Ticket modal is Bootstrap and jQuery<br>
•	Responsive embedded video help provided by <a href="https://themeskills.com/">https://themeskills.com/</a> - I needed to add in/change part of the code to ?start=20, for the video to start 20 seconds in. This was to cut out a big blank gap at the start of the video.<br>
•	Carousel was made with the help of <a href="http://www.w3schools.com">www.w3schools.com</a>.<br>
•	Mp3 players were made with the help of <a href="http://www.w3schools.com">www.w3schools.com</a>.</p>
<h2 id="media">Media</h2>
<p>•	Music mp3’s are from the material provided in the milestone project brief.<br>
•	Video shared from the official YouTube channel of The Monkees (WMG (on behalf of Rhino (Pure)); UBEM, SOLAR Music Rights Management, CMRRA, EMI Music Publishing, and 7 music rights societies.<br>
•	Image content provided by:<br>
o	Band page background photo is a still from the closing title sequence of the TV series ‘The Monkees’ [Credit: Columbia Pictures Television]<br>
o	Band pictures from material provided in the milestone project brief.<br>
o	Tour page, Media page and Contact page background pictures and also the location pictures on Tour page are all ‘free to use images’ from google search.</p>
<h2 id="disclaimer">Disclaimer</h2>
<p>This is for educational purposes only.</p>

