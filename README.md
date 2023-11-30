# GPT-Journey Interactive Story Game

## Overview

This project utilizes OpenAI's GPT-3.5 model to create an interactive story game where users make choices presented by the AI and see the consequences of those choices in an ongoing narrative.

## Features

- Allows users to interact with the AI story game by selecting options presented by the system.
- Dynamically generates storylines and options based on user choices.
- Incorporates Flask framework to create a web-based interface for the game.

## Setup

### Prerequisites

- Python 3.x
- OpenAI API key
- Flask

### Installation

1. Clone the repository:

    ```
    git clone https://github.com/your-username/gpt-journey.git
    cd gpt-journey
    ```

2. Install dependencies:

    ```
    pip install -r requirements.txt
    ```

3. Set up OpenAI API:

    - Replace `'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'` in the code with your own OpenAI API key.

4. Run the application:

    ```
    python app.py
    ```

## Usage

1. Access the application via a web browser at `http://localhost:5001`.
2. Read the instructions provided by the AI to start the game.
3. Make selections by clicking on the options presented.
4. Observe the continuation of the story based on your choices.

## Notes

- The project is in active development, and additional features or improvements may be added.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgements

- OpenAI for their GPT-3.5 model and API.
