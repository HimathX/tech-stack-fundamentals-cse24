Reddit Browser - Task Instructions
Time: 2-3 hours | Difficulty: Beginner-Friendly

Overview
Build a working Reddit browser that fetches real data from Reddit API, displays posts in a beautiful grid, and lets users search any subreddit.

By the end, you'll have:

✅ Fetching data from APIs

✅ Beautiful UI with CSS Grid

✅ Search functionality

✅ Responsive design (mobile + desktop)

Step 0: Setup Local Server (Important!)
⚠️ Read this first!

Before starting, you need to run a local server to avoid CORS errors when fetching from Reddit.

Option A: Python (Recommended)
Open terminal in your project folder and run:

bash
# Python 3
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000
Then open your browser: http://localhost:8000

✅ This solves CORS issues!

Option B: VS Code Live Server
Install "Live Server" extension in VS Code

Right-click index.html

Click "Open with Live Server"

✅ Automatically opens at http://localhost:5500

Option C: Node.js
bash
npx http-server
Then open: http://localhost:8080

Step 1: Basic Setup (5 min)
Goal: Create HTML file and open in browser.

Create a file named index.html with basic HTML structure including a heading.

Test:

Run your local server (see Step 0)

Open http://localhost:8000 (or your port)

You should see the heading. ✅

Step 2: Fetch Reddit Data (15 min)
Goal: Get real Reddit posts using JavaScript.

Add a script that:

Creates a URL pointing to Reddit's r/programming subreddit

Uses the fetch() function to get data

Converts response to JSON

Logs data to console

Test:

Press F12 to open Developer Tools

Go to Console tab

You should see Reddit data! ✅

What you'll learn:

Async/await

Fetch API

JSON parsing

Step 3: Display Posts as List (20 min)
Goal: Show post titles on webpage.

Add to your HTML:

A container div with id posts-list

Basic CSS styling for list items

JavaScript function to loop through posts and display titles

Test: You should see list of Reddit posts. ✅

Key concepts:

DOM manipulation

forEach() loop

appendChild()

Step 4: Beautiful Post Cards (25 min)
Goal: Show posts with images, upvotes, comments in a grid.

Update your page to:

Display posts as cards (not list)

Use CSS Grid layout for responsive design

Show thumbnail image for each post

Display post title

Show stats: upvotes, comments, author name

Add hover effects for better UX

Test: You should see beautiful grid of posts with images. ✅

Key concepts:

CSS Grid

Template literals

Object destructuring

Step 5: Add Search (20 min)
Goal: Let users search any subreddit.

Add to your page:

Input field for subreddit name

Search button

Update the fetch URL dynamically based on user input

Handle errors gracefully

Test:

Try searching: webdev, python, javascript

Invalid subreddit should show error ✅

Key concepts:

Event listeners

String interpolation

Error handling

Optional Challenges
Challenge 1: Dark Mode (⭐⭐ Easy)
Add a toggle button that switches between light and dark theme. Save preference using localStorage.

Challenge 2: Click to Open (⭐⭐ Easy)
Make post cards clickable so users can open the original Reddit post in a new tab.

Challenge 3: Load More (⭐⭐⭐ Medium)
Add a "Load More" button to fetch additional posts pagination.

Challenge 4: Favorite Posts (⭐⭐⭐ Medium)
Let users bookmark favorite posts and save them using localStorage.

Challenge 5: Post Preview (⭐⭐⭐ Medium)
Display first 150 characters of post content as preview text.

Submission
Step 1: Create Folder
Navigate to Task 02/submissions/ and create a folder with your name in format: First_Name_Last_Name

Step 2: Save Your Work
Save your index.html inside your folder.

Path should be: Task 02/submissions/Your_Name/index.html

Step 3: Commit and Push
Stage your changes with git add

Commit with clear message

Push to GitHub repository

Submission Checklist
 Folder name format: First_Name_Last_Name

 File name: index.html

 Can search different subreddits

 Posts display with images

 No console errors

 Works on mobile devices

 Successfully pushed to GitHub

What You'll Learn
HTML & CSS:

Semantic HTML structure

CSS Grid layout

Responsive design

Hover effects

JavaScript:

Fetch API

Async/await

DOM manipulation

Event listeners

Template literals

APIs & Full-Stack:

How APIs work

JSON data

Error handling

Real-world data integration

Troubleshooting
Posts not showing?

Check browser console for errors

Make sure you're running a local server (Step 0)

Verify subreddit name is correct

CORS Error?

You must run a local server (see Step 0)

Cannot open file directly (file://)

Images broken?

Not all Reddit posts have images (that's normal)

Use error handler to hide broken images

Search not working?

Check spelling of subreddit

Try popular ones: programming, webdev, python

Cannot push to GitHub?

Verify you have write access to repository

Check git remote URL is correct

Useful Reddit Data
Each post from the API contains:

Title - Post heading

Upvotes (ups) - Number of likes

Comments (num_comments) - Number of replies

Author - Username who posted

Thumbnail - Image URL

Permalink - Link to view on Reddit

Resources
MDN Web Docs - JavaScript and HTML/CSS reference

JavaScript.info - Modern JavaScript tutorial

Reddit API Docs - Official API documentation

CSS-Tricks - CSS Grid guide

Popular Subreddits to Try
r/programming

r/webdev

r/learnprogramming

r/javascript

r/python

r/memes

r/funny

r/todayilearned

Deadline
Submit by: 26th December 2025

Have fun building! 🚀