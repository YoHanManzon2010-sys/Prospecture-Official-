# TODO: Change "Next Question" to "Finish Test" for last question in Science quizzes

## Task: 
In the Science quizzes, when giving a message to the last number (question 10) when answered, make it say "Finish Test", unlike the other 1-9 which is "Next Question"

## Files to Edit:
1. [x] physics.html - Updated showFunFactPopup function
2. [x] biology.html - Updated showFunFactPopup function
3. [x] chemistry.html - Updated showFunFactPopup function
4. [x] earth-science.html - Updated showFunFactPopup function

## Implementation:
- Check if current === quiz.length - 1 (last question)
- If last question: show "Finish Test" button text
- Otherwise: show "Next Question ➜" button text

## Status: COMPLETED ✅

