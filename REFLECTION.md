# Cookie Clicker Reflection

## What helped you understand DOM interaction best?

Seeingthe counterDisplay.textContent = clickCount actually change the number of clicks on the page. I understood that getElementById grabs an element, 
but actually watching .textContent update every time I clicked made it clearer that the variable in my code and the text on the screen are two separate 
things I ahve to manually keep in sync. The number doesn't update itslef just becuase the clickCount changed.

## How did you choose your milestone messages?

I went with the suggested ones (10, 25, 50, 100) sincen they already had a nice pacing to them. I also added some color and an emoji change 
when the milestone of clikcs was reached, to give a sense of accomplishment for the user (me).

## What challenge or bug surprised you?

I had originally tried using >= instaed of === for the milestone checks, and it broke the emoji/color changes. Once I passed 10 clicks, 
the "10" condition kept matching on every single click after that too, because the numbers follwing are all >= 10. Switching to === fixed this problem. 

## What personal twist did you add?

I added a feature that the cookie emoji itself changes at every milestone to emphasize each milestone when it was reached.

## What real-world app uses this kind of interaction?

Duolingo uses similar features with usage streaks. When you finish a lesson, a counter goes up, and hitting a certain number triggers a new message and 
animation. This feature allows the milestone to feel more accomplished for the user.
  
