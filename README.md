# FlightSearch
Searching flight deals by using Python and API

.
├── data_manager.py          # Handles Google Sheet data (Sheety API)
├── flight_data.py           # Flight data model & cheapest flight logic
├── flight_search.py         # Amadeus API integration
├── notification_manager.py # Sends SMS/WhatsApp notifications
├── main.py                  # Main program execution
├── .env                     # Environment variables (not included)

⚙️ How It Works
Retrieve destination data from Google Sheets using Sheety
Get IATA codes for cities using Amadeus API
Search for flights based on user-defined dates
Find the cheapest flight using custom logic
Send notification if a cheap deal is found

DataManager
  Fetches and updates destination data from Google Sheets
FlightSearch
  Handles authentication and requests to Amadeus API
  Retrieves IATA codes and flight offers
FlightData
  Stores structured flight information
  Contains logic to find the cheapest flight
NotificationManager
  Sends alerts via Twilio (SMS or WhatsApp)


123123
