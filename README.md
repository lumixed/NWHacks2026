# Travelio

A flight deal discovery app that shows the cheapest flights departing from your city, with AI-generated travel itineraries.

## What it does

- **Flight Discovery**: Finds the cheapest available flights relative to average monthly prices from your origin city
- **Deal Comparison**: Shows how much cheaper each fare is versus typical pricing
- **AI Itineraries**: Generates personalized travel itineraries via the Gemini API for any destination you pick

## Tech Stack

- **Frontend**: React + Vite, CSS (Albert Sans + Bricolage Grotesque via Google Fonts)
- **Backend**: Node.js (Express), Python
- **Data**: Amadeus Travel API (flight pricing), Gemini API (itinerary generation)

## Prerequisites

- Node.js
- Python 3.x
- Amadeus API credentials — [developers.amadeus.com](https://developers.amadeus.com/)
- Gemini API key — [ai.google.dev](https://ai.google.dev/)

## Setup

1. Clone the repository

   ```bash
   git clone https://github.com/lumixed/Travelio.git
   cd Travelio
   ```

2. Install frontend dependencies

   ```bash
   npm install
   ```

3. Install Python dependencies

   ```bash
   pip install -r requirements.txt
   ```

4. Create a `.env` file in the root directory

   ```env
   AMADEUS_API_KEY=your_amadeus_key
   AMADEUS_API_SECRET=your_amadeus_secret
   ```

5. Create a `.env` file in the `travel-itinerary` directory

   ```env
   GEMINI_API_KEY=your_gemini_key
   ```

## Running the App

Start the frontend:

```bash
npm run dev
```

Start the itinerary backend (separate terminal):

```bash
cd travel-itinerary
node server.js
```

Then visit the localhost URL shown in your terminal.

## How to Use

1. Enter your departure city or airport code in the search bar
2. Set the number of passengers
3. Browse the flight results sorted by best deal
4. Click "Itinerary" on any destination to generate an AI travel plan
5. Click "Book" to go directly to the airline's site

## Roadmap

- Public deployment
- Faster API response times
- Filtering by budget, airline, and trip length
- Saved searches and user accounts
- Hotel and activity recommendations alongside flights

## License

MIT
