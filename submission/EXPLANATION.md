# Explanation

## Draft explanation (124 words)

In this project, I used JSX to describe the Event Planner page with HTML-like syntax inside JavaScript. JSX lets me place headings, lists, and components in the return value, and I write className instead of HTML's class. CSS selectors connect the markup to its appearance. The class selector .events_categories matches the section's className, while the descendant selector .events_categories .event-category h2 finds a heading inside a category card. Flexbox arranges the three cards in a row: display: flex creates the layout, gap spaces the cards, and justify-content centers them. On small screens, flex-direction: column stacks the cards. I also used component composition: App renders EventPlanner, and EventPlanner renders Footer at the bottom. This keeps the page organized and separates the footer from the main content.

## Why use a Footer component?

I import `Footer` and render `<Footer />` so I can reuse it on other pages, keep `EventPlanner.jsx` shorter and easier to read, and edit footer content in one place. The footer has its own responsibility, separate from the event page content. Putting the components together this way is called composition.

## Screenshots

- Desktop screenshot (about 1280px) = `desktop.png`, to be added manually.
- Mobile screenshot (about 375px) = `mobile.png`, to be added manually.

## Hover and click behavior

CSS `:hover` is handled by the browser and changes appearance only. React `onClick` runs a JavaScript function when the click event fires; in this page, it shows the welcome alert.
