# React Booking App

Booking front-end app using React. The home page has lists and search bar (destination, date range and other options). When you click the search button, the result page shows up and you can change search inputs or add other options. When you choose any hotel it will take you to the single hotel page where you can see it's details including the photo gallery of the hotel.


You can see the website [here](https://react-booking-12.netlify.app/)


This is one of three parts of full stack Booking app. You can find the Node.js/MongoDB REST API backend [here](https://github.com/adarraji/booking-node-api) and the React Booking Admin Dashboard [here](https://github.com/adarraji/booking-admin)


To run the application

1. Clone this repo
2. Run `npm install`
3. Run `npm start


## Built With

* HTML
* CSS
* Javascript
* React
* React Router
* React Hooks
* Font Awesome
* Custom hooks
* React Context


## Environmental Variables

Replace `process.env.REACT_APP_BACKEND_BASE_URL` with the backend api base url in:

* `src\components\reserve\Reserve.jsx`
* `src\hooks\useFetch.js`
* `src\pages\login\Login.jsx`


Example: `http://localhost:8800/api`

## Deployment

Deployed on [Netlify](https://netlify.com)
You can see the website [here](https://react-booking-12.netlify.app/)


## Authors

- **Ali Darraji** - [https://github.com/adarraji](https://github.com/adarraji)


## Deploy status
[![Netlify Status](https://api.netlify.com/api/v1/badges/8d760479-08e8-4e3c-9463-0d5129f2f718/deploy-status)](https://app.netlify.com/sites/react-booking-12/deploys)

## Screenshots