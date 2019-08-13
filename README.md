# FE-Exercise

Hey there candidate, we're going to build a little web page that will function as follows:
* There will be only a home page.
* The home page will have a docked header with your name on the left side of it.
* The rest of the page will display a scrollable list of notes.
* You will fetch the notes from a local server that we wrote for you (further information is in the technical section).
* Each note in the page will have an author name and description.
* On top of the notes, you can search for notes by author.
* When clicking on an item a modal will open (a dialog) that will show the following data:
	* The author name: not editable
	* The description: not editable
	* the body of the note: editable
	* updated at: not editable

	at the bottom of the modal you will add a cancel button and a save button.
* The page's layout should be responsive

Notes:
* The saved notes should be updated without refreshing it.
* The save button should send a request only when some data has changed.
* You need to implement the search functionality in the client.
* You can use additional packages to assist you.
* You will need to submit to exercise by mail to - royc@dropitshopping.com
* If you have ANY question, feel free to talk to us!

Bonus Points:
* Make the search a bit more efficient by not running she search functionality on any key press.

Technical instructions:
* Make sure you got npm installed on you computer
*
* Open a terminal, and navigate to the server directory
* Run node app.js to start your server
* Open another terminal to the client directory
* Run npm start to start the client

Server api:

GET "/notes/" - get all notes
GET "/notes/:id" - get a note by id
PATCH "/notes/:id" - update a note's body

after you have started the server, you can go to http://localhost:3006/notes and see the result in your browser

Enjoy this little exercise and good luck!