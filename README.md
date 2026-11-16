# Medical Chatbot

A Python project workspace for developing a medical-information chatbot.

## Current status

**Early scaffold — not a working medical chatbot yet.** The application entry point, helper modules, prompt module, and dependency list are currently empty. This repository is not ready for diagnosis, treatment decisions, or emergency use.

## Planned development

1. Define the chatbot's scope and safety boundaries.
2. Build the application interface and configuration.
3. Add a model/provider integration without hard-coding API keys.
4. Add safe fallback behavior and clear medical disclaimers.
5. Test input handling, provider failures, and safety responses.
6. Document setup and deployment only after the app is verified.

## Current structure

```text
medical-chatbot/
├── app.py
├── requirements.txt
├── setup.py
├── src/
│   ├── __init__.py
│   ├── helper.py
│   └── prompt.py
└── research/
```

## Development setup

Use Python 3.10 or newer. Create a virtual environment with `python -m venv .venv`. Activate it and install dependencies after they are added to `requirements.txt`.

## Safety

This project is for education and software development. It must not claim to diagnose conditions or prescribe medication, and it must direct users to qualified healthcare professionals for medical decisions.
