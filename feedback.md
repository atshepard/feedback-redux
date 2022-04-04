## Markdown

Hey Juliette!

General Feedback:

---
| Functional Requirements | Complete? |
| --- | :---: |
| Multi page form with client side routing and navigation (next button) | YES |
| Data stored in Redux when navigating from page to page | YES |
| User is notified when trying to leave a blank score | YES |
| Review Component displays scores and comments from current redux state | YES |
| Submit button sends data to the server via Axios | YES |
| Confirmaion Page displays after data is POSTed to the server | YES |
| Button on Confirmation Page clears Redux and starts a new survey | no |
-- This was one of the only things that stood out to me: when posting the server, your form doesn't send an empty object to redux to reset the 
-- current redux state. It will retain the last feedback entered: 

<img width="738" alt="Screen Shot 2022-04-04 at 9 26 33 AM" src="https://user-images.githubusercontent.com/94128124/161567624-2c1faa7d-7c6d-4e2f-81cb-c884d8ff108c.png">

-- Totally easy to miss doing this, because I ALSO DID THIS! 

| Views are broken down into components | YES |

---
### Notes:

Notes on the above Functional Requirements.

---
| General Items | Complete? |
| --- | :---: |
| More than 15 git commits | YES |
| Commits are descriptive of the changes made or feature added | YES |
| Readme file updated | YES |
| Appropriate amount of code comments | YES |
| Code is consistently formatted | YES |
| Server code organized with router & module files | YES |

---
### Notes:
Excellent work, Juliette. It's a great balance of form and function (HA), and it's clear you put a lot of work into this. If I had any say, you'd get 
an _Exceeds Expectations_ for this. I love your fearlessness for trying new things, and you really carved out a lot of space to try things here. 

Your redux, which is really the meat and potatoes of this assignment (so to speak), looks good, in my opinion. You dispatch on every form correctly. 
You found a way around using {... state, } by assigning the values of your placeholder object properties
but I wonder if this would make the redux harder to clear than just clearing state altogether.

Great job! Your ability to execute on a vision is so inspiring. Thank you for your positivity and creativity! 
