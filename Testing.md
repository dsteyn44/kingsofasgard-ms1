#  Testing Ground

## Overview
Generally, I tested often and made it a regular habit to a) check my responsiveness on all devices, and b) vallidating the script. It was only then I would stage, commit and push. I also used repl.it to try pieces of code to assess whether it would work or not. I found this quite useful as it was quicker than gitpod and I could make mistakes without affecting my actual project. This did however take more time ( I mean the checking bit) and I think in the future, I will just have to plan better. Also I tended to get caught up in one bug and this wasted precious time.That is something for the future.  

The project was a little challenging in regards to working with Bootstrap. Bootstrap is certainly great tool for creating a structured template in place but admittedly I had challenges with the responsiveness and overiding its templates to suit my requirements. Admittedly this could be because I am by no means an expert at using the software so when you hit a snag it takes time to figure out where the problem lies. Generally and as mentioned in the coursework, in order to overide bootstrap, you have to be fairly specific.
#
## Validators used: 
- Jigsaw - I used this for CSS verification. [Jigsaw validator](https://jigsaw.w3.org/).
- Nu W3 validator - I used this for HTML verification. [W3 validator](http:s//validator.w3.org/).
- Lighthouse - I used this to check performance. However I have to be honest and say that there was alot I was unsure of but it was good to 

Proof of final validation:

HTML:

CSS:

Lighthouse:


#
## Responsiveness

For the responsiveness I used Chrome Dev Tools to check how the website would behave. However saying this I must add that it did not always give a correct or real account on the device. Of course it is only a tool and not but I found one instance where it did not give me the correct response. This was an instance for mobile phone. on Dev tools it showed the main figure on the front-page was clearly visible but when I uploaded this on my device his head appeared cut-off by the jumbotron. It look too big. I did clear this up later by adding a media query.  

|   :iPhone 5:    |     :iPad/ Pro:   |    :Desktop:    |
| good              | good|
|[The Fanwall Page](wireframes/desktop-fan-wall.png)|[The Fanwall Page](wireframes/tablet-fan-wall.png)|[The Fanwall Page](wireframes/mobile/mobile-fan-wall.png)|
|[Fail Page](wireframes/desktop-fail-page.png)|[Fail Page](wireframes/tablet-fail-page.png)|[Fail Page](wireframes/mobile/mobile-fail-page.png)|


#
## Bugs

Navigation bar
- Originally I wanted to have the band logo in the center of the page at the top; however it was not coorosponding with the other elemants on the navbar. I think this was due to the facrt that I tried to make a navbar by using columns. So instead I decided to just to use Bootstrap's template Nabvbar (with Navbar Brand) and this solved the issue. 


Gig Guide - front page
- For the Gig-list at first i wanted to add a dark drop-down menu for Gig list. Add back ground to column.
Dropdown does not work. Bug-fix
I grabbed another dropdown menu from another project.

Contact Us dropdown toggle
- I primarily had the Contact Us (Contact page) as a drop up page in the footer bar but when I made the screen smaller it would move above the social links. I was spending too much time trying to work this out so I opted to make it a drop-down in the navbar. I then noticed that in smaller sizes it would over expand the screen so you could not add any information or see the "submit button". I contacted tutor support and they suggested i go with a modal instead. It did solve the issue in a different way.

Front Page Spotify Sound control and Audio 
- One of the features of the website would be to have a clip of music on the front page. At first I was unable to obtain a audio clip from the band but instead I copied my own version of the song onto gitpod form iTunes. And although this worked at first it a) took up too much space and b) did not always play. So I then decided to use a clip from spotify. Even though 

Fanwall Page Spotify Sound control and Audio
- This was moving towards the right-hand side of the screen - particularly in 
#

## User stories

#### Client User Stories
- As a client I want set-up a website so that it will bring like-minded people together.

- As a client I want a better platform so that I can increase my fan base.
- As a client I want my users to easily navigate my site so that they have a better user experience and therefore will continue to visit.
- As a client I want the website to have room to evolve so that I will have a repeat fanbase that is not necessarily 
- As a client I want eye catching visiuals so that the first time users will want to wnt to investigat further. 

#### First time User Stories
- As a first time User I want to be able to hear the bands music on the first page so that that I decide to follow.
- As a first time User I want to see where they are playing and the dates so I can see if i am  able to go view the concert.
- As a first time User I want to see what the band is about, who they are so.
- As a first time User I want to navigate easily throughout the site so that I can get to the pages efficently. 

#### Frequent User
- As a frequent user I want updates so that i can visit the website and it will keep me interested.

#### Festival organiser/ Concert organiser
- As festival organiser/ Concert organiser I want to efficently contact them.
- As festival organiser/ Concert organiser I want to see who account for their fans  so that i can see if they are are suitable for the content that I provide.