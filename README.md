# Your Own Money Investments
<b>Problem Statement</b><br>
People shy away from managing their own money even though it is well known that a lot of the investment fund managers only
get paid if the money is invested, which leaves the owner of the money in a very risky situation.
<br><br>
<b>Proposed Solution</b><br>
<i>Your own money investments</i> is a website aimed at surfacing educational opportunities to people 
in the form of a) recommended reading, b) podcast recommendations, and c) a trading ideas blog managed and written by the website owner. 
It also encourages people to develop their knowledge about the field at their own pace, over time.

## UX
The user experience for the website is aimed at collating pre-vetted recommendations for kindle books and for podcasts, with the extra addition of the 'trade ideas' blog which 
encourages users to come back to the website for the newest entries on the blog.

<b>User Story 1: Be Inspired</b><br>
- As a new user that has stumbled accross this website, they agree with the 'call to action' on the index.html page which tells the user to
'Learn - How to grow your own money safely' and the user identifies with the second statement, that they will never increase their wealth significantly
by just working a normal job. They are inspired to look for more information on the website.<br><br>

<b>User Story 2: Looking for quick book recommendations</b><br>
- As a new or experienced user, the user clicks the 'reading' button if they are on a wide screen device or on the 'start here' drop down button which reveals the 'reading' section on a narrower screen device such as a phone, this 
allows the user to see the latest recommendations for investment books.<br><br>

<b>User Story 3: Looking for quick podcast recommendations</b><br>
- As a new or experienced user, the user clicks the 'podcasts' button if they are on a wide screen device or on the 'start here' drop down button which reveals the 'podcasts' section on a narrower screen device such as a phone, this 
allows the user to see the latest recommendations for investment podcasts.<br><br>

<b>User Story 4: Looking for quick and easy trading ideas</b><br>
- As a new or experienced user, the user clicks the 'trade ideas' botton if they are on a wide screen device or on the 'start here' drop down button which reveals the 'trade ideas' section on a narrower screen device such as a phone, this 
allows the user to see the latest trade ideas that are published on the website. The user is interested in these trade ideas the most, as it is the most frequently updated content on the website, and from where they are getting trading insights from, over-time. The user checks back more frequently over time as he develops a trust with the
author.<br><br>

<b>User Story 5: User has a more specific question and wants to contact the website owner</b><br>
- As a new or experienced user, the user clicks the 'Contact Us' button if they are on a wide screen device or on the 'start here' drop down button which reveals the 'trade ideas' section on a narrower screen device such as a phone, this 
allows the user to see the latest trade ideas that are published on the website. The user is interested in these trade ideas the most as it is the main portion of the website content that keeps getting updated and that they are getting trading insights from over time. The user checks back more frequently over time as he develops a trust with the
author.<br><br>


## Features
1) <b>Recommended Reading Section</b><br><br> 
Users are able to look through a collection of books regarding investing and trading. There are so many poorly written books on investing that these recommendations cut through the noise and give them a place to start learning about the subject.

2) <b>Recommended Podcasts Section</b><br><br> 
Users are able to look through a collection of podcasts regarding investing and trading. The podcasts chosen cover specific categories and themes in order to give the user a wider view and a more diverse range of opinions from the trading and investing world.

3) <b>Trade Ideas Section</b><br><br> 
Users are able to look through trade ideas blog entries that allows them to get a feel for how the website owner thinks through his trading strategy and what attributes & signals may influence his trading decisions. There is also a useful <b> quick-links</b> section in the top left of the page, which allows the user to get quick access to the 'yahoo finance',
'trading view', 'morningstar', and 'tastyworks' websites.

4) <b>Contact Us Section</b><br><br> 
Users are able to learn a bit about the website owner and also are able to contact him through a form that a) categorises what their question is about, b) ask their question in the text field and then c) submit their question pressing the submit button. (this is just the static version of this and is not operational yet in terms of actually sending the information anywhere.)


###Future Feature Ideas
- I had an idea for using iframes to display the information from different websites on another page as a tool; For example you could have yahoo finance, trading view, and tastyworks open on the same website page. They don't support iframes though so I would probably try and scrape the information using beautifulsoup and python at a later stage.
- The quick-links section was originally on every page but then I decided against this because it actually encourages people to leave the website. I left it in on the trading ideas page as it becomes useful as a lot of the information on the page would be directly from those websites. Once there are multiple posts on the 'trade ideas' blog it might be worth making the icon links specific to the stock ticker from the post and having multiple of these quick-links icon groups. 
- Once there are more posts on the trade ideas page it might be worth implementing some of the bootstrap pagenation features to focus the users attention more, rather than them scrolling down for a long time to find the section they want and getting disctracted by the passing-other-posts.


## Technologies Used

- [Bootstrap](https://getbootstrap.com/)
    - The project uses **Bootstrap** to speed up the HTML and CSS work.
        - <b>Buttons:</b> https://getbootstrap.com/docs/4.4/components/buttons/
        - <b>Dropdowns:</b> https://getbootstrap.com/docs/4.4/components/dropdowns/
        - <b>Navbar:</b> https://getbootstrap.com/docs/4.4/components/navbar/
        - <b>Typography:</b> https://getbootstrap.com/docs/4.4/content/typography/
        - <b>Grid:</b> https://getbootstrap.com/docs/4.4/layout/grid/

- [Font Awesome](https://fontawesome.com/)
        - 'fa fa-graduation-cap'
        - 'fa fa-facebook'
        - 'fa fa-twitter'
        - 'fa fa-instagram'

- [Google Fonts](https://fonts.google.com/)
        - I used archivo as this website is a little bit like an archive of recommended content and ideas. It looks very strong and clean as well as a font.


    - [CSS](https://cssreference.io/)
        - <b>font-family:</b> for choosing the font.
        - <b>text-transform:</b> to use uppercase function.
        - <b>text-align:</b> to align the text especially justify for the centered text.
        - <b>background:</b> for adding in the background picture urls.
        - <b>background-position:</b> for background picture positioning.
        - <b>background-size:</b> Used cover to make sure that the background does not run out of picture and shows white space too much.
        - <b>background-repeat:</b> Put in no-repeat for having the background picture not repeating.
        - <b>height:</b> For sizing the images and playing around with the background image sizes as well.
        - <b>width:</b> For sizing the images and playing around with the background image sizes as well.
        - <b>padding:</b> For making sure all of the text and html components have enough space in terms of design so it does not look cramped.
        - <b>background-blend-mode:</b> I came across this one by chance on w3schools but I used it to make the background image 'lighten' so the text would show up better.
        - <b>color:</b> for text colouring and the colouring of the fa icon.
        - <b>background-color:</b> for creating little boxes (including opacity) to make the text show up better on the background image.
        - <b>font-weight:</b> To make the text easier to read.
        - <b>position:</b> for positioning
        - <b>border-radius:</b> for making oval backgrounds for the buttons and for some of the boxes that I put text into.
        - <b>display:</b> controlling and centering items as blocks.
        - <b>margin:</b> (left,right, top, bottom) for creating space between components and text.





## Testing
<b>Testing Summary</b><br>
Since this is a static website it only requires very basic testing. I tested all of the links and made sure that they all work and ended up replacing the backround pictures that were in jpg format and converting them to png so they would load faster. There is a lot of white space
on the bottom of the ipad view for index.html; I tried putting another picture underneath the main content on that page but then it looked too busy and took the focus away from the statements and the social links so I removed the other picture again. The website works very clean on mobiles and the space to the right on wider views is very comforting and I made sure to choose appropriate
background pictures that had the focus of the picture on the right of the picture which then worked well with the website.


1. <b>User Story 1:</b> Be Inspired: index.html page.
    1. Try to read all of the text on the index page and make sure that the text looks strong. - Success
    2. The background image now loads faster as I replaced the jpg files with the converted png files. - Success
    3. Try the 'Your Own Money Investments' link in the logo  - Success
    4. Try the 'Reading' button and hover-over response in the navbar. - Success
    5. Try the 'Podcasts' button and hover-over response in the navbar. - Success
    6. Try the 'Trade Ideas' button and hover-over response in the navbar. - Success
    7. Try the 'Contact Us' button and hover-over response in the navbar. - Success
    8. Try the 'Reading' button and hover-over response in the dropdown menu for narrower screens. - Success
    9. Try the 'Podcasts' button and hover-over response in the dropdown menu for narrower screens. - Success
    10. Try the 'Trade Ideas' button and hover-over response in the dropdown menu for narrower screens. - Success
    11. Try the 'Contact Us' button and hover-over response in the dropdown menu for narrower screens. - Success
    12. Try the 'facebook' icon & link, and hover-over response in the social links at the bottom of the page. - Success
    13. Try the 'twitter' icon & link, and hover-over response in the social links at the bottom of the page. - Success
    14. Try the 'instagram' icon & link, and hover-over response in the social links at the bottom of the page. - Success
    15. Check the index.html page in responsinator:<a href="https://www.responsinator.com/?url=https%3A%2F%2Fsammckenna1986.github.io%2Fmilestone_project_1-static_frontend%2Findex.html"></a>
        - iPhone eXpensive portrait · width: 375px - Success
        - iPhone eXpensive landscape · width: 734px - Success
        - Android (Pixel 2) portrait · width: 412px - Success
        - Android (Pixel 2) landscape · width: 684px - Success
        - iPhone 6-8 portrait · width: 375px - Success
        - iPhone 6-8 landscape · width: 667px - Success
        - iPhone 6-8 Plump portrait · width: 414px - Success
        - iPhone 6-8 Plump landscape · width: 736px - Success
        - iPad portrait · width: 768px - Success (1. There is a lot of white space at the bottom but I am actually fine with it as it draws the eye more towards the social links and it is unusual so it does not have the 'wall paper' effect on people. 2. I tried another picture underneat but it looked too busy.)
        - iPad landscape · width: 1024px - Success (1. There is a lot of white space at the bottom but I am actually fine with it as it draws the eye more towards the social links and it is unusual so it does not have the 'wall paper' effect on people. 2. I tried another picture underneat but it looked too busy.)
    
2. <b>User Story 2:</b> Looking for quick book recommendations: reading.html page.
    1. Try to read all of the text on the 'reading' page, make sure that the information is correct, and make sure that the text looks strong. - Success
    2. The background image now loads faster as I replaced the jpg files with the converted png files. - Success
    3. Try the 'Your Own Money Investments' link in the logo  - Success
    4. Try the 'Reading' button and hover-over response in the navbar. - Success
    5. Try the 'Podcasts' button and hover-over response in the navbar. - Success
    6. Try the 'Trade Ideas' button and hover-over response in the navbar. - Success
    7. Try the 'Contact Us' button and hover-over response in the navbar. - Success
    8. Try the 'Reading' button and hover-over response in the dropdown menu for narrower screens. - Success
    9. Try the 'Podcasts' button and hover-over response in the dropdown menu for narrower screens. - Success
    10. Try the 'Trade Ideas' button and hover-over response in the dropdown menu for narrower screens. - Success
    11. Try the 'Contact Us' button and hover-over response in the dropdown menu for narrower screens. - Success
    12. Try the 'facebook' icon & link, and hover-over response in the social links at the bottom of the page. - Success
    13. Try the 'twitter' icon & link, and hover-over response in the social links at the bottom of the page. - Success
    14. Try the 'instagram' icon & link, and hover-over response in the social links at the bottom of the page. - Success
    15. Try the 'One Good Trade' link in the book title, and hover-over response in the books section. - Success
    16. Try the 'Market Wizards' link in the book title, and hover-over response in the books section. - Success
    17. Try the 'How I Made $2,000,000 in the Stock Market' link in the book title, and hover-over response in the books section. - Success
    18. Try the 'Top 10 Trading Setups' link in the book title, and hover-over response in the books section. - Success
    19. Check the index.html page in responsinator: <a href="https://www.responsinator.com/?url=https%3A%2F%2Fsammckenna1986.github.io%2Fmilestone_project_1-static_frontend%2Freading.html"></a>
    - iPhone eXpensive portrait · width: 375px - Success
    - iPhone eXpensive landscape · width: 734px - Success
    - Android (Pixel 2) portrait · width: 412px - Success
    - Android (Pixel 2) landscape · width: 684px - Success
    - iPhone 6-8 portrait · width: 375px - Success
    - iPhone 6-8 landscape · width: 667px - Success
    - iPhone 6-8 Plump portrait · width: 414px - Success
    - iPhone 6-8 Plump landscape · width: 736px - Success
    - iPad portrait · width: 768px - Success (ipad looks great)
    - iPad landscape · width: 1024px - Success (ipad looks great)


3. <b>User Story 3:</b> Looking for quick podcast recommendations: podcasts.html page.
    1. Try to read all of the text on the 'podcasts' page, make sure that the information is correct, and make sure that the text looks strong. - Success
    2. The background image now loads faster as I replaced the jpg files with the converted png files. - Success
    3. Try the 'Your Own Money Investments' link in the logo  - Success
    4. Try the 'Reading' button and hover-over response in the navbar. - Success
    5. Try the 'Podcasts' button and hover-over response in the navbar. - Success
    6. Try the 'Trade Ideas' button and hover-over response in the navbar. - Success
    7. Try the 'Contact Us' button and hover-over response in the navbar. - Success
    8. Try the 'Reading' button and hover-over response in the dropdown menu for narrower screens. - Success
    9. Try the 'Podcasts' button and hover-over response in the dropdown menu for narrower screens. - Success
    10. Try the 'Trade Ideas' button and hover-over response in the dropdown menu for narrower screens. - Success
    11. Try the 'Contact Us' button and hover-over response in the dropdown menu for narrower screens. - Success
    12. Try the 'facebook' icon & link, and hover-over response in the social links at the bottom of the page. - Success
    13. Try the 'twitter' icon & link, and hover-over response in the social links at the bottom of the page. - Success
    14. Try the 'instagram' icon & link, and hover-over response in the social links at the bottom of the page. - Success
    15. Try the 'Chat with Traders' link in the podcast title, and hover-over response in the podcasts section. - Success
    16. Try the 'The Investors Podcast' link in the podcast title, and hover-over response in the podcasts section. - Success
    17. Try the 'Macro Voices' link in the podcast title, and hover-over response in the podcasts section. - Success
    18. Try the 'Top Traders Unplugged' link in the podcast title, and hover-over response in the podcasts section. - Success
    19. Check the podcasts.html page in responsinator: <a href="https://www.responsinator.com/?url=https%3A%2F%2Fsammckenna1986.github.io%2Fmilestone_project_1-static_frontend%2Fpodcasts.html"></a>
    - iPhone eXpensive portrait · width: 375px - Success
    - iPhone eXpensive landscape · width: 734px - Success
    - Android (Pixel 2) portrait · width: 412px - Success
    - Android (Pixel 2) landscape · width: 684px - Success
    - iPhone 6-8 portrait · width: 375px - Success
    - iPhone 6-8 landscape · width: 667px - Success
    - iPhone 6-8 Plump portrait · width: 414px - Success
    - iPhone 6-8 Plump landscape · width: 736px - Success
    - iPad portrait · width: 768px - Success (ipad looks great)
    - iPad landscape · width: 1024px - Success (ipad looks great)
    
4. <b>User Story 4:</b> Looking for quick and easy trading ideas: tradeideas.html page.
    1. Try to read all of the text on the 'trade ideas' page, make sure that the information is correct, and make sure that the text looks strong. - Success
    2. The background image now loads faster as I replaced the jpg files with the converted png files. - Success
    3. Try the 'Your Own Money Investments' link in the logo  - Success
    4. Try the 'Reading' button and hover-over response in the navbar. - Success
    5. Try the 'Podcasts' button and hover-over response in the navbar. - Success
    6. Try the 'Trade Ideas' button and hover-over response in the navbar. - Success
    7. Try the 'Contact Us' button and hover-over response in the navbar. - Success
    8. Try the 'Reading' button and hover-over response in the dropdown menu for narrower screens. - Success
    9. Try the 'Podcasts' button and hover-over response in the dropdown menu for narrower screens. - Success
    10. Try the 'Trade Ideas' button and hover-over response in the dropdown menu for narrower screens. - Success
    11. Try the 'Contact Us' button and hover-over response in the dropdown menu for narrower screens. - Success
    12. Try the 'facebook' icon & link, and hover-over response in the social links at the bottom of the page. - Success
    13. Try the 'twitter' icon & link, and hover-over response in the social links at the bottom of the page. - Success
    14. Try the 'instagram' icon & link, and hover-over response in the social links at the bottom of the page. - Success
    15. Try the 'yahoo finance' icon & link, and hover-over response in the social links at the top of the page. - Success
    16. Try the 'trading view' icon & link, and hover-over response in the social links at the top of the page. - Success
    17. Try the 'morningstar' icon & link, and hover-over response in the social links at the top of the page. - Success
    18. Try the 'tastytrade' icon & link in the social links at the top of the page. - Success
    19. Make sure all of the information in the 'trading view' chart is readable on wide screen and on narrow screens. - Success
    20. Make sure all of the information in the 'income statement' is readable on wide screen and on narrow screens. - Success
    21. Make sure all of the information in the 'liabilities section of the balance sheet' is readable on wide screen and on narrow screens. - Success
    22. Make sure all of the information in the 'cashflow sheet' is readable on wide screen and on narrow screens. - Success
    23. Check the tradeideas.html page in responsinator:<a href="https://www.responsinator.com/?url=https%3A%2F%2Fsammckenna1986.github.io%2Fmilestone_project_1-static_frontend%2Ftradeideas.html"></a> 
    - iPhone eXpensive portrait · width: 375px - Success
    - iPhone eXpensive landscape · width: 734px - Success
    - Android (Pixel 2) portrait · width: 412px - Success
    - Android (Pixel 2) landscape · width: 684px - Success
    - iPhone 6-8 portrait · width: 375px - Success
    - iPhone 6-8 landscape · width: 667px - Success
    - iPhone 6-8 Plump portrait · width: 414px - Success
    - iPhone 6-8 Plump landscape · width: 736px - Success
    - iPad portrait · width: 768px - Success 

5. <b>User Story 5:</b> User has a more specific question and wants to contact the website owner: contact_us.html page.
    1. Try to read all of the text on the 'contact us' page, make sure that the information is correct, and make sure that the text looks strong. - Success
    2. The background image now loads faster as I replaced the jpg files with the converted png files. - Success
    3. Try the 'Your Own Money Investments' link in the logo  - Success
    4. Try the 'Reading' button and hover-over response in the navbar. - Success
    5. Try the 'Podcasts' button and hover-over response in the navbar. - Success
    6. Try the 'Trade Ideas' button and hover-over response in the navbar. - Success
    7. Try the 'Contact Us' button and hover-over response in the navbar. - Success
    8. Try the 'Reading' button and hover-over response in the dropdown menu for narrower screens. - Success
    9. Try the 'Podcasts' button and hover-over response in the dropdown menu for narrower screens. - Success
    10. Try the 'Trade Ideas' button and hover-over response in the dropdown menu for narrower screens. - Success
    11. Try the 'Contact Us' button and hover-over response in the dropdown menu for narrower screens. - Success
    12. Try the 'facebook' icon & link, and hover-over response in the social links at the bottom of the page. - Success
    13. Try the 'twitter' icon & link, and hover-over response in the social links at the bottom of the page. - Success
    14. Try the 'instagram' icon & link, and hover-over response in the social links at the bottom of the page. - Success
    15. Try typing into the 'Email Address' field - Success
    16. Try picking all options: 'Particular Stock', 'Strategy', 'Position Sizing', 'Entering a Trade', 'Exiting a Trade' from the 'Question Subject' dropdown menu. - Success
    17. Try typing into the 'Question' field. - Success
    18. Try hovering over the 'Submit' button - Success (the full functinality of this form is out of scope for this static website project)
    19. Check the contact_us.html page in responsinator: <a href="https://www.responsinator.com/?url=https%3A%2F%2Fsammckenna1986.github.io%2Fmilestone_project_1-static_frontend%2Fcontact_us.html">Link</a>
    - iPhone eXpensive portrait · width: 375px - Success
    - iPhone eXpensive landscape · width: 734px - Success
    - Android (Pixel 2) portrait · width: 412px - Success
    - Android (Pixel 2) landscape · width: 684px - Success
    - iPhone 6-8 portrait · width: 375px - Success
    - iPhone 6-8 landscape · width: 667px - Success
    - iPhone 6-8 Plump portrait · width: 414px - Success
    - iPhone 6-8 Plump landscape · width: 736px - Success
    - iPad portrait · width: 768px - Success 
    - iPad landscape · width: 1024px - Success 


## Deployment

This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub Pages or Heroku).

In particular, you should provide all details of the differences between the deployed version and the development version, if any, including:
- I deployed the website on github pages: <a href="https://sammckenna1986.github.io/milestone_project_1-static_frontend/index.html">Link</a>



## Credits
- Thank you to Antonio Rodriguez my mentor who's two meetings on this project were excellent and helped me understand a few concepts that I was missing.
- Thank you to Neil Kavanagh for clarifying a few concepts on the phone and for providing some extra motivation.
- Thank you to all the teachers on the course; The videos and excercises were excellent.

### Content and Media
- I wrote all of my own content.
- 'Balance sheet', 'cashflow sheet', and 'income statement' on the 'trade ideas' page were screenshotted from <a href="https://finance.yahoo.com/quote/WTI/balance-sheet?p=WTI">Yahoo Finance</a>
- The links and incon images for the books were taken from amazon.com
- The podcast icon images came from google images and from the podcast websites themselves.
- The pictures were copyright free and were downloaded from https://pixabay.com/.


### Acknowledgements

- I received inspiration for this project from my friends who are always asking me for suggestions on how they can start investing and trading. 

<b>I got a lot of information and inspiration for code from the following links:</b><br><br>
<a href="https://designshack.net/articles/trends/best-website-color-schemes/">https://designshack.net/articles/trends/best-website-color-schemes/</a>

<a href="https://www.pexels.com/photo/apple-devices-books-business-coffee-572056/">https://www.pexels.com/photo/apple-devices-books-business-coffee-572056/</a>

<a href="https://www.designwizard.com/blog/design-trends/colour-combination">https://www.designwizard.com/blog/design-trends/colour-combination</a>

<a href="https://tilda.cc/colors/">https://tilda.cc/colors/</a>

<a href="https://github.com/chartjs/Chart.js">https://github.com/chartjs/Chart.js</a>

<a href="https://stackoverflow.com/questions/45415678/is-this-possible-to-bookmark-a-page-with-html-button">https://stackoverflow.com/questions/45415678/is-this-possible-to-bookmark-a-page-with-html-button</a>

<a href="http://www.javascriptkit.com/dhtmltutors/cssmediaqueries2.shtml">http://www.javascriptkit.com/dhtmltutors/cssmediaqueries2.shtml</a>

<a href="http://stephen.io/mediaqueries/">http://stephen.io/mediaqueries/</a>

<a href="https://css-tricks.com/places-its-tempting-to-use-display-none-but-dont/">https://css-tricks.com/places-its-tempting-to-use-display-none-but-dont/</a>

<a href="https://stackoverflow.com/questions/40027058/bootstrap-remove-column-margin">https://stackoverflow.com/questions/40027058/bootstrap-remove-column-margin</a>

<a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/iframe">https://developer.mozilla.org/en-US/docs/Web/HTML/Element/iframe</a>

<a href="https://codeburst.io/making-a-calculator-with-basic-html-css-and-javascript-part-1-1e4288f0bea1?gi=533a9abffa5f">https://codeburst.io/making-a-calculator-with-basic-html-css-and-javascript-part-1-1e4288f0bea1?gi=533a9abffa5f</a>
<a href="https://stackoverflow.com/questions/35816007/bootstrap-button-href-does-not-work">https://stackoverflow.com/questions/35816007/bootstrap-button-href-does-not-work</a>
<a href="https://www.w3schools.com/howto/howto_css_image_center.asp">https://www.w3schools.com/howto/howto_css_image_center.asp</a>


