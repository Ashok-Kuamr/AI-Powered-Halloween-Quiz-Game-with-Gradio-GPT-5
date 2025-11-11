# AI-Powered-Halloween-Quiz-Game-with-Gradio-GPT-5

🎃 AI-Powered Halloween Quiz Game

👻 Overview

The AI-Powered Halloween Quiz Game is an interactive web app that generates spooky Halloween-themed quiz questions using OpenAI’s GPT-5-nano model.

With a simple and fun interface built using Gradio, players can:

Pick a quiz category (like Haunted Places, Urban Legends, or Horror Movies)

Play through multiple-choice questions

Use lifelines like 50-50 to remove two wrong options

Earn points for each correct answer

All questions are AI-generated — no static database needed!

🧩 Features

🎭 Dynamic AI-Generated Questions: Each quiz session is new and unique.

🕹️ Interactive Gameplay: Includes lifelines, scoring, and feedback.

🎨 Simple, Web-Based UI: Built with Gradio for instant browser play.

🔒 Runs Anywhere: Works both in the cloud and on your local machine.

☁️ Running on IBM Skills Network Cloud IDE

If you’re using the IBM Skills Network Cloud IDE, you don’t need to set up any API keys manually.

The environment already includes secure access to the OpenAI GPT-5-nano model, so the app can connect to it automatically.

Steps:

Create a new folder in your workspace:

mkdir game
cd game


Create a new file named app.py and paste the provided project code.

Install dependencies:

pip3 install openai gradio


Run the app:

python3 app.py


Once running, you’ll see something like:

Running on local URL: http://127.0.0.1:7860
Running on public URL: https://xxxxx.gradio.live


Click on the public URL to open the quiz in your browser.
If it doesn’t open automatically:

Go to the Skills Network Server panel

Click Launch Application

Enter port 7860 and click “Your Application”

That’s it — no API key setup needed! 🪄

💻 Running Locally on Your Own System

If you’d like to run this project on your local computer, you’ll need your own OpenAI API key.

1️⃣ Get an API Key

Go to https://platform.openai.com/

Sign in and navigate to View API keys

Copy your personal key (looks like sk-xxxxx...)

2️⃣ Add Your Key to the Environment

Before running the app, open your terminal and set the key like this:

🪟 For Windows:
setx OPENAI_API_KEY "your_api_key_here"

🍎 For macOS / Linux:
export OPENAI_API_KEY="your_api_key_here"


(Make sure to replace "your_api_key_here" with your actual key.)

3️⃣ Install Dependencies
pip install openai gradio

4️⃣ Run the App
python app.py


Then open the provided local URL (e.g., http://127.0.0.1:7860) in your browser to start playing.

🧠 How It Works

The app sends your selected quiz topic to GPT-5-nano, which returns a set of multiple-choice questions in JSON format.

These are displayed dynamically in the browser using Gradio.

Your score updates in real time as you answer questions.

If GPT fails to respond, the app automatically uses built-in fallback questions, so gameplay never stops.

🎯 What You’ve Built

You’ve created a complete, AI-driven web application that combines:

Natural language generation

Interactive web design

State management and user engagement

It’s a fun and practical project showcasing how AI + Gradio can be used to create educational or entertainment apps quickly and easily.

🏁 Conclusion

Congratulations! 🎉
You’ve built and deployed your AI-Powered Halloween Quiz Game — powered by OpenAI GPT-5-nano and Gradio.

Now share your quiz with friends and challenge them to test their Halloween knowledge 👻

💡 Tip: You can easily extend this project for other themes (e.g., “Christmas Trivia” or “Movie Quizzes”) by changing the quiz categories!
