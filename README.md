
🚀 PayFlow AI: Automated Payment Scheduler
​PayFlow AI is an AI-powered payment scheduler built for the PayPal AI Hackathon. It connects an AI frontend to automate payouts, automatically logs transaction audit trails on Google Calendar, and sends high-priority confirmation receipts to Gmail.
​🛠️ Tech Stack
​Frontend: Bolt.new (AI-generated dashboard & user interface)
​Backend & Automation: Zapier (Webhooks, Custom Delay, & PayPal API)
​Verification & Audit: Google Calendar (Audit Logging) & Gmail API (Confirmation Receipts)
​✨ Key Features
​AI Frontend Scheduling: Easily schedule payouts and automated transactions through an intuitive AI-driven dashboard.
​Delayed Background Execution: Securely processes automated workflows and transactions after a specified custom delay.
​Automated Audit Logging: Instantly blocks and logs transaction schedules directly onto Google Calendar.
​Smart Receipts: Automatically dispatches high-priority confirmation emails straight to your inbox upon execution.
​🔄 How It Works
​The user submits payout details through the Bolt.new dashboard.
​A webhook securely triggers the Zapier backend automation pipeline.
​Zapier holds the trigger using a custom delay step, executes the PayPal transfer, logs the event onto Google Calendar, and dispatches a confirmation email marked important.
