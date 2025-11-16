# Automatic-Vet-bill-tracker
This project automates tracking vet bills for my senior dog, Scotch. Since my aunt pays the bills, it ensures every expense is recorded accurately, eliminating manual tracking of frequent visits. This keeps all payments clear, organized, and easy to review for both of us.

![Diagram of N8N workflow](N8N%20workflow%20image.png)

## Features
* Automatically extracts vet bill details from PDF attachments in emails related to Scotch’s appointments.

* Uses an AI agent to interpret and clarify bill specifics (date, amount, provider, etc.) for accurate records.

* Posts all expense records directly into a dedicated Google Sheet for transparent, ongoing tracking.

* Instantly notifies your aunt whenever a new bill is recorded, ensuring she’s always up-to-date on Scotch’s vet expenses.

## Demo 

https://github.com/user-attachments/assets/749332fe-77ab-477c-9bd6-9e6859ccd971


*Only thing which is pending is the Whatsapp message going to my aunt as the recipent. Due to meta policies I have to wait for app to be authorised and have tested extensively with API but only hello world template message can be sent at this stage however will upload more!

## 🚦 Running the Project
1. Download my workflow
2. Ensure you have npm downloaded
3. Run npx n8n
4. Click 3 dots top right corner and select 'import from file'
5. Fill out your details and get access to relevant API keys (Gmail, Mistral OCR, OpenAI, Google Sheets, Whatsapp)

I will write a more comprehensive manner of getting this access if people are interested as it was a challenge at the start@
