# TriviaApp
Trivia quiz App. This app contains trivia questions parsed from a JSON file from a remote server. This project is composed of three Activities, which include: Main, Trivia, and Stats Activities.

Part 1: Main Activity
The Main activity is responsible for the loading of the trivia contents (questions and answers) included in the JSON web service located at this address:
http:// dev.theappsdr.com/apis/trivia_json/index.php. Used Async task threads to process data.

There is a countdown timer that starts once the user starts the first question. After taking the quiz, the user will be sent
directly to the “Stats” activity. 

Clicking on finish button shows a percentage score of correctly answered questions.

http://square.github.io/picasso/ was used to load images from the JSON file into the app.
