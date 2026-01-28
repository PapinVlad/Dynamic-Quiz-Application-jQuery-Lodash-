
This was my first project where I moved away from "just making things look good" to "making things actually work." I built a fully functional Quiz App with 5 categories and 25 questions. The goal was to handle user data (registration), track progress in real-time, and display a competitive leaderboard.


This project was a big learning curve for me because I introduced external libraries to handle complex logic:

jQuery for DOM Power: I used jQuery to handle all the transitions—hiding the start screen, showing questions, and updating the progress bar without the user ever having to refresh the page.

Lodash for Data: I used Lodash to manage the question sets. It made shuffling questions and picking random categories much easier than writing everything in vanilla JS.

Dynamic UI: The progress icons (the SVGs you see in the code) change as the user moves through categories: Numeracy, Literacy, Health, Scottish History, and Social Awareness.

The Timer & Leaderboard: I implemented a countdown timer to add pressure and a table-based leaderboard to store and display results.


SVG is huge: You might see a massive block of SVG code in my HTML. Looking back, I learned that keeping SVGs directly in the HTML makes it messy, and in future projects, I’d probably move them to separate files or use a sprite sheet. But it was a great exercise in understanding how vector graphics work in the browser.

State Management: Keeping track of which question the user is on, their current score, and how much time is left was a challenge. It taught me how to think about "state" before I even started learning React.

Validation: I added basic validation for the username and email fields because I realized you can't have a leaderboard if people don't enter their names!


HTML5 & CSS3 (with a "Glow on Hover" effect)

jQuery (for interactivity and transitions)

Lodash (for data manipulation)

FontAwesome & Google Fonts
