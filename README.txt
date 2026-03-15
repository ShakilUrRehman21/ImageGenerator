#  AI Image Generator

An AI-powered web application that generates images based on user prompts.
Users simply enter a text description, and the AI generates a corresponding image.

---

##  Features

*  Generate images using text prompts
*  Fast API communication between frontend and backend
*  Simple and responsive UI
*  REST API integration for image generation

---

##  Tech Stack

**Frontend**

* JavaScript
* Axios

**Backend**

* Node.js
* Express.js

---

##  Dependencies

The project uses the following dependencies:

* **nodemon** – Automatically restarts the server during development
* **dotenv** – Manages environment variables
* **express** – Backend framework for building APIs
* **cors** – Enables cross-origin requests
* **axios** – Handles HTTP requests
* **stream-browserify** – Stream support for browser environments

---

##  Installation

Clone the repository:

```bash
git clone https://github.com/your-username/ai-image-generator.git
cd ai-image-generator
```

Install dependencies:

```bash
npm install
```

---

##  Running the Project

### Start Backend

```bash
npx nodemon server
```

### Start Frontend

```bash
npm run start
```

---

##  Usage

1. Start both the backend and frontend servers.
2. Open the frontend application in your browser.
3. Enter a prompt describing the image you want.
4. The AI will generate and display the image.

Example prompt:

```
A futuristic city at sunset with flying cars and neon lights
```

---

##  Project Structure

```
ai-image-generator
│
├── backend
│   ├── server.js
│   └── routes
│
├── frontend
│   ├── src
│   └── public
│
├── .env
├── package.json
└── README.md
```

---

##  Environment Variables

Create a `.env` file in the root directory and add your API keys:

```
API_KEY=your_api_key_here
```

---

##  Future Improvements

* Image download feature
* Prompt history
* Image gallery
* Multiple AI model support
* Better UI/UX
