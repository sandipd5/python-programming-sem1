# Game Support Chatbot

This project is designed to classify and provide answers to game-related questions using machine learning techniques. The model identifies the intent of the questions based on tags and delivers appropriate responses.

## Dataset

The dataset used in this project includes three main columns:
- `tags`: List of tags related to the question (e.g., `pause`, `timescale`)
- `intents`: The question asked by the user (e.g., `How can I pause my game?`)
- `answer`: The response to the question (e.g., `In the Editor, you can just click the pause button.`)

Example:
| tags            | intents                 | answer                                         |
|-----------------|-------------------------|------------------------------------------------|
| [pause, timescale] | How can I pause my game? | In the Editor, you can just click the pause button. |

## Requirements

Install the required dependencies using the following command:
```bash
pip install -r requirements.txt
