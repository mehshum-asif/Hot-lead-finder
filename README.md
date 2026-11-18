# Hot-lead-finder (n8n Workflow)

An AI automation that finds local businesses and writes personalized outreach for each one.

## What it does

1. You enter a niche (for example, "Dentists") and a city in a form.
2. It finds businesses on Google Maps using Apify.
3. It checks each business website for missing things: online booking, live chat, WhatsApp button, contact form, and mobile support.
4. Gemini AI gives each business an opportunity score (1-10), the best service to offer, and a personalized email and DM message.
5. Everything is saved to a Google Sheet.

## Tools used

n8n, Apify, Google Gemini, Google Sheets

## How to use

1. Import `Hot-lead-finder.json` into n8n.
2. Add your Apify, Gemini, and Google Sheets credentials.
3. Open the form, enter a niche and a city, and run the workflow.

## Built by

Mehshum Asif
Portfolio: https://mehshum-portfolio.vercel.app
