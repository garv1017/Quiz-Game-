Here’s the README file with an added explanation about the option shuffling feature on each refresh:

---

# Quiz Game

## Project Overview

This Quiz Game is a simple, interactive web-based application built with HTML, CSS, and JavaScript. It presents users with multiple-choice questions on various topics, tracking and displaying their score throughout the game.

![Screenshot 2024-11-06 122302](https://github.com/user-attachments/assets/40f99233-9fd3-4d3e-8ecb-f95e92639d23)

## Features

- **Multiple Questions**: Each quiz session includes a set of pre-defined questions stored in JSON format.
- **Answer Selection and Feedback**: Users can select an answer for each question. Correct answers increase the score, while incorrect answers incur a small penalty (-0.25 points). Users also have the option to skip a question if they are unsure of the answer, which does not impact the score.
- **Shuffled Options on Refresh**: Every time the quiz is refreshed, the options for each question are shuffled, adding variety to the experience.
- **Dynamic Question Loading**: Questions and answer options are dynamically loaded.
- **Responsive Design**: The quiz is designed to be responsive, adapting to different screen sizes.

## How It Works

1. **Question and Options Display**: Each question is presented with four answer options. Options are shuffled for randomness, and this shuffling happens every time the quiz is refreshed.
2. **Answer Selection**: Users can click on an option to answer the question. Correct answers increase the score by 1 point, while incorrect answers reduce it by 0.25 points. If users do not know the answer, they can skip the question by pressing "Next" without selecting an option, which will not affect the score.
3. **Navigation**: A "Next" button allows users to move to the next question. Once all questions are answered, a "Quiz Completed" message and the final score are displayed.

## Technologies Used

- **HTML** for structuring the page.
- **CSS** for styling, including responsive adjustments for different devices.
- **JavaScript** for functionality, including question navigation, scoring, shuffling of options on refresh, and user interactions.

## Project Structure

- **index.html**: Contains the structure and basic layout for the quiz game.
- **style.css**: Handles the styling, colors, and layout responsiveness.
- **quiz.js**: Contains the main logic, including question handling, scoring, shuffling of options on refresh, and user interactions.
- **assets/screenshot.png**: Screenshot of the game interface.

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/quiz-game.git
   ```
2. Open `index.html` in a web browser to start the game.

## Future Enhancements

- Adding more questions from a larger database.
- Implementing a timer for each question.
- Including difficulty levels or random question selection.

---

