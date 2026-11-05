# Recipes Hub

A responsive recipe website where visitors can browse 15 recipes in a clean card layout and open a detail page for each dish. It is built with plain HTML and CSS, with no frameworks and no JavaScript.

This is a **team term project** from our BS Software Engineering degree at the University of Central Punjab (UCP), built by **Hira Khan** and **Aiman**. The requirements document is in [`docs/`](docs/).

## Features

- **Home page** with a hero section and a responsive grid of 15 recipe cards.
- **Recipe pages:** each dish has its own page with a photo, prep time, cook time, servings, an ingredients list and step-by-step instructions.
- **Like button** on every card, built with CSS only (a styled checkbox).
- **Search bar and category filters** (Breakfast, Vegetarian, Dessert, Dinner, Vegan). These are interface designs only; they do not filter the recipes yet.
- **Login and sign-up pages** with form layouts. They are static and have no real authentication.
- **Consistent navigation** across all pages, and a layout that adapts to different screen sizes.

## Tech stack

HTML5 and CSS3

## Run it locally

No setup or build step is needed.

```bash
git clone https://github.com/HiraKhan13/recipes-hub.git
cd recipes-hub
```

Then open `index.html` in your browser.

## Project structure

```
index.html          home page with the recipe grid
recipe1.html ...    recipe detail pages (recipe1 to recipe15)
login.html          login page
signup.html         sign-up page
styles.css          styles for all pages
images/             recipe photos
docs/               requirements document
```

## Possible improvements

- Make the search and category filters work with JavaScript.
- Save liked recipes.
- Add real login with a backend.

## Team

- Hira Khan, [LinkedIn](https://www.linkedin.com/in/hirakhan01)
- Aiman, [LinkedIn](https://ww.linkedin.com/in/aiman-attaullah)
  
