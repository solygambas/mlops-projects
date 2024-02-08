# Sentiment Analysis - Node

A simple Node.js API that uses Transformers.js for sentiment analysis.

## Getting Started

1. Clone the repo and enter the project directory:
   ```bash
   git clone https://github.com/solygambas/mlops-projects.git
   cd 00-playground/01-tansformersjs/06-node
   ```
1. Install the necessary dependencies:

   ```bash
   npm install
   ```

1. Run the server:

   ```bash
   npm run start
   ```

1. Send a request:

   ```bash
   curl http://127.0.0.1:3000/classify?text=I%20love%20Transformers.js
   ```

   You should get `[{"label":"POSITIVE","score":0.9994831681251526}]`

## Features

- setting up the project.
- creating a basic HTTP server.

Based on [Building a Vanilla JavaScript Application](https://huggingface.co/docs/transformers.js/tutorials/vanilla-js) by Transformers.js (2023).
