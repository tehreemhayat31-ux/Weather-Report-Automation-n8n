# Weather-Report-Automation-n8n
This project is an automated weather report generator built using n8n. It retrieves weather forecast data, parses it to extract the high and low temperatures for the current day, and generates a natural language weather summary.

The workflow:

Fetches hourly temperature data from a weather API.

Filters the temperatures for the current date.

Calculates the highest and lowest temperatures.

Outputs a formatted message, for example:
“In Islamabad, the high today is 32°C and the low is 24°C.”

This automation can be easily extended to:

Send daily weather updates via email, Slack, or Telegram.

Support multiple locations dynamically.

Run on a schedule to deliver daily reports automatically.
