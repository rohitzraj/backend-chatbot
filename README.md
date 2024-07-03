# Gemini Backend Application

## Overview

This is a simple backend application built using Node.js and Express.js. It utilizes Google's Generative AI to process and respond to chat messages. The application sets up a server with a single endpoint to handle chat messages.

## Features

- Express server running on port 8000.
- CORS enabled for handling cross-origin requests.
- JSON request body parsing enabled.
- Integration with Google Generative AI (Gemini Model).

## Prerequisites

Before running the application, ensure you have the following installed:

- Node.js (v14 or higher)
- npm (v6 or higher)

## Installation

1. Clone the repository to your local machine.
   ```sh
   git clone <repository-url>
   cd <repository-directory>``
2. Install the dependencies.
	```sh
	npm install
3. Create a `.env` file in the root directory and add your Google Generative AI API key
GOOGLE_GEN_AI_KEY=your_api_key_here

## Usage
```sh
npm run start:backend
