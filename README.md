# Getting Started with *PARTNER HERO SPOITIFY INTEGRATION* REACT App


Runs the app in the development mode.\
Open [https://serene-chamber-55859.herokuapp.com/](https://serene-chamber-55859.herokuapp.com/) to view it in your browser.

This is the front end development of the application, which runs with the backend development \
Open [https://lit-dawn-26115.herokuapp.com/](https://lit-dawn-26115.herokuapp.com/) 
developed using Node.

## Caution
*Please not the config.env file has been removed from the git repository as instructed. It will be forwarded to assessment supervisor as an email*

## Database
The database used fo this was MongoDB NoSQL.

## Deployment
Using Heroku, Deployment was made possible after installing create-react-app-buildpack by mars buildpack on the application service,
more information about this service through here \ 
Open [https://github.com/mars/create-react-app-buildpack](https://github.com/mars/create-react-app-buildpack)

## Implementations
* Login Screen through Spotify’s authentication method.
* Logout methods.
* Display all song descriptions within the “New Releases” and “My Library” in the form of thumbnail previews with their respective album art, title and action button
* Display all song descriptions within the result section on the home screen in the form of rows alongside their action button.
* Save only the necessary user and songs information within Firebase *(mongoDB was used instead)*
* Ability to see and remove any of the songs saved to “My Library” from anywhere they may be accessible from (as for example, the results within the Home Page and the New Releases section).
* Ability to see and add any of the songs from New Releases and Search Results.
* Ability to be able to scale the application by changing the window’s dimension without ruining the proposed design (Mobile friendly).
* Display proper error messages when the HTTP request cannot be completed.
* Unit testing for the functionality.

## Limitations
The following were not acheivable due to limited time
* Export “My Library” to my Spotify account as a new playlist.
* Save “My Library” data into the redux store while it is being used in the app.
* Typescript as a template for your React project.
* Persisting favorited data on a NoSQL Database (Firebase, Mongo, etc.).

## Addtions that could have been added if available time was not limited
* Feedback response when a song is added or removed from My Library
* A sort for "New Release" to get songs that are and/ or not in my Library
