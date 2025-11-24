# Nirmaan --- Communication Skills Scorer

Nirmaan is an AI-powered web application that analyzes
**self-introduction transcripts** and provides instant scores across key
communication skill criteria.\
It uses rule-based checks, NLP-inspired logic, grammar analysis,
coherence detection, and a clean UI to deliver actionable feedback.

# Features

-   **Instant transcript analysis** --- paste or type and get results
    immediately\
-   **Scoring across 8 criteria**:
    -   Salutation\
    -   Keywords / Introduction Essentials\
    -   Flow & Coherence\
    -   Speech Rate\
    -   Grammar\
    -   Vocabulary\
    -   Filler Words\
    -   Sentiment\
-   **Coherence and gibberish detection**\
-   **Progress bars** for each criterion\
-   **Responsive light-mode design**\
-   **Fully client-side** (HTML/CSS/JS --- no backend)

# Live Demo

Experience the app here:\
**https://nirmaan-cyan.vercel.app/**

# How It Works

1.  Enter or paste a transcript.\
2.  Click **Analyze Transcript**.\
3.  The system evaluates:

### Evaluation Includes:

-   Presence of introduction essentials (name, age, education, hobbies,
    goals, etc.)\
-   Logical flow and coherence\
-   Word count and estimated speech rate\
-   Grammar and vocabulary richness\
-   Sentiment and enthusiasm\
-   Filler word frequency\
-   Detection of gibberish, random text, or off-topic content

Scores for each category are calculated and adjusted based on coherence.

# Running Locally

Clone the project:

    git clone https://github.com/ParvTiwari/Nirmaan.git

Run the app by simply opening:

    index.html

No installation or dependencies required.

# Requirements

-   Modern browser (Chrome, Edge, Firefox)\
-   No build tools, no framework --- pure HTML, CSS, and JavaScript

# File Structure

    Nirmaan/
    │── index.html     // Main application UI + scoring logic
    │── style.css      // Responsive light-mode styling
    └── README.md      // Documentation

# Usage

-   Paste your introduction or use **Load Sample**\
-   View detailed scoring across all 8 criteria\
-   See penalties applied for incoherence or gibberish\
-   Use feedback to improve your communication skills

# Deployment

This project is deployed on **Vercel**:\
**https://nirmaan-cyan.vercel.app/**

To deploy yourself: 1. Upload the project to GitHub\
2. Import the repository into Vercel\
3. Deploy --- Vercel automatically serves static files
