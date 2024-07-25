# AIMockSter

## Features

- **Next.js and React**: Robust frontend framework for building scalable web applications.
- **Clerk Authentication**: Implements social and email/password authentication for secure access.
- **Tailwind CSS**: Utility-first CSS framework for rapid UI development.
- **PostgreSQL and Drizzle ORM**: Efficient database setup and querying.
- **Google Gemini API**: Generates AI interview questions and processes user responses.
- **Speech-to-Text**: Converts recorded user answers into text.
- **Cloud Deployment**: Easily deploy your application on Vercel.

## Installation

To get started with the project, follow these steps:

1. **Clone the repository:**

    ```bash
    git clone https://github.com/Satyam5665/AiMockSter.git
    cd ai-mock-interviewer
    ```

2. **Install dependencies:**

    ```bash
    npm install
    ```

3. **Set up environment variables:** Create a `.env.local` file in the root directory and add your environment variables for Clerk, PostgreSQL, and Google Gemini API.

4. **Run the development server:**

    ```bash
    npm run dev
    ```

## Usage

- **Authentication:** Users can sign up or log in using social accounts or email/password through Clerk.
- **AI Interview Generation:** Generate interview questions using the Google Gemini API.
- **Answer Recording:** Users can record their answers using the web interface and their microphone.
- **Speech-to-Text:** The app converts spoken answers into text for analysis.
- **Save and Review:** Users can save their responses and review them later.

## Technologies Used

- **Frontend:** Next.js, React, Tailwind CSS
- **Backend:** Next.js API Routes
- **Database:** PostgreSQL, Drizzle ORM
- **Authentication:** Clerk
- **AI Integration:** Google Gemini API
- **Deployment:** Vercel
