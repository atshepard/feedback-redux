# Weekend Challenge 11 - React-Redux Feedback Form

## Instructions

Reviewing code is an important role developers play. We're going to practice reviewing code from others.

- Get the repo url from your partner
- Get your partner's project running on your computer
- Review the code from your partner and give relevant feedback
- Complete the Markdown section and submit that in the notes section on the assignment app. (Make sure you include who's code you reviewed.)

Practicing compassionate code reviews is important (you can learn more from this video on the topic: https://www.youtube.com/watch?v=Ea8EiIPZvh0 )

## Review Checklist

## Base Required Features 

- Multi-Part Form:  
  - [x] Able to add feedback
    - [x] Data collected on individual pages & components
    - [x] Click on next takes you to the next page in sequence
    - [x] Data saves in DB after *all* the parts are completed (not piecemeal)
    - [x] Thank you page takes you back to the first view
    - [ ] Old Data is cleared on form completion

- Client code:
  - [x]  Individual components for each form part
  - [x]  Redux setup complete
    - [x] Store linked to react with `<Provider>`
    - [x] Store setup with reducer(s) and logger middleware 
  - [x] Reducers & Actions Working
    - [x] Actions are in SCREAMING_SNAKE_CASE and semantically named
    - [x] Actions have a `type` key, and `payload` if sending data
    - [x] Reducers are returning a new state, or the old state (not mutating)
    - [x] Reducers are using spread correctly (to keep old data, while adding new)
  - [x] Review Component shows at all times with current redux state
  - [x] React-Redux Working
    - [x] Dispatching actions onClick
    - [x] Grabbing data from the redux store with `useSelector`
  - [x] Axios POST request to add feedback


- Server code:   
  - [x] Router made for GET, POST


## General Items
Feedback should be provided for these items, but they do not impact scoring.

- Git 
  - [x] Multiple git commits showing incremental progress
  - [x] Commits are descriptive of the changes made or feature added 
  - [x] Has .gitignore with node_modules
  - [x] Readme file updated (assuming this is previously discussed)
- Code Style 
  - [x] Appropriate amount of code comments
  - [x] Code is consistently formatted
- Client
  - [x] Appropriate use of HTML tags
  - [x] Basic CSS styling with margins/padding


## Stretch Goals
First must be complete for score of  _Exceeds Expectations_

- Previous Steps
  - [x] allows a user to go to a previous step, either directly or by cycling backward thru the steps
  - [x] user can update their score for a step
    - [x] new score is validated to not be empty
    - [x] redux is updated with new score
  - [x] user can continue on to review page and submit as in Base Mode


- Admin View
  - [ ] All entries are visible with correct data from inputs
    - [ ] Most recent is at the top
  - [ ] Can Delete an entry
    - [ ] User is prompted before deleting
  - [ ] Axios GET request to get all feedback for `/admin` view in componentDidMount

  Busywork Goals, consider removing or making more useful

- [x] Styling with Material UI
- [ ] Ability to flag a feedback item on `/admin` for further review
- [x] Deployed to Heroku
