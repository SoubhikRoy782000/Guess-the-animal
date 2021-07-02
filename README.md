# Guess-the-animal

Aim -

To implement knowledge representation schemes by developing optimized technique to detect  the animal and if the prediction fails it adds to the knowledge tree and restarts the questionnaire  with the updated knowledge tree.


Algorithm -

STEP 1 – Create a knowledge tree for all questions to be asked with an animal directing to the correct and wrong answer.

STEP 2 – Add nodes with different questions to arrive to an animal based on it’s characteristics.

STEP 3 – Ask questions from the knowledge tree.

STEP 4 – For every answer, move deeper in the knowledge tree to ask the next question.

STEP 5 – When arriving to the end of a branch, output a prediction:

a. If the prediction is correct, ask for a new game.

b. If the prediction is wrong, ask for the animal and a relevant question to arrive at the animal and add to the knowledge tree.

STEP 6 – Restart questionnaire with the updated knowledge tree.
