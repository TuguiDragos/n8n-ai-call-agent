<p align="center">
  <a href="https://n8n.partnerlinks.io/cpqi2mcvtjxx"><img src="https://img.shields.io/badge/Built%20with-n8n-2088FF?style=flat-square&logo=n8n" alt="n8n"></a>
  <img src="https://img.shields.io/badge/AI-OpenAI-424242?style=flat-square&logo=openai" alt="OpenAI">
  <img src="https://img.shields.io/badge/Voice-Vapi-8B5CF6?style=flat-square&logo=audiomack&logoColor=white" alt="Vapi">
  <img src="https://img.shields.io/badge/Telephony-Twilio-F22F46?style=flat-square&logo=twilio" alt="Twilio">
  <img src="https://img.shields.io/badge/Data-Google%20Sheets-34A853?style=flat-square&logo=google-sheets&logoColor=white" alt="Google Sheets">
  <img src="https://img.shields.io/badge/status-live-brightgreen?style=flat-square" alt="Status">
  <a href="https://tuguidragos.com"><img src="https://img.shields.io/badge/visit-tuguidragos.com-blue?style=flat-square&logo=google-chrome" alt="Website"></a>
  <a href="https://github.com/TuguiDragos/n8n-ai-call-agent/blob/main/LICENSE"><img src="https://img.shields.io/badge/license-MIT-yellow?style=flat-square" alt="License"></a>
</p>

<h1 align="center">🤖 n8n-ai-call-agent</h1>

<p align="center">
  <a href="https://tuguidragos.gumroad.com/l/n8n-ai-call-agent" target="_blank" style="text-decoration:none;">
    <strong>🛒 View on Gumroad – Download the Workflow</strong>
  </a>
  <br/><br/>
  <a href="https://youtu.be/xgDPP_hJ7ms" target="_blank" style="text-decoration:none;">
    <strong>▶️ Watch the Demo Video on YouTube</strong>
  </a>
</p>

<p align="center"><strong>✅ Tested on 100+ real phone leads! Fully functional & battle-tested.</strong></p>


## 📚 Table of Contents
- [Features](#-features)
- [Requirements](#-requirements)
- [Use Cases – Where This AI Call Agent Shines](#-use-cases--where-this-ai-call-agent-shines)
- [Why This Beats Manual Calling](#-why-this-beats-manual-calling)
- [Visual Overview (Screenshots)](#-visual-overview-screenshots)
- [FAQ – Questions you’re probably asking yourself](#-faq--questions-youre-probably-asking-yourself)
- [How It Works – Step-by-Step Flow](#-how-it-works--step-by-step-flow)
- [Why This Works](#-why-this-works)
- [License](#-license)
- [About the Creator](#-about-the-creator)
- [Tags & SEO](#-tags--search-keywords)


## ⚙️ Features

- 📞 Calls leads automatically using AI voice assistant  
- 🧠 Understands natural language and extracts key info (like email)  
- ✉️ Saves call transcript, summary, and contact info into Google Sheets  
- 🔁 Retry logic for missed calls or unanswered leads  
- 🔔 Slack notifications for every call: missed or successful  
- 📊 Live monitoring using Vapi Dashboard & Twilio logs  
- 🔄 Sheet refresh between calls for data consistency  
- 🧩 Fully no-code thanks to n8n visual builder  

---

## 🔧 Requirements

- n8n (self-hosted or cloud)  
- Google Service Account (for Google Sheets integration)  
- Slack Bot (for notifications)  
- [Vapi.ai](https://vapi.ai) account (for voice agent)  
- Twilio phone number (for call handling)  

---

## 🎯 Use Cases – Where This AI Call Agent Shines

This isn’t just a fancy workflow. It’s a real solution to real problems. Whether you're a freelancer, run an agency, or manage a SaaS startup, this system can save you hours of manual work and increase your efficiency like never before. Here are some real-world scenarios where it delivers serious value:

---

### 🏪 1. Local Business Outreach (Digital Agencies)
**Scenario**: You run a small digital marketing agency offering services like website builds, SEO, or booking systems.  
**Use**: Upload a list of local businesses without websites or proper digital presence. The agent calls them, collects their email, and asks if they’d be interested in receiving an offer or demo.  
**Real impact**: Perfect for salons, barbershops, restaurants, dental clinics — businesses that rarely respond to cold emails but always pick up the phone.

---

### 🧑‍💻 2. Freelancers Doing Cold Outreach
**Scenario**: You're a solo freelancer offering services like automation, web design, copywriting or AI integrations.  
**Use**: Collect a list of potential clients from LinkedIn, directories or Google Maps. Let the bot call them and ask if they're interested in your services. You receive a Slack ping with the result and the client's email, without lifting a finger.  
**Why it works**: It removes the awkward first contact and builds instant intrigue through voice.

---

### 🛍️ 3. E-commerce Follow-up System  
**Scenario**: You have an online store and want to follow up with customers who abandoned carts or didn’t respond to support emails.  
**Use**: Use the agent to call those customers and ask if they still want the product or if they need help completing the order.  
**Result**: Personalized customer support at scale, without hiring a full team.

---

### 🚀 4. SaaS Pre-Qualification Calls  
**Scenario**: You run a SaaS platform and get daily sign-ups. Your team can’t follow up with everyone fast enough.  
**Use**: This agent calls every new user, confirms their email, asks their interest level, and logs everything. Ideal for scoring leads and routing only hot ones to your human sales team.  
**Boost efficiency**: Saves time and filters noise before human contact.

---

### 💼 5. Service Booking Confirmation  
**Scenario**: You're running a booking-based business (car service, spa, coaching) and need to confirm appointments.  
**Use**: The AI agent automatically calls clients to confirm their appointment time, gather missing info, or remind them of what to bring.  
**Impact**: No-shows drop, and your calendar stays full.

---

### 📞 6. Follow-up for Inbound Leads (Lead Nurturing)  
**Scenario**: You run Facebook or Google Ads and get form submissions.  
**Use**: Instead of just sending emails, the agent calls them, confirms info, and asks about interest - then updates your CRM or sheet.  
**Result**: Leads are contacted instantly, increasing your conversion rate.

---

**The truth?** This isn’t some experimental gimmick. It’s a fully capable AI phone agent that can handle the job of a real sales rep. No breaks, no burnout, no excuses.

If your work involves people, leads, or outreach, this system will save you hours, lower your stress, and keep your pipeline flowing effortlessly.

---

## 📸 Visual Overview (Screenshots)

### 🔂 Full n8n Workflow  
Everything from sheet read to Slack update, visualized in one place.

![Workflow Full](https://raw.githubusercontent.com/TuguiDragos/n8n-ai-call-agent/main/Workflow.png)

---

### 🧩 Workflow Overview — Part 1  
Main process: load sheet, validate leads, send call to Vapi.

![Workflow 1](https://raw.githubusercontent.com/TuguiDragos/n8n-ai-call-agent/main/Workflow%201.png)

---

### 🔁 Workflow Overview — Part 2  
Post-call logic: extract email, update status, and notify Slack.

![Workflow 2](https://raw.githubusercontent.com/TuguiDragos/n8n-ai-call-agent/main/Workflow%202.png)

---

### 📝 Full Transcript Logging  
Everything the AI says and hears is saved in Google Sheets.

![Transcript](https://raw.githubusercontent.com/TuguiDragos/n8n-ai-call-agent/main/Transcript.png)

---

### ☎️ Twilio Call Logs  
Call stats, durations, and statuses shown in real time.

![Twilio Logs](https://raw.githubusercontent.com/TuguiDragos/n8n-ai-call-agent/main/Twilio.png)

---

### 🎯 Custom Agent Prompt (Vapi)  
Voice agent trained to understand broken or slow English, ask smart questions, and confirm data.

![Vapi Prompt](https://raw.githubusercontent.com/TuguiDragos/n8n-ai-call-agent/main/Vapi%20System%20Prompt.png)

---

### 📊 Vapi Dashboard  
Monitor call volumes, durations, and call-end reasons.

![Vapi Dashboard](https://raw.githubusercontent.com/TuguiDragos/n8n-ai-call-agent/main/Vapi.png)

---

### ✉️ Email Extraction with Regex  
AI extracts spoken email even when said as “tugui dragos at gmail dot com”.

<img src="https://raw.githubusercontent.com/TuguiDragos/n8n-ai-call-agent/main/Extract%20email.png" alt="Email Extraction" width="600"/>

---

### 📞 Real Phone Calls  
AI agent calls leads using real phone numbers via Twilio/Vapi.

<img src="https://raw.githubusercontent.com/TuguiDragos/n8n-ai-call-agent/main/Phone%20Call.png" alt="Phone Call" width="300"/>

---

### 🔔 Slack Notifications  
Slack updates for both missed and successful calls.

![Slack Notification](https://raw.githubusercontent.com/TuguiDragos/n8n-ai-call-agent/main/Slack.png)

---


## ❓ FAQ – Questions you’re probably asking yourself

**Is it hard to set up?**  
🛠️ Not at all. The workflow is pre-configured and ready to go. You just plug in your accounts (Vapi, Twilio, Google Sheets, Slack), and you’re ready to test in under 10 minutes.

**Can I test it before going live?**  
📞 Yes! You can manually trigger the workflow and send a test call to your own phone. That’s the best way to see how it behaves before using it on real leads.

**Does it work in other languages?**  
🌍 Definitely. As long as Vapi and your AI model support the language, you can easily adapt the prompt to speak and understand different languages.

**What happens if someone doesn’t answer the call?**  
🔁 No worries! The system catches that. It sends a Slack notification letting you know the lead didn’t pick up, and you can retry or follow up later.

**Can I customize the messages or logic?**  
🧩 Of course. Everything is visible and editable in n8n. You can tweak Slack messages, the AI’s voice prompt, email logic.. anything you want.

**Do I need to self-host n8n?**  
☁️ Nope. You can use n8n cloud (with a free account), or host your own if you want full control.

**Does it require coding?**  
👨‍💻 Not really. It’s all visual. You only need a tiny bit of JavaScript if you want to tweak the email extraction or advanced conditions.. and that’s already included.

**Any costs involved?**  
💰 Vapi gives you free minutes every month. Twilio charges a few cents per call. Most tests will cost you almost nothing.

---

## ⚙️ How It Works – Step-by-Step Flow

This AI-powered voice agent workflow is made up of 25 nodes, each playing a specific role in automating phone-based lead processing. Here’s a breakdown anyone can understand:

### 1. Start & Load Leads
- **Manual Trigger**: You manually start the workflow.
- **Load Lead Sheet**: Reads a list of leads from Google Sheets.
- **Filter Valid Leads**: Filters out leads that have already been processed.
- **Has Leads to Process?**: Checks if there are any valid leads left. If not, the workflow ends.

### 2. Prepare the Call
- **Clean Phone Number**: Formats the phone number to be compatible with Twilio/Vapi.
- **Create Customer in Vapi**: Initializes a customer profile in Vapi.
- **Initiate Call**: Sends the lead’s number to Vapi to begin the AI-powered voice call.
- **Loop Setup Variables**: Sets internal variables for retry logic and status tracking.

### 3. Monitor the Call (Loop Section)
- **Set Attempt Counter**: Starts counting how many attempts have been made.
- **Get Call Status**: Checks the current status of the AI call.
- **Check Final Status**: Determines if the call is complete or should continue.
- **Should Continue? (IF)**: Decides whether to loop again or move on.
- **Wait (3 seconds)**: Pauses briefly before the next check.
- **Prepare Loop Payload**: Refreshes loop variables for the next iteration.

### 4. Handle the Result
- **Get Call Data**: Pulls detailed information from the call (transcript, audio, etc).
- **Set: Parse AI Response**: Extracts reply, category, tone, etc. from the AI's output.
- **IF: Was the Call Answered?**: Branches based on whether someone answered the call.

### 5A. If No One Answered
- **Update Lead (No Answer)**: Marks the lead in Google Sheets as "No Answer".
- **Notify Slack (No Answer)**: Sends a Slack alert that the lead didn't respond.

### 5B. If the Call Was Successful
- **Extract Email**: Uses regex + JS to extract a valid email from the spoken transcript.
- **Update Lead (Completed)**: Logs all call data, email, and status as "Processed".
- **Notify Slack (Success)**: Sends a detailed Slack message with summary + audio.

### 6. Refresh for Next Lead
- **Wait Before Sheet Refresh**: Short pause to allow Google Sheets update.
- **Sync Updated Sheet**: Reads the updated lead list again.

### 7. Wrap Up (if No Leads Remain)
- **Slack - All Done**: Sends a final Slack message when all leads are processed.

---

Each node has been carefully configured and tested to ensure smooth, reliable execution without errors. Whether someone answers the phone or not, the system knows exactly what to do next. All actions are logged and monitored, fully automated, zero guesswork.

## 💡 Why This Works

While cold emails go unread and DMs get ignored, phone calls still win attention. But no one has time to call 50+ leads a day! and that’s where this system shines.

This AI call agent combines:

- 🗣️ Human-like voice interaction through Vapi  
- 🧠 Intelligent understanding with OpenAI  
- 📞 Reliable phone delivery via Twilio  
- 📊 Live lead tracking inside Google Sheets  
- 🔁 Automated retry & logic branching via n8n  
- 🔔 Real-time Slack updates so you’re always in the loop  

The result? A system that sounds human, thinks smart, and works non-stop.

Instead of:
- Spending hours dialing numbers
- Chasing leads manually
- Forgetting to follow up

You:
- Launch the workflow
- Go make a coffee ☕
- Return with leads sorted and emails collected

This works because it's built for one thing: **hands-free lead processing that doesn’t suck.**

Simple. Clean. Smart.

---

## ⚖️ License

This project is released under the **MIT License** — simple, open, and flexible.  
You’re free to use it, modify it, improve it, and even sell it - as long as proper credit is given.  
For full terms, see the [LICENSE](https://github.com/TuguiDragos/n8n-ai-call-agent/blob/main/LICENSE) file.

---

## 👋 About the Creator

Created by **Tugui Dragoș** 



🌐 Website: [tuguidragos.com](https://tuguidragos.com)  
📬 Email: contact@tuguidragos.com  

---

💬 Have questions? Want this workflow customized for your business?

[→ Contact Me](mailto:contact@tuguidragos.com) • [→ Visit tuguidragos.com](https://tuguidragos.com)

---

**If this project helped or inspired you:**  
Leave a ⭐, share it with your crew, or reach out for collabs, custom builds, or smart automation work.


---

## 🧩 Tags & Search Keywords

n8n AI call workflow, AI phone agent automation, lead generation automation, voice call automation with Vapi, Twilio voice workflow, Google Sheets + n8n integration, OpenAI GPT smart caller, cold outreach AI bot, no-code SDR system, lead qualification voice AI, call follow-up automation, Slack notifications from calls, smart CRM data capture, phone bot with email extraction, n8n lead pipeline automation, automated voice campaigns, SaaS lead validation tool, freelancer cold call automation, digital agency voice outreach, customer support AI phone bot, Vapi n8n integration, Twilio Vapi smart call bot, call transcription automation, AI call workflow for Google Sheets, automation for client onboarding, conversational AI phone workflow, intelligent voice workflows with no-code, hands-free AI call solution, async sales assistant automation, AI rep that never sleeps, real-time lead qualification tool

Looking for something that can automate voice calls, capture lead data, and respond intelligently all without writing a single line of code?  
This AI voice agent powered by **n8n**, **Vapi**, **Twilio**, **OpenAI**, and **Google Sheets** is exactly what you need.
