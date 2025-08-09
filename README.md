# Servicenow-to-telegram-Integration-
This project integrates ServiceNow with Telegram to send real-time alerts for high-priority incidents. Using the Telegram Bot API, it automatically delivers incident details to a designated Telegram chat or group whenever a high-priority (P1) incident is created in ServiceNow

Key Features:
Triggers only for P1 (High Priority) incidents
Uses Business Rule for automation
Sends notifications via RESTMessageV2 to Telegram
Includes incident number, short description, and urgency in messages
Improves response time by notifying teams instantly

Tech Stack:
ServiceNow (Business Rules + RESTMessageV2)
Telegram Bot API
