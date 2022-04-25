* As a user, I want to be prompted what my name is so that my scores can be tracked
  * Use object constructor to make an object for user
* As a user, I want to be able to see my top five previous High Scores
  * While-loop to check if there are 5 highscores yet
    * If not, add score and name to array
  * Nested for-loop to check if recent score is better than those in array
    * If they are, .pop lowest score and name?
    * .push new score and name
  * If user score is not a new highschore display message saying "Better luck next time!"
  * Stretch:
    * Live top five highscores table displayed at bottom of page
    * High Score is tracked by TTC(Time To Complete) or TE(Total Errors)
* As a user, I want to be able to flawlessly switch between the game page, "About the Devs" page, and "Meet our Pets" page without losing previous highscores
  * Store Highscores in LocalStorage
* As a user, I want to be notified when I choose two cards that don't match.
  * Use while loop to determine when two cards are chosen
  * Use if statement to determine if cards match or not
  * If they don't, alert "Those don't match!, Try again."
  * Flip chosen cards back over
  * Stretch: 
    * wrongCounter++
* As a user, I want to be notified when I choose two cards that do match.
  * Use while loop to determine when two cards are chosen
  * Use if statement to determine if cards match or not
  * If they do, alert "Nice job! Only i more matches to go!"
  * Make cards correct cards disappear or noticeably different
* As a user, I want 
* As a developer, I want cards a user clicks to turn over and display an image so that the user can know what image is where.
* As a developer, I want two cards that do not match to turn back over so that the cards can be reselected
  * Stretch: Counter to track when user chooses two cards that don't match
* As a developer, I want each round to have which sets of pets to be randomized.


