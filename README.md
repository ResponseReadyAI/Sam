# Sam: AI Virtual Assistant for HVAC Professionals

## 🚀 Project Overview
Sam is a specialized AI voice and web assistant designed to help HVAC business owners handle inbound calls, qualify leads, and manage bookings without leaving the job site.

## 🛠 Tech Stack
- **Hosting:** [Netlify](https://www.netlify.com)
- **Version Control:** [GitHub](https://github.com)
- **AI Brain:** [Synthflow AI](https://synthflow.ai)
- **Scheduling:** [Cal.com](https://cal.com) (Integrated with Outlook)
- **Phone Routing:** Google Voice

## 📞 Logic & Routing
1. **Inbound Call:** Customer dials the dedicated business number.
2. **Forwarding:** Google Voice forwards the call to the Synthflow Inbound Agent.
3. **The Agent (Sam):** Greets the customer, identifies the issue (Emergency vs. Routine), and offers a booking link.
4. **Action:** Sam sends a calendar invite via Cal.com that syncs to the master Outlook calendar.

## 📝 Configuration Notes
- **Styling:** Controlled via `style.css`. Uses a dark "Slate/Sky Blue" professional theme.
- **Demo Video:** Hosted on [YouTube/Vimeo] and embedded in `index.html`.
- **Environment Variables:** API keys for Synthflow are managed within the Synthflow dashboard, not the code.

## 📈 Future Scaling
To duplicate this for other industries (e.g., Salons):
1. Clone the Synthflow Agent.
2. Update the Knowledge Base (FAQ) for the specific niche.
3. Update the `index.html` text and `tel:` link for the new industry.
