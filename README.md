# Weather Teller ⛅️

![IMG_3933](https://user-images.githubusercontent.com/58259611/147996130-02c9d6a2-f2dd-4d56-954d-77aa8ffc5c27.jpeg)

## Introduction
A simple web app project built to review Ajax/JQuery and API integration and to have fun with designing characters in the app.

### Purpose
This app allows you to look at the current weather anywhere in the world by clicking locations on the displayed map or manually adding longitude/latitude values.
Based on the current weather, the potato character will change to reflect the weather!

### Demo

Sample demo of the weather page:

How the webpage looks currently as of 5/26:

I decided to change the background designs completely after seeing that the background was "drawing too much attention" from the user and hence a simpler design !

*The video may be a bit laggy*

<img src=https://github.com/ac-hj/weather-teller/blob/master/demo/weather-app-demo-v2.gif alt="drawing" width="1000"/>

### How to use
1) Sign up for Google Maps and OpenWeatherMap APIs -- both are free to use 
2) Replace "[Your API Key]" with yours in weatherpage.ejs file
3) Run `node app.js` on the terminal and go to http://localhost:8080/ on browser

## Tech Stack
- Node.js
- Express
- EJS
- Ajax/JQuery
- HTML/CSS
- Procreate

## APIs
- Bootstrap
- Google Maps API
- OpenWeatherMap API

## Design Credits
- Main page background design was inspired by Art with Flo (https://www.youtube.com/watch?v=RzH3DCvsTx0&t=270s&ab_channel=ArtwithFlo)
- Potato character design was inspired by Angela Kalokairinou (https://www.youtube.com/watch?v=RBUr9RdMMik&ab_channel=AngelaKalokairinou)

##  Next Steps
- [x] Add 7-day weather forecast feature (5/21)
- [x] Add celsius/farenheit change (5/21)
- [x] Add more potato character designs to account for other different weathers. Currently there are sunny, cloudy, and rainy (5/25)

UPDATED (5/21): Now has 7-day forecast feature + fahrenheit/celsius conversion!

UPDATED (5/25): Snow designs fully added now!

<img src=https://github.com/ac-hj/weather-teller/blob/master/demo/snow-demo.png alt="drawing" width="140" height="250"/>

## Random learnings:
- To delete some commit histories, do git log, git rebase git rebase -i <commit_hash>, and then change pick to drop. and then push?
https://stackoverflow.com/questions/30893040/git-remove-commit-from-history
- also git reset --hard doesn't work sometimes :(( gets confusing when using different branches

## Before the design makeover

<img src=https://github.com/ac-hj/weather-teller/blob/master/demo/demo-vid.gif alt="drawing" width="500"/>


  <img src=https://github.com/ac-hj/weather-teller/blob/master/styles/forecast.png alt="forecast" width="500"/>



