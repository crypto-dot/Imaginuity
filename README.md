# LIVE LINK -> https://crypto-dot.github.io/Imaginuity/

# Imaginuity
Take home assignment

## Technologies And Why I Used Them
I decided to use vanilla HTML, CSS, and JS for this take home assignment. While I could have theoretically used any framework I wanted I decided to keep it simple for a few different reasons:

1. This is a simple landing page. There is no user authentication or anything complex happening behind the scenes. There is no need for separate components when each component on the page requires at most 25 to 50 lines of CSS. 

2. The data on the page is not dynamic. For sites with dynamic pages I tend to reach for Preact (lightweight react) or NextJS (something I'm still learning). NextJS is currently the future of React. It allows SSR which completely removes client side rendering (long page loads and big JS bundles) and allows developers to render their websites on a server and ship the HTML,CSS, and any remaining JS to the client.

3. No JS is needed. Sometimes the simplest solution is quite literally the best solution, adding React would introduce client side rendering and slow page load times. Additionally, There's no purpose of using JS at all for this site.

4. Everyone knows HTML,CSS, and JS (Well almost everyone). If I really wanted to I could have gone with AstroJS. However, I realized that not everybody is proficient with it (I'm still learning some of its quirks), and it would give anyone looking at my work a harder time to understand my abilities as a web developer.

## What's BEM Conventions, and why did you use it?

BEM aka Block Element Modifier conventions allow CSS developers to write at most (0,1,0) specificity. This means LESS CSS and LESS COMPLEX CSS. Quite literally the best of both worlds. Additionally, BEM conventions are very easy to pickup and remember (the name BEM is how CSS classes are named). BEM conventions refuse to use IDs (this adds complexity) and only relies on CSS classes. This allows other people to more easily read through your CSS AND make additions to it without wondering if something should be an ID or not.
