# references

Personal knowledge base hosted at [yevicki.github.io/references](https://yevicki.github.io/references)

A fast-access hub for reference guides, study curriculum, and AI prompt libraries — built for quick lookup on desktop, iPad, or phone.

---

## What's here

| File | Description |
|------|-------------|
| `index.html` | Hub homepage — card grid linking to all references |
| `curriculum/pace-circle-curriculum.html` | 16-week backend engineering curriculum built around the PaceCircle project (Java Spring Boot, React Native, PostgreSQL) |
| `prompts/pace-circle-prompts.html` | Claude prompt library for building PaceCircle — one complete-context prompt per week, plus utility prompts for debugging, code review, and interview prep |

---

## Structure

```
references/
├── index.html
├── curriculum/
│   └── pace-circle-curriculum.html
└── prompts/
    └── pace-circle-prompts.html
```

---

## About PaceCircle

The curriculum and prompt guides are built around **PaceCircle** — a web-based fitness calendar app with a low-pressure social accountability layer. Users plan workouts, join invite-only circles, share events with those circles, and RSVP with "Count me in."

**Tech stack:**
- Backend: Java 21, Spring Boot 3.x, PostgreSQL, Spring Security + JWT, Redis
- Frontend: React + TypeScript (Vercel), React Native + Expo (App Store)
- Deployment: Railway (backend), Vercel (frontend)

---

## Adding new references

1. Add your HTML file to the appropriate folder (`/curriculum`, `/prompts`, or a new category folder)
2. Open `index.html` and copy an existing card block
3. Update the `href`, title, description, and `data-tags` to match your new file
4. Commit and push — GitHub Pages deploys automatically

---

## Local preview

Open any file directly in your browser — no build step needed. All files are plain HTML with no dependencies beyond Google Fonts.

```bash
open index.html
```

---

*Built and hosted on GitHub Pages · [yevicki.github.io](https://yevicki.github.io)*
