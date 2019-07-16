# TriviaGame

Using Bootstrap for styling, maintain borders by centering a card to hold the game between col 3 &10. 

Have an intro header with game name and start button. The onClick() of the start button intiates setTimeout() and the timer is displayed in the middle of the game card. 

Several var = Questions are to be listed with answer options to be listed within [] and the correct answer specified. Some method of button must be employed here in order to allow the player to select an answer. The onClick for an answer will move the game forward, after each question has had an answer selected then the #submitButton will change state to allow it to be clicked.

If the #timeRemaining reaches zero then an "Times up!" alert will be dispayed and all unselected answers are counted as incorrect.

onClick of #submitButton or #timeRemaining = 0 will  reveal the results page and the #questionsAnswered, #correctAnswer, #incorrectAnswer stats will be listed on a new card as the quiz is removed. A formula can be written to show percentage of right answers at this point. Something like {Accuracy = math(#correctAnswer/#numQuestions)+"%"}