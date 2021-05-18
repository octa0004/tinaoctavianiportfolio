README.md

Tina Octaviani Web Portfolio –

The concept is to make the portfolio minimal and straightforward, showcase directly to my works.
I believe potential clients or collaborators prefer to see direct what I can do rather than a lengthy description of who I am. So, what I do is make a section of Works (Homepage), profile (who am I), insight (supposed to be like a blog that I can update for article, issues, or tutorial), and contact (to collaborate or hire me).

I am combining the Playfair font and Montserrat to complement each other. Showcase the minimal, elegant vibe but making it readable and suitable for display.

I used the grid, flex, and a little bit of javascript. Mostly I used a lot of grid since I make a lot of changing displays and look from mobile to tablet to desktop. CSS all the way. But to be honest, I feel that I want to explore more with bootstrap and javascript.

Challenges and reflection during web portfolio creation:
1. Navigation
I was having a hard time with the navigation. I thought that I could apply the hamburger menu for tablet and mobile using SVG code, but I realize it does not work that way during the process. I was trying to use bootstrap for the navigation, but the result is not what I want. So end up looking for javascript. Many try from here and there. It takes more than 3 hours to figure it out.
I am a bit panicking here.

2. Homepage – hover
The idea of my homepage is showcase like gallery, so not much text or description around.  When you hover the image, then there is the project title and description. To achieve that, I need an overlay and transition. There I go again, go deep into the rabbit hole, find how to make overlay, and make the position all the same. Until the finishing, I still did not get the exact place. Thanks to Prof Rob's help that mentioned the position absolute and relative. If not, I am sure to the end I will go and probably add more code or whatever to make it the same.

3. Profile
When I make it UX, everything looks exactly what I want. I LEARN BIG TIME here.
Next time if I do a project, I will keep the web developer in mind.
The text and the “to” are not easy to achieve. I was using the grid, <nobr> and <span> and a lot more code, and it cannot look to what I expect, also giving me an error while doing the HTML Validator. To be honest, the transition is not that great, but sadly I think that is the best I can do. Use the min and max to control the grid and the spacing.

For the “-“ part next to them, my story, mantra, fashion, films, hobby.
I thought I could easily use the copy SVG code, but when I do, validation gives me a fatal error.
I go around to add span, different ID, and all those codes, then it hits me. I remember about HTML entities. I feel so dumb here, so I change all the “-“ with HTML entities.


4. Organize and make the naming correctly
I realize after halfway that I had so many pages and how important to have clear naming, so it will be easier during the <a href> to link or to styling, especially I had a lot of transition and change the display from block to grid.

5. Too many pages
When I design it in XD, I didn’t realize that will be so many pages when I code.
But I thought if not now, then I can try to make a website from scratch.
Even though I know, in real life, mostly client is not building from scratch, usually buy a template and ask for customization. I honestly find it challenging, I feel the pressure to make it good, and at the same time, this is a chance to know how far I can use UX and coding skills at this level.

Most of the time, I face the coding is not working because space, a slash or misspell, when doing the coding with many pages, focus and keep calm is essential. Keep doing the inspection and slowly find.

6. Validation Warning
I like to use <section> and <div>. In HTML Validator, I always get the warning because I lack H2-H6 in <section>. I tend to always use h2-h6 inside the div instead of direct to <section>. That is the warning that keeps appearing in my HTML code validation.

When I used :root for color during the validator, I get the warning, “is an unknown vendor extension”. Not so sure why

What I learn during web portfolio creation:
1.	When design in UX, design as if I will do the coding
2.	Always start with mobile and thinking about the navigation or transition I need to make from mobile to tablet to desktop, whether it is possible or not.
3.	Organize the name. Structure correctly before starting the CSS styling! Very important. I made a mistake and causing confusing coding in graphicportrait.
4.	Keep calm and be patient. Look for other sources like LinkedIn, Stackoverflow, GitHub, YouTube to find any help or tutorial.


Adobe XD prototype link:
I cannot put inside the github, so I provide the link here
Desktop
https://xd.adobe.com/view/7aad727e-ec3e-4aa1-b155-13bd6a67670a-2ffe/?fullscreen&hints=off

Tablet
https://xd.adobe.com/view/ee675d6b-f0b0-4619-8ff0-50f9134f52e9-bb34/?fullscreen&hints=off

Mobile
https://xd.adobe.com/view/1ebe4a1a-4bfb-4916-ba5c-8279df04c525-4bed/?fullscreen&hints=off

-

Google Font:
Playfair Display
https://fonts.google.com/specimen/Playfair+Display?query=playfair
https://fonts.googleapis.com/css2?family=Playfair+Display:wght@600&display=swap

Montserrat
https://fonts.google.com/specimen/Montserrat?query=monts
https://fonts.googleapis.com/css2?family=Montserrat:wght@400;600&family=Playfair+Display:wght@600&display=swap

-

Normalize:
https://cdnjs.cloudflare.com/ajax/libs/normalize/8.0.1/normalize.min.css

Javascript:
jquery-3.6.0.min.js

-

Image Assets:

Index.html
Ladies – Background image, use the frame to superimpose my illustration
https://www.rawpixel.com/image/539185/gallery-display-frames

Artdate – Background image, use the image as a border display to make my calendar superimpose look more interesting
https://unsplash.com/photos/Ee7C9fGiZI4

Nyah bakso – iMac image, use to illustrate what I work on, so my artwork is not flat and looks more interesting to display,
https://unsplash.com/photos/3xQ65cknLPk

pattern to overlay
https://unsplash.com/photos/-odUkx8C2gg

Tulistulis – Ipad image, use to superimpose my prototype work so it will look more real 
I buy for this image
https://creativemarket.com/graphiccrew/3887104-Multi-Device-Mockup-Scene-Creator

Smoochy scoop – Ipad image, use to superimpose my prototype work so it will look more real
I buy for this image
https://creativemarket.com/graphiccrew/3887104-Multi-Device-Mockup-Scene-Creator

Custom King – Ipad image, use to superimpose my prototype work so it will look more real
I buy for this image
https://creativemarket.com/graphiccrew/3887104-Multi-Device-Mockup-Scene-Creator

-

graphicladies.html
Ladies – Background image, use the frame to superimpose my illustration, as if my works show case in the real gallery
https://www.rawpixel.com/image/539185/gallery-display-frames

Ladies image 1 – image background, use a real image background to elevate my illustration, make it more eye catching and relatable by mixing illustration with photograph 
https://unsplash.com/photos/s6xt1mwF_iU

Ladies image 2 – image background, use a real image background to elevate my illustration, make it more eye catching and relatable by mixing illustration with photograph 
https://unsplash.com/photos/AD6rn3vqG7o

Ladies image 3 – image background, use a real image background to elevate my illustration, make it more eye catching and relatable by mixing illustration with photograph 
https://unsplash.com/photos/SQxcZIIZHV8

-

graphicsimplyglow.html
Simply glow image 1- Laptop image, use a real laptop to superimpose my works into it, so it does not look so flat and boring
https://www.freepik.com/free-psd/online-education-concept-with-laptop_8852039.htm#page=1&query=online%20educational%20concept%20with%20laptop&position=30

Simply glow image 2- frame and background image, superimpose my artwork logo into it, so it gives more sense of the branding 
https://www.freepik.com/free-psd/top-view-beauty-spa-essentials-with-frame-candles_8851979.htm#page=1&query=top%20view%20beauty%20spa%20essentials%20with%20frame%20candle&position=0

Simply glow image 3 – box and bottle label, superimpose my artwork logo into it, so it gives preview to the client how it will look in their product
https://www.freepik.com/free-psd/cosmetic-bottle-with-box-mockup_13099786.htm#page=3&query=cosmetic+box&position=4

-

printflorarecipe.html
flora recipe image 1 – Background image, use the image to superimpose my sketch into it, give a mood and also bring up the ideas how this project start-
I buy for this image
https://www.istockphoto.com/photo/close-up-on-top-view-with-compostion-of-book-and-cup-and-white-ceramic-plate-in-gm1063657278-284363338?irgwc=1&cid=IS&utm_medium=affiliate&utm_source=TinEye&clickid=3dgX7wRMixyLTpKxU-SAVSQkUkESCDzvPyz7xY0&utm_term=&utm_campaign=&utm_content=435504&irpid=77643

printnyahbakso.html
nyah bakso image 1 – sketchbook, grab 1 of image, edit and make it as a background to contain my sketch, make it more eye-catching so it will grab people attention
I buy for this image
https://www.istockphoto.com/photo/top-view-collection-of-spiral-kraft-notebook-front-back-and-white-open-page-isolated-gm1007719510-271877074?irgwc=1&cid=IS&utm_medium=affiliate&utm_source=TinEye&clickid=3dgX7wRMixyLTpKxU-SAVSQkUkESCFQ%3APyz7xY0&utm_term=&utm_campaign=&utm_content=435504&irpid=77643

nyah bakso image 2 – card and hands blank mock up, to superimpose with my artwork
I buy for this image
https://www.istockphoto.com/photo/kraft-square-flyer-invitation-mock-up-gm589450422-101249165

-

webportfolio.html
iMac, ipad and iphone blank template – to contain the prototype image work so it will look more real - I buy for this image
https://creativemarket.com/graphiccrew/3887104-Multi-Device-Mockup-Scene-Creator

webdash.html
school project and protype provide by Professor Rob –
https://imdac.github.io/mtm6201/exercises/landing-page.html

webarc.html
school project and protype provide by Professor Rob –
https://imdac.github.io/mtm6201/projects/prototype.html

webooso.html
image inside the project (header - yellow nuts background) -
https://unsplash.com/photos/sVrEI2myiv4

websmoochy.html
image inside the project (header - ice cream image) –
https://unsplash.com/photos/zgl4LvTL06c

webcustomking.html
image inside the project (header – 2 person image) – edit the content 
https://www.rawpixel.com/image/2827196/free-photo-psd-t-shirt-mockups-t-shirt-couple-t-shirts