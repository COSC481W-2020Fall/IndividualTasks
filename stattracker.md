## week of Nov. 30 - Dec. 7
### Alex
(Catch up on tasks) Page allows multiple decks to be viewed
- [ ] Have interactive elements to allow the user to page between decks
- [ ] Show graphs for multiple stats if needed
- [ ] Display useful trends to user on page
- [ ] Create meaningful information from the data collected (Does not have to be displayed to page yet)

### Kris
- [ ] Streamline building process
  - [ ] Add search to card list
  - [ ] Put add button next to card in list
  - [ ] Put delete button next to card in list
  - [ ] Error when adding nonexistent cards
  - [ ] Error when 'deckname' is not filled in (the other error messages work, that's the only field I couldn't get an error message for
  - [ ] Clean up error message format
  
### Tristan
- [x] Dont allow cards to be added if they do not exist

### Domenic
- [x] bug fixes (need to be more specific)

## week of Nov. 16 - Nov. 30
### Alex
(Catch up on tasks) Page allows multiple decks to be viewed
- [ ] Have interactive elements to allow the user to page between decks
- [ ] Show graphs for multiple stats if needed
- [ ] Display useful trends to user on page
- [ ] Create meaningful information from the data collected (Does not have to be displayed to page yet)

### Tristan
- [ ] Action dropdown resets every time you execute an action, it would be nice if it just stayed on the last one I picked. Same with the deck choice. (Create a last action, last deck selected option and set the dropdown menus to display these.)
- [ ] Deck Builder (suggestion: users): When page is refreshed, “Select Deck” seems to default to most recent deck instead of deck that was just modified
- [x] Card count in deck shows as a decimal, I assume there’s no fractional card counts (Cast fractional card counts as int)

### Domenic
General:
- [x] Text not behind a white background is slightly hard to see with some of the website background images
- [x] Potentially adding a how to play page to help assist people (like me) who don't know how to build a competent deck
- [x] Navbar (bug): Font and margins inconsistent across pages

Data Input Page:
- [x] In DataInputpage - the font color is blended with the background color and hard to read
- [x] Entering invalid deck code on Data Input Page gets an internal server error
- [x] On data input page it would be nice to have a dropdown to select the deck built from the deck builder
- [x] And on data input page you could display win/loss

### Kris
- [x] Click the build deck without filling out the fields causes an internal error (create an error message)
- [x] You can add nonexistent cards (create error message)
- [x] Error when trying to add NaN to deck
- [x] Change cardCode to Card ID
- [x] Streamline building process
  - [x] Add search to the card list
  - [x] Put add button next to card in list
  - [x] Put delete button next to card in deck
- [x] General error messages
- [x] When selecting deck, show the deck name and not folder in file extension

## week of Nov. 9 - Nov. 16
### Domenic
- [x] Add navigation bar to the stat viewer page and a button to the stat viewer page get them connected with all the other pages (The navigation bars will have the new button for the new page and will be able to send you there on all the pages along with a new button on the home page that will direct you to our new page.)

### Tristan
- [x] Create a feature to export deckcode from deckbuilder. (Create an action to export deckcode for the current deck in the deckbuilder page. This will allow users to import and export decks from runterra.)

### Kris
- [x] Create MySql database
  - [x] Create a mySql database, preparing to switch over our current database (which uses SQLite) to mySql
  - [x] Create and set up the server
  - [x] Look into how to connect it to aws

### Alex
- [ ] display useful trends to user on page: comparing decks' win counts, comparing cards win counts

## week of Nov. 2 - Nov. 9
### Tristan
- [x] Condense current deck to show number of copies of each card.

### Demenic
- [x] Clean up Data Input Page so that you can add champions one at a time instead of having them there all on load.

### Kris
- [x] Set up the database so it's not modified locally? (Look into moving it to mySql?)

### Alex
- [ ] Have interactive elements to allow the user to page between decks
- [ ] Show graphs for multiple stats *if needed*

## week of Oct. 26 - Nov. 2
### Kris
- [x] Set up a method to add a new deck to users own list of decks to database
- [x] Create an id for new users
- [x] Create a new user table if not already created
- [x] Set up a method to grab that deck list by user id

### Tristan
- [x] Decrease unnecessary inputs to page

### Domenic
- [ ] Move the project to an AWS server

### Alex
- [x] Generate initial statistics (win rate, card usage, etc.) to prepare for displaying them to the user

## week of Oct. 19 - Oct .26
### Domenic
- [x] Home page will have a button for all 3 of our web pages.
- [x] Each page will have a navigation bar to make it easier to navigate our website.

### Tristan
- [x] Use API in order to convert a deck code into a list of cards and create a deck by that.

### Kristal
- [x] When 'none' is selected, it's ignored when adding to the database
- [x] Confirmation message when the game is successfully added to the database. 

### Alex
- [ ] Generate initial statistics (win rate, card usage, etc.) to prepare for displaying them to the user


## week of Oct. 12 - Oct .19
### Domenic
- [x] Initial page and background (webpage, background, and layout)

### Tristan
- [x] Create a form with a field for each piece of data: select deck, opponent region, opponent champions, win or loss

### Kristal
- [x] Link the input form to the database so it updates a table which stores all of this information

### Alex
- [ ] Generate initial statistics (win rate, card usage, etc.) to prepare for displaying them to the user

