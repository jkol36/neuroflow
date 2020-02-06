For this project, please create a small backend REST API which fulfills the requirements written below:


Create a single public git repo to host your project and then commit & push to that repo once per story. If you need to push more than once that's okay, it just makes it easier to review if it's once per story.
Feel free to develop however you normally would. Please use Python, but besides that you can make use of whatever frameworks and 3rd party libraries you think make sense for this project.
If you have any questions feel free to reach out, but specific direction is up to you.
When you're finished, please send back the link to the GIT repo with your completed work.
 

Requirements:
 

Create a web REST application with a '/mood' endpoint, which when POSTed to persists the submitted mood value.
 

Add the ability for users to login.
 

Update the '/mood' endpoint with a GET method, so it only returns values submitted by the logged-in user.
 

Add to the body of the response for the ‘/mood’ endpoint the length of their current "streak".
A user is on a “streak” if that user has submitted at least 1 mood rating for each consecutive day of that streak.
For example, if on March 1st, March 2nd, March 3rd, and March 5th the user entered mood ratings, a 3-day streak will apply to the March 3rd rating and the streak will reset to a 1-day streak for the March 5th rating.
 

Calculate the user's streak's percentile compared to other users, and if the percentile is >= 50%, return that percentile in the ‘/mood’ endpoint
A users’ longest streak is defined as the largest number of consecutive days that a user has submitted mood ratings. Compare this user’s streak to all other users’ longest streaks to determine the percentile.
 

Containerize your application
Set up your application for containerization such that it can be run on any machine that supports the containerization technology (e.g., Docker).
 

Document what, if anything, you would do differently if this were a production application and not an assessment? What tech would you use? How would you handle things differently if it needed to handle more users, more data, etc.?