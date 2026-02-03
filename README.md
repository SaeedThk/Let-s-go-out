# Will You Be My Valentine?

Welcome to the "Will You Be My Valentine?" project, a playful and interactive way to ask that special someone the big question this Valentine's Day. Hosted as a GitHub Page, this project offers a unique blend of creativity and technology to make your Valentine's Day proposal unforgettable.

## Overview

"Will You Be My Valentine?" is a web-based application that starts by asking "Will you be my valentine?". Once they say "Yes", it transforms into a full interactive date planner. Users are guided through selecting a date, food, desserts, and activities, with every choice sent directly to you via email.

## Features

- **Interactive Question**: The core of the project is the interactive Valentine's Day proposal.
- **The "No" Button Trick**: If the user attempts to click "No", the button evades them or the "Yes" button grows, playfully forcing a positive response.
- **Date & Activity Planner**: A multi-step form that lets your Valentine choose the Date, Food Menu, Dessert, and Post-Dinner Activities.
- **Instant Email Notifications**: Powered by Formspree, you receive an email notification immediately after every selection is made.
- **Responsive Design**: Crafted to look great on both desktop and mobile devices.

## Technology

This project is built using simple yet powerful web technologies:
- HTML
- CSS
- JavaScript
- **Formspree** (for handling form submissions and emails)

## How to View

To experience "Will You Be My Valentine?", simply visit [https://akshitbhalla15.github.io/Valentine/](https://akshitbhalla15.github.io/Valentine/) from any modern web browser.

## How to Customize (For Developers)

If you fork this repository to use for yourself, you must update the email handling to work for you:

1. **Create a Formspree Account**: Go to [Formspree.io](https://formspree.io) and create a new form to get your unique endpoint URL.
2. **Update the Forms**: In `index.html`, `date.html`, `food.html`, `dessert.html`, and `activities.html`, replace the `action` URL in the `<form>` tag with your own Formspree link.
3. **Update Redirects**: Change the `_next` hidden input value in each file to match your own GitHub Pages URL structure.

## How to Contribute

Contributions to the "Will You Be My Valentine?" project are more than welcome. Whether it's suggesting new features, improving the design, or fixing bugs, here's how you can contribute:

1. **Fork the Repository**: Start by forking the project repository on GitHub.
2. **Clone Your Fork**: Clone your fork to your local machine for development.
3. **Create a New Branch**: Make a new branch for your changes.
4. **Make Your Changes**: Implement your feature, fix, or improvement.
5. **Commit Your Changes**: Commit your changes with a clear and descriptive commit message.
6. **Push to Your Fork**: Push your changes up to your fork.
7. **Open a Pull Request**: Back on GitHub, open a pull request from your fork to the main project.

## Support

If you encounter any issues or have questions about the project, feel free to open an issue on the GitHub repository.

# Valentine