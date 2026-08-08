# phishing-awareness-quiz
🎣 Interactive phishing awareness quiz with real email simulations — DecodeLab Cybersecurity Internship Task 3
https://malikaira.github.io/phishing-awareness-quiz/
# DecodeLab_Phishing_Quiz

**Email Phishing Quiz — DecodeLab Cybersecurity Internship Task 4**

## 🎣 Phishing Awareness Quiz

**DecodeLab Cybersecurity Internship — Task 4**

An interactive, browser-based phishing awareness training tool. Users review realistic email simulations and answer knowledge questions to build the instincts needed to spot phishing attacks in real life.

## 🚀 Live Demo

🔗 https://malikaira.github.io/phishing-awareness-quiz/Phishing-Awareness.html

## 📸 Preview

| Intro Screen | Email Case | Quiz | Results |
|---|---|---|---|
| Tactics overview + Start | Judge: Legit or Phishing? | 13 MCQ knowledge questions | Score ring + full breakdown |

## ✨ Features

- **7 Realistic Email Simulations** — HBL bank alert, Netflix billing, GitHub notification, IT helpdesk, job scam, prize fraud, Google Drive share
- **13 Knowledge Questions** — covering lookalike domains, urgency tactics, spear phishing, BEC/CEO fraud, DMARC/DKIM/SPF, macro malware, and more
- **Shuffle on Every Run** — questions and answer options are reshuffled each time so the quiz stays fresh
- **Instant Flag Explanations** — every email case reveals exactly which red flags to look for
- **Score Breakdown** — circular score ring with per-question recap (correct/incorrect)
- **Mobile Responsive** — works on screens from 320px to 1920px
- **Zero Dependencies** — single HTML file, no frameworks, no backend, no install

## 🚀 Quick Start

```bash
# Clone the repo
git clone https://github.com/malikaira/phishing-awareness-quiz.git

# Open in browser — that's it
open Phishing-Awareness.html
```

Or just download the HTML file and open it directly in any modern browser. No server needed.

## 📂 File Structure

```
phishing-quiz/
│
├── phishing-quiz-enhanced.html   # Complete app — single self-contained file
└── README.md
```

## 🧠 What It Covers

### Email Simulation Cases

| # | Case | Type |
|---|---|---|
| 1 | HBL Bank Account Suspension | 🔴 Phishing |
| 2 | Job Opportunity / Registration Fee | 🔴 Phishing |
| 3 | GitHub Password Change Confirmation | 🟢 Legitimate |
| 4 | IT Department Password Reset | 🔴 Phishing |
| 5 | Netflix Billing Update | 🔴 Phishing |
| 6 | Google Drive Shared File | 🟢 Legitimate |
| 7 | Prize Winner Notification | 🔴 Phishing |

### Knowledge Topics

- Lookalike / homograph domains (micros0ft, dec0delab)
- Urgency and fear-based pressure tactics
- Mismatched display URLs vs actual destinations
- Sender address spoofing
- Spear phishing vs mass phishing
- Business Email Compromise (BEC) / CEO fraud
- Pretexting in social engineering
- Malicious Office macro delivery
- Email authentication: SPF, DKIM, DMARC
- Incident response after clicking a phishing link

## 🛡️ Security Notes

- No data is collected. Everything runs locally in the browser.
- No external requests except Google Fonts (for typography).
- All HTML rendering uses `textContent` and `escapeHtml()` — XSS-safe by design.
- This is an educational simulation only — no real phishing activity is involved.

## 🎨 Tech Stack

| Layer | Technology |
|---|---|
| Structure | HTML5 |
| Styling | CSS3 (CSS Variables, Flexbox, Grid) |
| Logic | Vanilla JavaScript (ES6+) |
| Fonts | Google Fonts — Roboto, Google Sans, Roboto Mono |
| Icons | Unicode emoji / symbols |

## 📱 Browser Support

| Browser | Supported |
|---|---|
| Chrome / Edge 90+ | ✅ |
| Firefox 88+ | ✅ |
| Safari 14+ | ✅ |
| Mobile Chrome / Safari | ✅ |

## 🤝 Acknowledgements

- Inspired by Google Jigsaw's Phishing Quiz
- Built as part of the DecodeLab Cybersecurity Internship program
- Email scenarios modeled after real-world phishing templates documented by SANS and CISA

## 📄 License

This project is built for educational purposes as part of an internship program.

© 2026 DecodeLab Cybersecurity Internship. All rights reserved.
