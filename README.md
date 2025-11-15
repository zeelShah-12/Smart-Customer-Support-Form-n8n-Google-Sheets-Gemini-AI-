# Smart-Customer-Support-Form-n8n-Google-Sheets-Gemini-AI

ConnectCare is a simple and efficient customer-support intake workflow built using n8n, Google Sheets, and Gemini AI.
It helps businesses collect customer issues, validate missing details through AI, and respond automatically.

This project is perfect for companies that don’t have full customer-support systems and rely on Instagram or phone calls for communication.

🚀 Features
✅ Smart Form Submission

Customers submit:

Name

Email

Phone Number

Problem / Message

Instagram ID

The information goes directly into Google Sheets.

✅ AI-Powered Validation (Gemini)

Gemini checks:

Which fields are missing

Whether the request is understandable

Whether the submission is complete or incomplete

Output example:

status: complete
missing: none


or

status: incomplete
missing: phone number, message

✅ Auto-Routing With IF Node

Based on Gemini’s output:

Complete submissions → send success email / store data

Incomplete submissions → ask customer to provide missing details

✅ Google Sheets Integration

Stores and organizes all responses in a clean sheet:
| Name | Email | Phone | Problem | Instagram ID | submittedAt |

✅ Expandable Workflow

You can easily add:

WhatsApp notifications

Telegram alerts

CRM integration

Auto-reply bots

🧩 How the Workflow Works

Webhook / Form Trigger
Sends all form data to n8n.

Google Sheets Node
Saves all the raw data.

Gemini AI Node
Analyzes missing fields + submission clarity.

IF Node
Checks Gemini’s status output.

Two Paths:

Complete → send thank-you message / forward to support

Incomplete → send missing-details request

Link:https://zeelshah1205.app.n8n.cloud/form/f508eac1-a0fc-48ff-9215-538bdb4b5737

<img width="588" height="194" alt="ai2-1" src="https://github.com/user-attachments/assets/c39cc999-c448-4944-90bb-f2441bfae9a0" />
<img width="456" height="646" alt="ai2-3" src="https://github.com/user-attachments/assets/7b9e0e8c-2900-43ba-828f-bf74d1ccdb1c" />
<img width="582" height="209" alt="ai2-2" src="https://github.com/user-attachments/assets/af40ee03-cc41-4d73-96c9-0e10895c78ce" />
