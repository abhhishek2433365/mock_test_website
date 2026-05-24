# 📚 ExamPro India – Free Mock Tests

> A completely free, offline-capable mock test platform for India's major competitive exams. No sign-up, no API key, no internet required — just open and start practicing.

---

## 🌟 Features

- **100 randomised MCQs** per test session — drawn from a large question bank so every attempt feels fresh
- **90-minute countdown timer** with visual warnings (yellow at 10 min, red + blinking at 5 min) and auto-submit on timeout
- **+4 / −1 marking scheme** — mirrors the actual exam pattern
- **Live question map** — colour-coded grid showing answered, unanswered, and current questions
- **Instant result screen** — score, percentile, accuracy %, time taken
- **Detailed answer key** — full table comparing your answers vs correct answers for every question
- **Works 100% offline** — no backend, no database, no server needed
- **Fully responsive** — works on desktop, tablet, and mobile

---

## 📋 Supported Exams & Subjects

| Exam | Subjects Available |
|---|---|
| UPSC CSE | General Knowledge & Current Affairs, General Hindi, Mathematics |
| SSC CGL / CHSL | General Knowledge, Reasoning, Mathematics, English |
| RRB NTPC / Group D | General Knowledge, Mathematics, Reasoning |
| IBPS PO / Clerk | Reasoning, Quantitative Aptitude, English |
| SBI PO / Clerk | Reasoning, Quantitative Aptitude, English |
| NDA / CDS | General Knowledge, Mathematics |
| CRPF / CISF / BSF | General Knowledge, Reasoning |
| UP Police | General Knowledge, General Hindi, Mathematics |
| UPTET / CTET | General Knowledge, Mathematics, Pedagogy |
| JEE Main | Physics, Chemistry, Mathematics |
| NEET UG | Physics, Chemistry, Biology |
| GATE | Computer Science, Electronics |
| CAT | Quantitative Aptitude, Verbal Ability, DILR |
| CUET | General Knowledge, Mathematics |

---

## 🚀 Getting Started

### Prerequisites

None. This is a single HTML file with zero external dependencies at runtime.

### Running locally

```bash
# Clone the repository
git clone https://github.com/your-username/exampro-india.git

# Navigate into the folder
cd exampro-india

# Open in your browser — no server needed
open index.html        # macOS
start index.html       # Windows
xdg-open index.html    # Linux
```

Or simply double-click `index.html` in your file manager.

---

## 🗂️ Project Structure

```
exampro-india/
├── index.html      # Entire application — HTML, CSS, JS, and question bank in one file
└── README.md
```

---

## 🧩 How It Works

1. **Select Exam** → choose from 14+ competitive exams via dropdown
2. **Select Subject** → pick a subject/paper for that exam
3. **Start Test** → 100 random questions are drawn from the question bank; the 90-minute timer begins
4. **Answer & Navigate** → click options, jump between questions using the map panel
5. **Submit** → manually or automatically when time runs out
6. **Results** → instant scorecard with correct / wrong / skipped counts, marks, accuracy, and the full answer key

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Markup | HTML5 |
| Styling | CSS3 (custom properties, CSS Grid, Flexbox) |
| Logic | Vanilla JavaScript (ES6+) |
| Fonts | Google Fonts — Baloo 2 + Noto Sans |
| Dependencies | None (fully self-contained) |

---

## 📊 Scoring System

| Result | Marks |
|---|---|
| Correct answer | +4 |
| Wrong answer | −1 |
| Skipped | 0 |
| Maximum score (100 Qs) | 400 |

---

## 🎨 Design Highlights

- Tri-colour header border inspired by the Indian flag (saffron / white / green)
- Warm parchment background palette (`#f5f0e8`) for eye comfort during long sessions
- Ashoka Chakra (☸) used as a subtle decorative watermark
- Baloo 2 — a rounded display typeface suited for Indian-language rendering
- Responsive grid layout — collapses gracefully on smaller screens

---

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. **Add questions** — expand the question bank for any subject inside the `QB` object in `index.html`
2. **Add a new exam** — add an entry to the `EXAMS` array with subjects and their question sets
3. **Bug fixes** — open an issue or submit a pull request

### Adding questions

Each question follows this format inside the relevant subject array:

```javascript
{
  q: "Question text here?",
  opts: ["Option A", "Option B", "Option C", "Option D"],
  ans: 0  // zero-based index of the correct answer
}
```

---

## 📄 License

This project is open-source and free to use under the [MIT License](LICENSE).

---

## 🙏 Acknowledgements

- Question content sourced and curated from standard competitive exam preparation material
- Fonts by [Google Fonts](https://fonts.google.com)
- Built with love for students preparing across India 🇮🇳

---

<p align="center">Made for India's competitive exam aspirants · 100% Free · No sign-up required</p>
