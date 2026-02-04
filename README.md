# appointment_setter
A dual-workflow automation system that synchronizes Google Sheets with Gmail to deliver personalized booking calendars. It handles real-time appointment scheduling via webhooks, updates Google Calendar, and sends instant confirmation alerts to Telegram.


# Appointment Setter: Automated Booking & Notification System

A professional automation suite built with **n8n** to streamline professional service bookings and client management. This system eliminates manual scheduling by connecting client data with interactive booking tools.

### Integrations
* **Google Sheets:** Source of truth for client sessions and info.
* **Gmail:** Automated delivery of dynamic booking calendars.
* **Google Calendar:** Instant event creation upon client selection.
* **Telegram:** Real-time push notifications for the coach.

### Key Features
* **Dynamic HTML Buttons:** In-email booking links generated via custom JavaScript.
* **Session Tracking:** Automated logic to display availability based on remaining sessions.
* **Dual-Workflow Architecture:** Separates the "Invitation" phase from the "Confirmation" phase for maximum stability.
