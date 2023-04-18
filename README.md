# Turbo Giggle
## a Real-time Distance Tracker for Strava and Garmin

This project allows you to fetch real-time distance data from Strava and Garmin for multiple accounts and display it on a web page.

## Usage

1. Clone the repository to your local machine
2. Open either one of the HTML files (`strava-live-view.html` or `garmin-live-view.html) in your web browser
3. Enter the start and end times for the event, the update interval, the number of accounts to fetch data for, and the access tokens
4. Click the "Start" button to start fetching data, and the "Stop" button to stop fetching data

## Notes

- The access tokens for Strava and Garmin must be obtained separately from their respective developer portals
- The web page will display the total distance traveled by all accounts, as well as the individual distances and times for each account
- The data is updated at the specified interval, and the total distance traveled is cumulative from the start time to the end time
- The web page is designed to work with up to 5 accounts, but this can be adjusted in the HTML code
- The HTML code is written using JavaScript and requires a modern web browser with support for the Fetch API and the ES6 syntax
