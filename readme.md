#Recipe Finder

### Overview

Create an app using React and [React Hooks](https://reactjs.org/docs/hooks-intro.html) that will be a recipe finder.

- Use [fontawesome](http://fontawesome.io/icons/) for any icon needs and [axios](https://github.com/axios/axios) for any http requests.
- Spend, at max, 4 hours on this project
- Prefer to see effective use of state management, thoughtfulness in component building and focus on performance/best practices over styling if you are running out of time

### Requirements

- Integrate with "TheMealDB" API http://www.themealdb.com/api.php
- The main page will display 5 random recipes as 'Recipes of the Day'
- Mobile designs are provided, get creative with responsive desktop designs
- Use a css preprocessor
- Clicking on a recipe should open a detail page about the recipe
  - The URL should change (consider using [react-router](https://github.com/ReactTraining/react-router)) when a recipe is clicked
  - If a user copy/pastes the URL into a new window, the same recipe detail page should display
  - Detail page should show the ingredients and instructions for that recipe
- There should be a search bar allowing users to search for a recipe
  - Search button on mobile in the bottom right corner of the screen - which should open a search window with the keyboard
- The search results will be displayed where the random recipes were displayed
- The results should be paginated with 5 results displaying at a time
- Add a 'Heart' icon in the modal for a recipe
  - The heart icon should 'favorite' this recipe
  - Store this data in the users browser
- If any favorited recipes are detected in the browser, add a button on the home page that shows a list of these recipes

#### Bonus

- Add a share button on the modal page to "Tweet" the recipe

### Submission

Once you've completed your project, deploy the code (to a free account on Heroku), and submit links to the hosted instance and your github repo.
