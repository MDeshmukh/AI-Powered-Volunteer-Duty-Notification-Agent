# AI-Powered-Volunteer-Duty-Notification-Agent

## Overview
An AI-assisted automation tool built with Google Sheets, Google Apps Script, and the Gmail API to streamline volunteer duty notifications for both volunteers and coordinators. This project uses LLM-powered prompt engineering for rapid prototyping, optimized email templates, and polished documentation — cutting development time significantly.

## Features
1. Automated daily email reminders to volunteers and coordinators.
2. Separate custom message templates for different recipient groups.
3. Dynamic content generation based on Google Sheets data (name, date, phone number, duty type).
4. Error handling for smoother execution and fewer delivery failures.
5. LLM-assisted development:
   1. Used ChatGPT for code scaffolding and logic optimization.
   2. Prompt-engineered message templates for clarity and engagement.

## Tech Stack
1. Google Sheets – Data storage and schedule management.
2. Google Apps Script – Automation logic and email handling.
3. Gmail API – Sending personalized notifications.
4. Large Language Models (LLMs) – ChatGPT for code generation, debugging, and content optimization.

## How It Works
1. Google Sheet Setup - List volunteers/coordinators, their dates of duties, and mail ids.
2. Trigger Configuration - Automated Mail trigger runs daily (or on demand).
3. Dynamic Email Generation
   a. Personalized messages with names, dates, and phone numbers to volunteers.
   b. Coordinator-specific messages from a separate function.
4. Error Logging - Any failed sends are logged for quick review.

## Impact
1. 100% accuracy in volunteer reminders.
2. ~1 hr/day saved in manual coordination work.
3. Seamless scale-up to larger volunteer rosters.
4. Development time cut in half using LLM-assisted coding.

## Future Enhancements
1. WhatsApp API integration for multi-channel reminders.
2. Dashboard in Google Data Studio for duty tracking.
3. LLM-generated schedule summaries for event heads.

