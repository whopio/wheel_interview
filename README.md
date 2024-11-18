## Overview

Welcome to the Whop Wheel Rails Project.

In this project, you will be building a Rails application that allows users to spin a wheel to win prizes.


## Setup

1. **Create a GitHub Codespace:**
   - Click the "Code" button on the GitHub repository page.
   - Select the "Codespaces" tab.
   - Click "Create codespace on main".

2. **Once the Codespace is ready:**
   - The project will be automatically set up for you.
   - Run `bundle install` to install the dependencies.

3. **Start the Rails server:**
   - Run `rails server` to start the Rails server. It will run on port 3000.

> You can also run this all on your local machine if you'd like. You just need Rails and Ruby installed. It uses a SQLite database.

## Instructions

Your job is to build a REST API that will be used by the frontend to spin the wheel and display the results.


## Resources
Join this whop for an example at the wheel: https://whop.com/whop-eng-interview/


## Requirements
- Prizes can have different probabilities and limited stock. For example, we might want to give away only one PS5 a day but 10 Chipotle gift cards a day.
- Users get 1 spin a day, but it possible for the Whop team to give a user more spins if we want.
- A wheel should have multiple losers on it in order to make it more interesting.
- The user should see a list of all winners and their recently won prizes.
