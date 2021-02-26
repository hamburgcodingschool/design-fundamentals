# Design Fundamentals – Cheat Sheet


## What is design?
Design is communication. As we cannot not communicate, we cannot not design. Design is closely connected to creation. Also we as humans are inherently creative. We strive to create solutions to overcome limitations or obstacles and ease our lives. To learn, develop and grow. As soon as we create, we think about how something works. That is design. Design is how it works. Design always solves a problem. Design always serves a purpose. **Design is consciously taking decisions to define how something works (and in turn looks) in order to support its purpose.**

Design is the process of selecting and adjusting design parameters that make a difference in the given context (sender/identity/message/channel/identity/receiver/interaction), so users can digest (learn) the content (storyline) with focus and get value out of using it (your website or app).


## Why design?
As we cannot not do it, let's do it intentionally in order to support our purpose. **Good design is intentional.**

## Define your purpose
Define who (person/brand = provider of service/product) is saying what (message/call-to-action) to whom (users/customers). Set a goal for what you want to achieve upfront, your design goals derive from that motly. Information creates context, context gives you constraints, constraints help to decide how to approach your target group.

## What can design do?
### The basic layer of design is usability. Making your message accesible, readable and usable for the audience you want to reach.
### The second layer is styling or branding. It is used to add emotion and context which appeal to a certain audience.


## Principles

### Always start with why. 
* Why are you doing this design?
* Who is sending the message?
* Who is it for? 
* What should it achieve?
* When is it good (=successful)?
* What is the overall context?
* What's the channel/medium?

### Constraints are your friend. 
Constraints define the boundaries of how you can design something to work effectively. Contraints help you take (design) decisions and thereby direct you an. The context adds meaning and intent and sets constraints. Use them to communicate your message effectively to an audience it is relevant to and make them act on it. Design always aims to create impact and alter peoples behavior.

### Whitespace creates focus. Do not fill the page to fill the page.

### Cluster your content and align it along a "storyline" and distribute it on your format accordingly, to present it to your audience in order and in several steps. Uusally communication that puts a lot of information at once on you, is percieved as overwhelming. But mostly you do not want to overwhelm people.

### Contrast
Use big steps, that really make a difference to the reader, instead of light and subtle differences that might not get notice. Contrast is what makes the difference clear.


Always try to respect (social) context and (channels) conventions. Learned stuff that users already now from their reality/life. 
- For example clicking on the logo usually leads back to the homepage. Or links are underlined and colored. Things that are interactive, show that and also react on hover.
- Reading direction left to right and we start in the top left corner and go down to the top right, but not in  a straight line, but in a Zoo F shaped motion.

Constraints are your friend. The give orientation and direction (towards a certain group of people.)

Context: By gathering information about your purpose and everything related you build context. Context gives you constraints.

Presenting new stuff means learning or users.
Their cognitive load is very high.
So portioning the content carefully is important. 
Separate the stuff you want to tell them into small chunks. 
That is how human perception works anyway. If something is too big or complex for us to grasp, our cognition (the cognitive perception machine that our brain is) starts breaking stuff down into smaller chinks it can process. 
The smaller the chunks the easier to process.

That’s why we do exactly the same when we introduce new offers to our audience. We create a storyline out of chunks of information. We group it into clusters and give it an order and thereby direction. So users can follow the story and discover the new step by step, with focus on one chunk at a time, instead of being overwhelmed by all chunks being placed on one screen.

The example page could have been designed in a way where all the information is crammed into one screen, the first page above the fold. This way no scrolling would be necessary. 
That way it would not feel like one short and simple story I can follow. Not like something clear I can start with and continue from there in only one direction (down the page) being able to discover each step of the story at a time, with the necessary focus, because there is little distraction. Instead it would probably feel like a marketplace where everybody is screaming at you and competing for your attention. This would be a very high cognitive load, which could lead to you refusing to take a look at all. (Paradox for choice).

You could compare this with an optional stroll through nature or the woods. As compared to everything on one screen would feel like a marketplace where all the impression rain on you at the same time, trying to get your attention at the same time. Everybody screams for you louder than the others to get your attention and sell you their product or benefit. This is confusing and a lot to process and does not allow for focus and clarity and comprehension and sequential learning, but results in information overload. 


## How to prfoessionally work with designers as a developer

...


## Tricks

Eye-squeeze-test to determine your visual hierarchy, the reading order if you will. It allows you to see which elements take what amount of attention in your design and how they (mis-)guide the user by this, apart from their content (just visual appearance). This also works by overlayin a transparent blurred shape over a design. (Easily possible in design software like e.g. in Figma or Sketch.)

## Rules of thumb

### How to build a visual hierarchy

### How to select colors?
- Start with black (type) white (paper/canvas) 
- For each new color, think about if you could do it + some shade of grey to have sogrey and an accent color and see if that already works for you.

### How to select fonts?
Google fonts
If you want to pari fonts, make sure the really differ from each other. Do not try to pair fonts that are similar. Better take a font that has a lot of weights and variants (a big family) son you can stay inside the family and variate as needed, but overall stay in the same family (character).

### How to style fonts?
What is a good starting point for font-size, line-height and paragraph width.
- For reading text, do not go below 16px font size.
- Line-height can be set relative to 1.5em and will optimize
- Do not use multiple styles for the same purpose, e.g emphasizing a word (only bold or italic).

How to decide on headline sizes and where to start?
Start with the smallest text size you defined (probably min. 16px as the largest amount of text will be set in this) and go up from there.

### How to create a grid?
Use 12 columns for flexibility.
Then you can define layout areas that are full width, half width, 1/3 and 1/4 width for example, to have different layout modules to combine to distribute the contenton your format.
Going with squares here is a good practice. This means initially defining your layout areas to be as high as they are wide, so theyre always square, is good practice. (You can of course extend their height in grid steps whenever it supports your purpose better.)
960px width for your base content grid guarantees good redability from standard screen distance on desktops.
A gutter of 20px mostly works well.

### More

Each page should have some empty space on the very bottom to signal: This is the end of reading here.


### Why define a headline hierarchy and a grid ?
That is basically why we create grids and steppingstones in font sizes (also a kind of grid). To make sure the differences are big enough for user to clearly recognize. Also by creating the stepping we reduce the number of choices drastically and make sure we have the flexibility to chunk content and in doing so create repeating patterns that users can learn and rely on.


### How to make any page look better?
html {   max-width:70ch;   padding:2ch;   margin:auto;   color:#333;   font-size:1.2em; }


## Tools
Grid generator https://grid.layoutit.com/
Font pair selector
Color picker
Gradient generator


## Further learning on design

Learning UI - newsletter & Teardowns
https://learnui.design/

E-Mail Design Course
https://www.hackdesign.org

UI Audits
Https://uibreakfast.com

Better Web Typography
https://betterwebtype.com/

Boilerplates?
MVP.css https://andybrewer.github.io/mvp/
Tailwind


## Laws (of perception)

* Hicks law
* Fitts law
* Ockhams razor
* Law of proximity 
* Law of continuity


## Quotes 
Good design is not when there’s nothing left to add, but when there’s nothing left to take away. 
Content is King, design is queen.
Keep it simple stupid.
Less is more.
Reduce to the max. 
