# Jungle Devs' Frontend Challenge

This repository holds the code related to Jungle Devs' frontend challenge to join their Academy Program. The following gif shows the page in both desktop (1920x1080) and mobile (360x774) sized screens. If its quality seems to be subpar it's because of the 10mb limit to file sizes here on GitHub (the original gif was 17+ mb). If you wish to see the result in a more in-depth demo and in a better resolution, you can watch a video I recorded [here](https://www.loom.com/share/57f6d1aa46174d1eb1ac1a7575f5b423).

![jungle](https://user-images.githubusercontent.com/20730250/109849173-d55ed080-7c2f-11eb-80f6-5eb27f803f26.gif)

# Table of contents

- [Challenges](#challenges)
  - [Inconsistent styles](#inconsistent-styles)
  - [Very long style sheet](#very-long-style-sheet)
- [Lessons learned](#lessons-learned)
  - [Think globally before you start](#think-globally-before-you-start)
  - [Markup reusability](#markup-reusability)
- [Goals](#goals)

# Challenges
## CSS grid system
I had some experience with responsive design, but only with Bootstrap, so it proved challenging to make a responsive page with native CSS only. It was quite interesting getting to know it better, even though I think there's much more to learn in order to make better use of it.

## Inconsistent styles
One of the main challenges I faced was some behavior inconsistencies of a few elements. I struggled a little to create style for an element that should behave differently in different parts of the page. Case in point: article. The way I built the HTML, the h1, h2, h3, p and a tags are placed inside the article. This way I'd created a structure that could hold three elements that would be aligned mostly the same way. Sometimes, though, they should fill the whole row, then I'd have to add more specific styles to the initial ones. Which leads me to the next issue.
  
## Very long style sheet
Having many highly specific cases led me to write a lot of mark up, which resulted in a style sheet longer than I intended it to be. Early on I noticed this was happening, so I tried to read about CSS good practices in order to learn a better way to make my mark up but, unfortunately, in this time frame I didn't manage to refactor the CSS in order to make it shorter.
    
# Lessons learned
## Think globally before you start
This challange made me appreciate even more the work of the designer, who has to think of everything beforehand. It was already evident to me that this was important, but after this experience, I'll become even more adamant on the importance of planning before starting a project. I did try to start with the basic HTML structure but it didn't prevent me of creating the first two issues mentioned in the previous section. Next time I start a frontend project from scratch, I'll have to rethink my process.

## Markup reusability
Having come up with a better way to plan/organize the HTML and the CSS, surely the code will be more readable and shorter, having multiple smaller pieces that I can reuse as needed. 
		
# Goals
Before starting out the project I made a roadmap with everything I wanted to accomplish and also something I wished to do, if I concluded the project with enough time to venture in this path. Fortunately, I managed to deliver everything I set out to do: three screen sizes (desktop/larger, intermediate/tablets, mobile) and, of course, respect the deadline. I really wish I could have spent more time with accessibility, but the mobile screen size took much longer than I anticipated it would. 

- [x] Desktop resolution
- [x] Intermediate and mobile screen sizes 
- [ ] Accessibility
- [x] Deliver on time		
		
		
		
