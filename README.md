# Maison Chef at Home — Chatbot Concierge

A multi-agent chatbot for the Maison Chef at Home private-chef service, built with the Gemini API and deployable to GitHub Pages.

## 5 Expert Agents

| Agent | Role | Handles |
|---|---|---|
| 🎩 Le Concierge | Front desk | General inquiries, triage |
| 📋 Le Chef de Service | Bookings | Guest changes, rescheduling, cancellations |
| 👨‍🍳 Le Chef de Cuisine | Dietary | Allergies, preferences, substitutions |
| 🍷 Le Maître d'Hôtel | Menu | Menu planning, wine pairing, occasions |
| ⏱️ Le Coordinateur | Logistics | Timing, setup, special requirements |

## How to Deploy to GitHub Pages

1. **Create a GitHub repository** at https://github.com/new

2. **Push these files** to the repository:
   ```powershell
   cd "C:\Users\laura\OneDrive\Documents\NCI Postgraduate AI for Business\Customer Engagement and Artificial Intelligence (PGDAIBUS_SEP)\ai-projects\maison-chef-chatbot"
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/maison-chef-chatbot.git
   git push -u origin main
   ```

3. **Enable GitHub Pages:**
   - Go to repo → Settings → Pages
   - Source: **Deploy from a branch**
   - Branch: `main`, folder: `/ (root)`
   - Click Save
   - Your site will be live at `https://YOUR_USERNAME.github.io/maison-chef-chatbot`

## How to Use

1. Open the deployed page (or open `index.html` locally)
2. Paste your Gemini API key into the bar at the top and click **Save**
3. The key is stored in your browser — only you can see it
4. Start chatting! Use the quick-action buttons or type freely
5. The bot automatically routes your request to the right expert agent

## Requirements

- A Gemini API key from https://aistudio.google.com (free tier works fine)
- A GitHub account (for deployment)

## Notes

- Your API key stays in your browser's localStorage — it never touches a server
- The free tier allows 15 requests per minute
- No backend needed — everything runs in the browser
