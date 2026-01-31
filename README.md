# AI Knowledge Inbox

Authored by Satvik Akkaraju

> Note: Documentation for Design Decisions are placed in the respective repositories
> This README.md only contains Setup instructions

## Table of Contents

- [Backend](github.com/akkaraju-satvik/AI-Knowledge-Inbox-backend)
- [Frontend](github.com/akkaraju-satvik/AI-Knowledge-Inbox-frontend)
- [Setup](#setup)

### Setup

Clone the repositories

```bash
git clone --recurse-submodules git@github.com:akkaraju-satvik/AI-Knowledge-Inbox.git
```

#### Ollama/Mistral:7B

1. Ensure Ollama is available on the device

  ```bash
  ollama --version
  ```

2. Pull the Mistral 7B model.

```bash
ollama pull mistral:7b
```

#### Backend

1. `cd` into the backend directory and install the dependencies.

```bash
cd backend/
pip3 install -r requirements.txt
```

2. Run the application using `python3 main.py`

#### Frontend

1. `cd` into the frontend directory and install the dependencies.

```bash
cd frontend/
npm install
```

2. Run the development using `npm run dev`.
