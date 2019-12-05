## Deployment Instructions For Mac:

1. Do 'Start virtualenv' and navigate where you want to store the code

2. After logging in to your server, use git clone https://github.com/computationalmystic/sengfs19-group9/tree/Sprint4/Sprint%204 to download our repository.

3. Mkdir 'ProjectName' & then cd 'ProjectName'

4. Inside that folder, create a folder a new virtualenv. Do virtualenv env.

5. Activate virtualenv

6. source env/bin/activate

7. It's up and running.

## Testing: 
Used manual testing of website to debug and assess any errors 

## Acceptance Criteria for Nav Bar 
As a user, I want to be able to navigate to different pages, so that I may login, and view other data with a clear navigation system
1. When I click on home in the navbar it will display home page data
2. When I click on profile in the navbar it will display my data based on which profile I have used to login; Data will include 3 graphs, and a list of the repositories
3. If I try to access the profile page without having logged in prior, the page will redirect me to the login page before I can proceed
4. When I hover over the augur logo on the top right corner, a dropdown will appear with the option to logout or login; should I click the button to login it will take me to the login page, should I click the button to logout the page will redirect me to the home page and the augur logo will change from green to red to indicate a change in login status

## Acceptance Criteria for Profile Page
As a user, I want to view my profile, so that I may see a contributions per user in a pie graph, a bar graph of contributors over the last 6 months, a bar graph of weekly pull rate over the last 6 months, and a list of repositories in a dropdown menu
1. To view a full list of the repositories you can click on the dropdown button on the right hand side of the page that will show the full list of repos

## Acceptance Criteria for Home Page
As a user, I want to view the home page when first visiting the website, and when I click on the home tab in the navbar, so that I will see Augur information, a bar graph for contributors in each repo group, a youtube video explaining Augur, with a link to login

## Acceptance Criteria for Login Page
As a user, I want be able to login to my respective repository group, so that I may see data on my profile page after logging in that reflects data pertinent to my work
1. To login on the login page using GraphQL credentials type username “graph” and password “pass”; To login on the login page using Zephyr credentials type username “zephyr” and password “pass”
2. If username or password are incorrectly entered a popup alert will show “Sorry! The username or password you have entered is incorrect, Please try again”
3. If correct username and password are entered the page will redirect the user to the home page, and the augur logo will update from red to green in the top right corner indicating a successful login

## Acceptance Criteria for About, Contact, and Settings Tabs
As a user, should I navigate to the About or Contact tab on the navbar, I will see an image explaining the site is under construction (To be updated later)

As a user, should I click on the settings button on the navbar, the button will be disabled until further testing has taken place to adjust “dark mode” properties
