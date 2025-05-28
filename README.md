# Quizzler App

A modern quiz application built with Python and Tkinter that tests your knowledge through a series of questions. The app features a clean user interface, score tracking, and immediate feedback on answers.

## Features

- Interactive quiz interface with True/False questions
- Real-time score tracking
- Visual feedback for correct and incorrect answers
- Progress tracking through the quiz
- Clean and modern UI design
- HTML entity support for special characters in questions
- Case-insensitive answer checking

## Requirements

- Python 3.x
- Tkinter (built into Python standard library)

## Installation

1. Clone this repository:

```bash
git clone https://github.com/momed-ali/quizzler_app.git
cd quizzler_app
```

2. Run the application:

```bash
python main.py
```

## Project Structure

- `main.py`: Entry point of the application
- `quiz_brain.py`: Core quiz logic and scoring system
- `question_model.py`: Question data model
- `data.py`: Quiz questions and answers database
- `ui.py`: User interface implementation
- `images/`: Directory containing UI assets

## How It Works

1. The application loads questions from the data source
2. Questions are presented one at a time
3. Users can select True or False as their answer
4. Immediate feedback is provided for each answer
5. Score is tracked throughout the quiz
6. Final score is displayed upon completion

## Quiz Brain Logic

The `QuizBrain` class handles:

- Question progression
- Score tracking
- Answer validation
- HTML entity decoding for special characters

## Contributing

Feel free to submit issues and enhancement requests!

## License

This project is licensed under the MIT License - see the LICENSE file for details.
