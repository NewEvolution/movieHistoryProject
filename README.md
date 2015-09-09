#Movie History Project

Group exercise in taking another groups previous project and refactoring the foreign code to meet new requirements.

####Original project:

Utilize the OMDb API (http://www.omdbapi.com/) to retrieve movies, add them to a list, provide ratings & a status of watched or unwatched.

####Refactored project:
- Two views, one for wishlist of to-watch movies, one for already watched movies with star-bar ratings.
- Search bar in menu that searches watched movies, unwatched movies, and returns any other movies that match the searched value via the OMDb API
- Choosing a movie from the API adds it to the wishlist
- Clicking watched on a wishlist movie moves it to the watched view and allows it to be rated
- Unwatched movies can be removed from the wishlist, but watched movies cannot be unwatched/removed
- Site must be mobile responsive

Makes use of Firebase https://www.firebase.com/ for data storage.

###Requirements:
- Node.js https://nodejs.org/en/
- Installation of http-server via _npm install -g http-server_

###Post-clone Installation:
- inside the main repo directory:
 - run _bower install_
 - run _npm install_
 - run _http-server_
 - make note of the port number returned after running _http-server_
- navigate to http://localhost:[your-port-number]