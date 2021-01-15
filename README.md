# filmspot-personal-project
app which  presents the user with lists of trending and top rated movies, allowing the user the search and favourite movies, and view movie details like who directed it which year it came out etc when clicking on a movie.

Features:
implements the recommended architectural pattern(single activity with fragments)and uses android architecture components like viewmodel, room, livedata.
-seperation of concernes- created a network request class which communicates with an API(movie db open source API) via Volley, and sends data to a repository class which then sends data to a viewmodel, and fragments only communicate with the viewmodel class
-implements a youtube framework which allows for more customization options when playing the trailer for a movie.
-search function which updates the results in a recyclerview with every new letter typed
-allowing the user to favourite a movie which will be stored in a sql database, the list can be viewed when clicking on account button in toolbar

it's a work in  progress, featerus will be added,and certain things tweaked.

