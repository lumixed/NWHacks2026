✈️ Travelio

Travelio helps travelers discover unusually cheap flight deals and generate AI-powered itineraries for spontaneous, budget-friendly adventures.

🌍 Inspiration

One of our team members loves to travel spontaneously—sometimes booking a trip without a destination in mind if the price is right. However, most travel platforms require users to specify a destination before searching for flights. We wanted to build a tool that surprises users with affordable travel opportunities, encouraging exploration beyond planned routes.

🚀 What Travelio Does

Given a user’s origin city, Travelio:

Finds and displays exceptionally cheap flight deals relative to monthly average prices

Highlights destinations offering the best value

Generates AI-powered travel itineraries using Gemini

This allows users to plan trips based on opportunity and curiosity rather than fixed destinations.

🛠️ Built With

React – Frontend framework

Python – Backend server

Amadeus Travel API – Flight price and route data

Gemini API – AI-generated travel itineraries

JavaScript, HTML, CSS – UI and interactivity

⚙️ Setup & Installation
Prerequisites

Node.js

Python

Git

Installation

Clone the repository:

git clone <your-repo-url>


Install Python dependencies:

pip install -r requirements.txt


Create a .env file in the main directory and add your Amadeus API credentials:

AMADEUS_API_KEY=your_key
AMADEUS_API_SECRET=your_secret


Create a .env file in the travel-itinerary directory and add your Gemini API key:

GEMINI_API_KEY=your_key

▶️ Running the Project

Install frontend dependencies:

npm install


Start the frontend:

npm run dev


Open the provided localhost link in your browser.

In a new terminal, start the Gemini API server:

cd travel-itinerary
node server.js


You can now search for flights and generate itineraries on the website.

🧩 Challenges

Handling slow response times from the flight data API

Integrating multiple APIs across frontend and backend

Coordinating asynchronous data fetching

🏆 Accomplishments

Built a fully functional travel discovery platform

Successfully integrated real-world APIs

Created a useful tool that encourages spontaneous travel

📚 What We Learned

Working with external APIs and environment variables

Full-stack collaboration using React and Python

Managing performance and async requests

🔮 What’s Next for Travelio

Deploy the application

Optimize API response times

Improve UI/UX and itinerary customization

Add user preferences and saved trips
