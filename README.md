# IE-E-C-Task-1 — Employee Interests Survey Form

A single-page HTML survey form (Task 1). It asks an employee for:

- name and department
- a short free-text introduction
- whether they exercise at home (Yes / No)
- how they like to read about their favourite topics (Books, Online Resources, Phone Apps, Magazines)
- their favourite movie genre (Comedy, Suspense, Thrill, Horror)

There is no backend. Submitting the form shows a thank-you message on the page; nothing is sent
or stored anywhere. Name is the only required field.

**Live page:** https://samarthjaiswal.github.io/IE-E-C-Task-1/ (served by GitHub Pages from `main`)

## How to run locally

Open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8000
# open http://localhost:8000
```

## Project structure

```
IE-E-C-Task-1/
└── index.html   # the form, a small inline stylesheet, and the submit handler
```

## Tech stack

HTML5, CSS, a few lines of vanilla JavaScript.
