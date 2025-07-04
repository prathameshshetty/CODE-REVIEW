# AI Code Reviewer – Backend

This is the Express backend for the AI Code Reviewer project. It exposes REST endpoints for code review, integrating with Google Gemini AI to generate feedback.

## Features

- **REST API:** Receives code submissions and returns AI-generated reviews.
- **Google Gemini Integration:** Uses the `@google/genai` package.
- **CORS Enabled:** Allows requests from the frontend.
- **Environment Variables:** API keys and secrets managed via `.env`.

## Tech Stack

- [Node.js](https://nodejs.org/)
- [Express](https://expressjs.com/)
- [@google/genai](https://www.npmjs.com/package/@google/genai)
- [dotenv](https://www.npmjs.com/package/dotenv)
- [cors](https://www.npmjs.com/package/cors)

## Setup

1. **Install dependencies:**
   ```sh
   cd BackEnd
   npm install
   ```

2. **Configure environment variables:**
   - Copy `.env.example` to `.env` (if provided) or create `.env`:
     ```
     GEMINI_API_KEY=your_google_gemini_api_key
     ```

3. **Start the server:**
   ```sh
   node server.js
   ```

4. **API Endpoint:**
   - `POST /ai/get-review`  
     Body: `{ "code": "<your code here>" }`

## Project Structure

- `server.js` – Entry point
- `src/app.js` – Express app setup
- `src/routes/ai.routes.js` – API routes
- `src/controllers/ai.controller.js` – Request handlers
- `src/services/ai.service.js` – Gemini AI integration

---
