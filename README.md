<!--
  README for n8n-ai-call-agent
  Screenshots in assets/ are pre-rounded PNGs with transparent corners.
  GitHub strips CSS from README files, so the corner radius has to live in the image.
-->

<img src="./assets/hero.svg" alt="AI phone call agent for n8n, built with Vapi, Twilio and Google Sheets" width="100%" />

<p align="center">
  <a href="https://n8n.partnerlinks.io/cpqi2mcvtjxx"><img alt="n8n" height="25" src="https://img.shields.io/badge/n8n-161826?style=flat&logo=n8n&logoColor=9184D9" /></a>
  <a href="https://vapi.ai"><img alt="Vapi" height="25" src="https://img.shields.io/badge/Vapi-161826?style=flat&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPGcgZmlsbD0ibm9uZSIgc3Ryb2tlPSIjOTE4NEQ5IiBzdHJva2Utd2lkdGg9IjIiIHN0cm9rZS1saW5lY2FwPSJyb3VuZCI%2BPHBhdGggZD0iTTMgMTB2NE03LjUgNi41djExTTEyIDN2MThNMTYuNSA2LjV2MTFNMjEgMTB2NCIvPjwvZz48L3N2Zz4%3D" /></a>
  <a href="https://www.twilio.com"><img alt="Twilio" height="25" src="https://img.shields.io/badge/Twilio-161826?style=flat&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPGcgZmlsbD0iIzkxODREOSI%2BPHBhdGggZD0iTTEyIDEuNkExMC40IDEwLjQgMCAxIDAgMjIuNCAxMiAxMC40MSAxMC40MSAwIDAgMCAxMiAxLjZ6bTAgMTguMkE3LjggNy44IDAgMSAxIDE5LjggMTIgNy44MSA3LjgxIDAgMCAxIDEyIDE5Ljh6Ii8%2BPGNpcmNsZSBjeD0iMTQuOSIgY3k9IjkuMSIgcj0iMi4yIi8%2BPGNpcmNsZSBjeD0iMTQuOSIgY3k9IjE0LjkiIHI9IjIuMiIvPjxjaXJjbGUgY3g9IjkuMSIgY3k9IjkuMSIgcj0iMi4yIi8%2BPGNpcmNsZSBjeD0iOS4xIiBjeT0iMTQuOSIgcj0iMi4yIi8%2BPC9nPjwvc3ZnPg%3D%3D" /></a>
  <a href="https://openai.com"><img alt="OpenAI" height="25" src="https://img.shields.io/badge/OpenAI-161826?style=flat&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPGcgZmlsbD0ibm9uZSIgc3Ryb2tlPSIjOTE4NEQ5IiBzdHJva2Utd2lkdGg9IjEuOSIgc3Ryb2tlLWxpbmVqb2luPSJyb3VuZCI%2BPHBhdGggZD0iTTEyIDIuNiAyMC4xIDcuM3Y5LjRMMTIgMjEuNCAzLjkgMTYuN1Y3LjN6Ii8%2BPHBhdGggZD0iTTEyIDcuNCAxNS45IDkuN3Y0LjZMMTIgMTYuNiA4LjEgMTQuM1Y5Ljd6Ii8%2BPC9nPjwvc3ZnPg%3D%3D" /></a>
  <a href="https://workspace.google.com/products/sheets/"><img alt="Google Sheets" height="25" src="https://img.shields.io/badge/Google%20Sheets-161826?style=flat&logo=googlesheets&logoColor=9184D9" /></a>
  <a href="https://slack.com"><img alt="Slack" height="25" src="https://img.shields.io/badge/Slack-161826?style=flat&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPGcgZmlsbD0ibm9uZSIgc3Ryb2tlPSIjOTE4NEQ5IiBzdHJva2Utd2lkdGg9IjEuOCIgc3Ryb2tlLWxpbmVjYXA9InJvdW5kIj48cGF0aCBkPSJNOS40IDMuMiA3LjYgMjAuOE0xNi40IDMuMmwtMS44IDE3LjYiLz48cGF0aCBkPSJNMy42IDguOWgxN00zIDE1LjFoMTciLz48L2c%2BPC9zdmc%2B" /></a>
  <a href="https://github.com/TuguiDragos/n8n-ai-call-agent/blob/main/LICENSE"><img alt="License MIT" height="25" src="https://img.shields.io/badge/License-MIT-161826?style=flat&labelColor=161826" /></a>
  <a href="https://youtu.be/xgDPP_hJ7ms"><img alt="Watch the demo" height="25" src="https://img.shields.io/badge/Watch%20the%20demo-161826?style=flat&logo=youtube&logoColor=9184D9" /></a>
</p>

<p align="center">
  <a href="https://tuguidragos.gumroad.com/l/n8n-ai-call-agent"><img alt="Get the workflow on Gumroad" height="48" src="./assets/cta-gumroad.svg" /></a>
</p>

---

A no-code AI voice agent that calls your leads, holds a real conversation, pulls their email straight out of what they said, and writes everything to a Google Sheet. Slack pings you on every call, answered or not.

Twenty five nodes, built entirely in n8n. Tested on 100+ real phone leads.

> Running GoHighLevel? There is a full CRM version of this agent that books appointments into your calendar and tags contacts automatically. [See the difference](#lite-or-full).

<br>

### What comes back from a call

<img src="./assets/04-results-sheet.png" alt="The Google Sheet the agent fills in, with status, recording, transcript, summary and interest" width="100%" />

One row per lead: status, recording URL, full transcript, an AI summary, whether they were interested, and a processed flag so nobody gets called twice. This is the actual output sheet from a live campaign.

<br>

<details>
<summary><strong>What changed in the May 2026 update, n8n v2 and Vapi stability release</strong></summary>

<br/>

Deep architectural fixes for full compliance with the n8n v2 engine, plus proper error handling on every Vapi connection.

**Added**
- **HTTP error handling and auto-retry** on all 4 Vapi nodes (`Create Customer`, `Initiate Call`, `Get Call Data`, `Get Call Status`): `retryOnFail: true`, `maxTries: 3`, `waitBetweenTries: 2000`, and `onError: continueRegularOutput` so a Vapi rate-limit or timeout cannot hard-crash the run.

**Changed**
- **n8n v2 syntax migration.** The `Filter Valid Leads` code node no longer uses the deprecated `items` array; it uses `$input.all().map(...)`.
- **14 nodes upgraded.** Google Sheets `4.5 → 4.7`, HTTP Request `4.2 → 4.4`, Slack `2.3 → 2.4`, If `2.2 → 2.3`.

**Fixed**
- **Code return format.** `Check Final Status`, `Set Attempt Count` and `Extract Email` returned plain `{}` objects, which n8n v2 rejects. All three now return `[{json: { ... }}]`.

**Compatibility**

| | |
| :-- | :-- |
| n8n | v2.0+, tested on v2.x, May 2026 |
| Vapi API | current stable, `api.vapi.ai` |
| Node.js | v24+, the n8n v2 default |

</details>

<br>

### What it does

- Calls leads with an AI voice that holds a natural conversation
- Extracts the email from speech, even said as *"tugui dragos at gmail dot com"*
- Writes transcript, summary, recording link and interest level to Google Sheets
- Slack alert on every call, successful or missed
- Retries and status polling, so a slow call never breaks the run
- Refreshes the sheet between leads so the data stays consistent
- Fully visual, no code to write

**You need:** n8n (cloud or self-hosted), a [Vapi](https://vapi.ai) account, a Twilio number, a Google service account, and a Slack bot.

<br>

### Where it earns its keep

| | scenario |
| :-- | :-- |
| **Agencies** | Call local businesses with no web presence. Salons, barbershops, dental clinics: they ignore cold email, they answer the phone. |
| **Freelancers** | Work a list from LinkedIn or Google Maps. The agent makes first contact, you get the email in Slack. |
| **E-commerce** | Follow up abandoned carts and ignored support emails with a real call. |
| **SaaS** | Call every new signup, confirm the email, score the interest, and pass only the warm ones to a human. |
| **Bookings** | Confirm appointments and collect missing details. No-shows drop. |
| **Inbound leads** | Someone fills in your ad form and gets a call in minutes instead of an email they will not open. |

<br>

---

## Inside the workflow

<img src="./assets/01-workflow.png" alt="The full n8n workflow" width="100%" />

**Part one, load and call.** Read the sheet, drop the leads already processed, clean the phone number, create the customer in Vapi and start the call.

<img src="./assets/02-workflow-part1.png" alt="Workflow part one, loading leads and initiating the call" width="100%" />

**Part two, after the call.** Pull the call data, parse the result, branch on whether anyone answered, extract the email, update the sheet and notify Slack.

<img src="./assets/03-workflow-part2.png" alt="Workflow part two, parsing the result and updating the sheet" width="100%" />

<br>

### The twenty five nodes

| step | nodes |
| :-- | :-- |
| **Start** | Manual Trigger, Load Lead Sheet, Filter Valid Leads, Has Leads to Process? |
| **Dial** | Clean Phone Number, Create Customer in Vapi, Initiate Call, Loop Setup Variables |
| **Watch** | Set Attempt Counter, Get Call Status, Check Final Status, Should Continue?, Wait 3s, Prepare Loop Payload |
| **Read** | Get Call Data, Parse AI Response, Was the Call Answered? |
| **No answer** | Update Lead (No Answer), Notify Slack (No Answer) |
| **Answered** | Extract Email, Update Lead (Completed), Notify Slack (Success) |
| **Next** | Wait Before Sheet Refresh, Sync Updated Sheet, Slack: all done |

Every branch is handled. Answered or not, the workflow knows what to do next and never leaves a lead in limbo.

<br>

---

## The output

### Every word, saved

<img src="./assets/05-transcript.png" alt="Full call transcripts logged in Google Sheets" width="100%" />

The whole conversation goes into the sheet. Nothing to listen back to unless you want to.

### Email pulled out of speech

<img src="./assets/06-email-extraction.png" alt="Regex and JavaScript extracting an email from the spoken transcript" width="100%" />

People say their address out loud, badly. The `Extract Email` node handles *"at"*, *"dot"*, spaces and hesitation, and returns a clean address.

### Slack, in detail

<img src="./assets/07-slack-message.png" alt="A Slack notification with name, email, summary, audio link and time" width="100%" />

Name, email, phone, a written summary of how the call actually went, a link to the recording, and the time. You read six lines instead of listening for four minutes.

<img src="./assets/08-slack-alerts.png" alt="Slack alerts for successful and missed calls" width="100%" />

Missed calls get their own alert, so a silent lead is still a lead you know about.

### Real calls on real numbers

<img src="./assets/09-phone-call.png" alt="An incoming call from the agent on a phone" width="100%" />

<br>

---

## The voice

<img src="./assets/10-vapi-prompt.png" alt="The Vapi system prompt behind the agent" width="100%" />

The prompt is tuned to understand slow or broken English, ask one question at a time, and confirm what it heard before moving on. Change the language, the persona or the script and the rest of the workflow does not care.

<img src="./assets/11-vapi-dashboard.png" alt="The Vapi dashboard with call volumes and end reasons" width="100%" />

<img src="./assets/12-twilio-logs.png" alt="Twilio call logs with durations and statuses" width="100%" />

Vapi shows you volume, duration and why each call ended. Twilio shows you the raw telephony side.

<br>

---

<h2 id="lite-or-full">Lite or full</h2>

This repo is the lite build. It runs on a Google Sheet, which is enough for most outreach. The full version is built around GoHighLevel and does the parts a spreadsheet cannot.

| | this one, lite | the GoHighLevel version |
| :-- | :-- | :-- |
| **Lead source** | Google Sheet | GoHighLevel contacts, with API pagination |
| **Calls** | Vapi and Twilio | Vapi and Twilio, rotating 6 caller IDs |
| **Email capture** | yes, from speech | yes |
| **Where results go** | Google Sheet and Slack | GHL contact record, tags, notes and Slack |
| **Books appointments** | no | yes, straight into the GHL calendar |
| **Auto-tagging** | no | yes, on every call outcome |
| **Lead top-up** | manual, you fill the sheet | nightly importer, 300 to 400 leads |
| **Scale tested** | 100+ leads | 9 hour runs, ~300 calls a day, 1,700+ calls placed |
| **Nodes** | 25 | 24, plus a suite of GHL workflows |
| **Price** | €58.99 | [on Gumroad](https://tuguidragos.gumroad.com/l/ghl-n8n-vapi-ai-calling-agent), and $230 [on the n8n template library](https://n8n.io/workflows/8339-replace-your-call-center-with-an-ai-agent-using-gohighlevel-ghl-vapi-and-twilio/) |

<p align="center">
  <a href="https://github.com/TuguiDragos/ghl-n8n-ai-calling-agent"><img alt="See the GoHighLevel version" height="48" src="./assets/cta-upgrade.svg" /></a>
</p>

<br>

---

## Questions

**Is it hard to set up?**

No. The workflow is pre-configured. Plug in Vapi, Twilio, Google Sheets and Slack, and you can place a test call in about ten minutes.

**Can I test it before going live?**

Yes. Trigger it manually and call your own number first. That is the right way to hear how it behaves.

**Does it work in other languages?**

Yes, as long as Vapi and your model support the language. Rewrite the prompt and it speaks it.

**What happens if nobody answers?**

Slack tells you, the sheet is marked "No Answer", and you can retry or follow up later.

**Can I change the messages and the logic?**

All of it. The Slack text, the voice prompt, the email regex, the branching. It is all visible in n8n.

**Do I need to self-host n8n?**

No. n8n cloud works. Self-host if you want the control.

**Does it require coding?**

Barely. It is visual. There is a little JavaScript in the email extraction, and it is already written.

**What does it cost to run?**

Vapi gives you free minutes each month. Twilio charges a few cents per call. Testing costs close to nothing.

<br>

---

## License

MIT. Use it, change it, build on it. Credit stays with the copyright notice. Full terms in [LICENSE](https://github.com/TuguiDragos/n8n-ai-call-agent/blob/main/LICENSE).

> **Before you dial.** You are responsible for how you use this. Disclose that the caller is AI where the law requires it, and comply with the rules on automated calling and data handling in your market, TCPA and GDPR included.

<br>

---

## About

Built by **Țugui Dragoș** `|QC⟩`. I build automation that runs without supervision: n8n workflows, AI agents, and the quiet machinery behind a business.

<p align="center">
  <a href="https://www.tuguidragos.com/"><img alt="Website" height="25" src="https://img.shields.io/badge/Website-161826?style=flat&logo=safari&logoColor=9184D9" /></a>
  <a href="https://n8n.io/creators/tuguidragos/"><img alt="n8n Creator" height="25" src="https://img.shields.io/badge/n8n%20Creator-161826?style=flat&logo=n8n&logoColor=9184D9" /></a>
  <a href="https://tuguidragos.gumroad.com"><img alt="Gumroad" height="25" src="https://img.shields.io/badge/Gumroad-161826?style=flat&logo=gumroad&logoColor=9184D9" /></a>
  <a href="https://www.linkedin.com/in/tuguidragos"><img alt="LinkedIn" height="25" src="https://img.shields.io/badge/LinkedIn-161826?style=flat&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPGcgZmlsbD0iIzkxODREOSI%2BPHJlY3QgeD0iMi42IiB5PSI4LjkiIHdpZHRoPSI0IiBoZWlnaHQ9IjEyLjUiIHJ4PSIwLjYiLz48Y2lyY2xlIGN4PSI0LjYiIGN5PSI0LjQiIHI9IjIuNCIvPjxwYXRoIGQ9Ik0xMCA4LjloMy44djEuOGE0LjIgNC4yIDAgMCAxIDMuNy0yYzMgMCA0LjkgMS45IDQuOSA1LjR2Ny4zaC00di02LjZjMC0xLjctLjctMi43LTIuMi0yLjdzLTIuMyAxLTIuMyAyLjd2Ni42SDEweiIvPjwvZz48L3N2Zz4%3D" /></a>
  <a href="https://github.com/TuguiDragos"><img alt="GitHub" height="25" src="https://img.shields.io/badge/GitHub-161826?style=flat&logo=github&logoColor=9184D9" /></a>
</p>

Write to **contact@tuguidragos.com** for questions, custom builds or automation work. If this helped, leave a star.

<br>

---

<p align="center">Built with 🖤 by <a href="https://tuguidragos.com">Țugui Dragoș</a></p>

<!-- n8n AI call workflow, AI phone agent automation, voice call automation with Vapi, Twilio voice workflow, Google Sheets n8n integration, OpenAI smart caller, cold outreach AI bot, no-code SDR system, lead qualification voice AI, call transcription automation, Slack notifications from calls, phone bot with email extraction, automated voice campaigns, conversational AI phone workflow, n8n v2 AI workflow -->
