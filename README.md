# Indoor Rock Climbing

Indoor Rock Climbing is a website to introduce the three main disciplines of competition climbing; Bouldering, Lead Climbing and Speed Climbing, to anyone, from those who have only just heard of the sport to those eager to give it a go. Many people will have discovered the sport for the first time when it made it's debut Olympic appearance at Tokyo 2020. Whilst the climbs were impressive to witness, for most people, the air of mystery around the sport may have prevented them from thinking they could ever try it out for themselves. 

This site provides an insight into the rules, equipment and technical language involved in each of these three disciplines, designed to bring indoor rock climbing to anyone with an interest in the sport, as well as a brief look at its origins and some highlights from it's first Olympic appearance.

[*Insert an image of your site on different devices from the Am I Responsive site or similar*]

## Initial Vision [**to complete**]
---

* wireframes screen shots
* basic explanations for ideas

The colours and layouts for each page just to distinguish the different sections and show how the content could be arranged. 

## Features [**to complete**]
---
Done:
* The header in each of the 3 information pages is fixed so that the logo and nav menu stay at the top of the page as the user scrolls
* The heading in the top left corner of each information page is also a clickable link back to the homepage
* The information pages each have a fixed set of links in the bottom right hand corner which stays in this position as the user scrolls. The initial styling is set so that it is visible enough but doesnt distract from the page content. Once hovered over, the links are styled so that their text and background colours invert making them more visually obvious (also contributes to user interactivity/UXD)

To Do:
* homepage
* header
* footer
* navigation
* main background
* 3 main menu items
* 3 main info pages (their images, videos, links, navs)
* contact/newsletter form
* site credits (new tab? with links to new tabs)
* about the author
* social media links (new tab)

## Responsiveness [**to complete**]
---

(note: using % heights/widths in CSS contribute to responsiveness)
* media queries 
* different screen sizes
* incl. screeenshots

## UXD [**to complete**]
---
Done:
* Used Google Fonts [add-link] to choose a main font which I liked the look of (Montserrat - Extra-light 200) and one that was recommended to pair with it (Roboto - Light 300) and imported them into my styles.css so that all of my html files with the style.css link can access these fonts. I later removed the pre-set weighting from the import link so that I would have more flexibilty with styling the font.
* Used Google Fonts [add-link] to choose Fira Sans to pair with Montserrat and imported all the none-italicised weights so that I had the flexibility to see which are most readable in different page sections.  
* Homepage background image:
    * Originally was a more close up image that was a bit dark and only a few many colours.
    * Changed to the current image which is a lot lighter and even though there are a few more colours, I feel that no part of the image particularly draws the user's attention away from the main text and navigation.
    * I used the linear-gradient CSS property to create a semi-transparent layer over the image in order to make the text and navigation ontop stand out a bit more.
    * I tried using tinyPNG [add-link] and tinyJPEG [add-link] to reduce the size of the image, but when testing the reduced images I did feel that the quality of the image suffered a bit on larger screens so I decided to keep the full size image which is less than 500kb anyway.  

To Do:
* how you considered it in your design
* justify deviations (if any)

## Accessability [**to complete**]
---

Done:
* Made the main navigation links 'button' elements instead of 'divs' [semantic html] 
* Added aria-labels to the footer social media links (read about on: https://www.w3.org/WAI/WCAG21/Techniques/aria/ARIA8.html)
* Added the alt attribute to the img element for social media icons
* Changed homepage navigation buttons into anchor element links after researching which would be best from an accessability point of view. The Youtube video: https://www.youtube.com/watch?v=OmoCfODeBTA by Steve Griffith explains how the button and anchor elements can be styled to look identical and work the same with other languages such as JavaScript, but there is actually more inbuilt accessability with anchor elements, if you are using it for the purpose of linking to another part of the page or openeing a new page, such as opening in new tabs/incognito tabs/windows.
* Added the main element around the main content of each page (except for the homepage whose main content is the nav element which cannot be placed inside the main element) for better screen reader accessability.

To do:
* how you considered it in your design 
    * aria-labels
    * semantics html [buttons instead of divs]
    * testing screen readers?
* research
    * the NV website/project
    * continual testing with Lighthouse (Google Dev Tool)

## Other Feature Ideas [**to complete**]
---

* ideas there wasn't time to implement (and how you would)
* incl. wireframes?

## Testing [**to complete**]
---
Done:

[html & css validators (regularly, comment on any frequent/difficult issues)]
* [19-10-21] 1st testing index.html in WC3 markup validator indicated:
    * that I had section elements without headings, which led me to create the welcome h2 heading for the #welcome-para section and to realise that my main-nav nav element did not need to be within a section element.
    * that I had anchor elements within button elements, which led me to research buttons vs anchor elements from an accessability point of view and to ulitmately change the buttons to just be anchor element links (as explained in the Accessability section).

[bugs and fixes]
* [21-10-21] couldn't get the font-weight property to work for my Monserrat and Roboto Google Fonts. 
    * Solution: After searching through the Google Fonts site I realised I needed to import all of the font weights that I wanted to use in my website, so I imported a number that I wanted to try.  
* [24-10-21] on larger screens some of my pages which didn't have a lot of content ment that the footer was not at the bottom of the viewport. 
    * Solution: I created a CSS class with min-height = 100vh and applied it to the main element of each page (nav element for the homepage) so that the main content of each page adapts to have a minimum height which allows it to fill the viewport on any screen size.

To Do:
* Lighthouse accessability score
* bugs and fixes (document throughout)
* any unfixed bugs (and what you tried or changed to instead)

## Deployment [**to complete**]
---

* describe process to deploy to GitHub Pages
* live site link

## Credits [**to complete**]
---
Done: [add to Site Credits page]
* Google Fonts [add-link] for Montserrat and Roboto (or the Fira Sans?) fonts used 
* Using the Flexbox method to centralize content horizontally **and** vertically [Link: https://stackoverflow.com/questions/5703552/how-can-i-center-text-horizontally-and-vertically-inside-a-div-block (scroll to: Approach 2 - Flexbox method)] 
* Using social media icons from Icons8:
    * <a href="https://icons8.com/icon/84884/instagram">Instagram icon by Icons8</a>
    * <a href="https://icons8.com/icon/84872/facebook">Facebook icon by Icons8</a>
    * <a href="https://icons8.com/icon/84938/twitter">Twitter icon by Icons8</a>
* Using icons for my homepage main navigation menu from Icons8:
    * <a href="https://icons8.com/icon/61752/order-history">Order History icon by Icons8</a>
    * <a href="https://icons8.com/icon/-oxziy4sBdXf/climbing-wall">Climbing Wall icon by Icons8</a>
    * <a href="https://icons8.com/icon/5111/olympic-rings">Olympic Rings icon by Icons8</a>
* Finding that the Google Font Fira Sans paired better with Montserrat for me:
    * https://www.figma.com/google-fonts/montserrat-font-pairings/
* Using icons for my The 3 Main Climbing Disciplines page from Icons8:
    * <a href="https://icons8.com/icon/9800/drawstring-bag">Drawstring Bag icon by Icons8</a>
    * <a href="https://icons8.com/icon/9809/harness">Harness icon by Icons8</a>
    * <a href="https://icons8.com/icon/19099/time">Time icon by Icons8</a>
* Homepage background image: <a href = "https://www.pexels.com/photo/girl-in-blue-and-brown-dress-standing-on-multi-colored-heart-shaped-blocks-6700629/">by cottonbro on Pexels</a>

To Do:
* mention the Site Credits page which is on the site 
* links to things you borrowed from/were inspired by
    * content (text/icons)
    * features (things in css or functions on the site)
    * media (photos/videos)

##  Site Expansions Ideas [**to complete**] 
---

(different to Other Feature Ideas)

* social media aspect for climbers to get in contact with eachother 
* a way to recommend gyms for user to visit based on their location, distance/travel preferences etc (with links to the gym's site)
* basic 'game' (climb-through) type quiz where you work your way up a climbing wall answering different questions about things learnt on the site (rules, technique, equipment, saftey...)
* actual newsletter 
    * updates from different gyms
    * general climbing news 
    * section for answering questions users send in
* blogs for users to contribute to (monitored) and/or written by the site owner
* advertising for climbing equipment and places to climb 