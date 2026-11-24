# Portfolio Presentation Script — 8 to 10 Minutes

Student: Somendra Mishra | Roll No: 2601060088 | Section C | BCA (AI & DS)
Specialisation interest: Data Science & AI/ML (Track B)

---

## [0:00 – 1:00] INTRODUCTION

"Good morning/afternoon. I am Somendra Mishra, Roll No 2601060088, BCA (AI & DS), Section C,
K.R. Mangalam University. I am particularly interested in Data Science and AI/ML, and today
I will walk you through the work I have done in the CSE103 lab course."

## [1:00 – 3:00] SKILLS & PROFILE OVERVIEW

- Open GitHub profile: https://github.com/Somendra-Mishra
- Walk through the Profile README: skills table, featured projects, LinkedIn and email links.
- If the HackerRank certificate was earned, open its public verification link; otherwise say "In Progress".
- Open LinkedIn briefly: https://www.linkedin.com/in/somendra-mishra-7b3799430 — point out the headline and skills.

## [3:00 – 6:00] LIVE PROJECT DEMO (most important)

**Demo 1 — GitHub repository (90 seconds).** Open https://github.com/Somendra-Mishra/cse103-lab-LAB3.
Point out the README badges and table, the `src/`, `tests/`, `docs/` structure, and the repository topics.
In the terminal run `git log --oneline` and explain that commit messages follow the Conventional
Commits format: `feat`, `fix`, `docs`, `chore`.

**Demo 2 — Shell script execution (90 seconds).** In the terminal run the LAB 2 system report script
(`./script6_sysreport.sh`). Explain each output section: CPU info, memory usage, disk usage,
top processes and uptime. "I wrote this script in Bash. It uses grep, awk, df, free and ps to
gather system information automatically."

**Demo 3 — API interaction (60 seconds).** Run:
`curl https://api.github.com/users/Somendra-Mishra | jq '.name, .public_repos'`
"curl sends an HTTP GET request to the GitHub REST API and jq extracts specific fields from the
JSON response. This is how modern apps communicate with backend services."

## [6:00 – 8:00] LEARNING ROADMAP & GOALS

- Open `LEARNING_ROADMAP.md` on GitHub and walk through each semester briefly.
- State the chosen Track B (Data Science & AI/ML) and why: the BCA (AI & DS) programme builds directly
  towards Python, statistics and ML frameworks, and the AI timetable/attendance advisor project is a
  natural first application.
- Open `PROGRESS.md` and show the coding platform tracker with honest current counts.
- Mention one concept that was difficult (for example, understanding `git diff --staged` or parsing
  nested JSON with jq) and how it was resolved by reading the documentation and practising in the terminal.

## [8:00 – 9:00] PORTFOLIO WEBSITE

Open https://Somendra-Mishra.github.io/developer-portfolio. Show the About section, project cards,
skills table and contact section. "I built this with plain HTML and CSS and deployed it for free
using GitHub Pages. No framework was needed."

## [9:00 – 10:00] CONCLUSION & QUESTIONS

"The most challenging part of this course was [X], because [Y]. I resolved it by [Z].
Thank you. I am happy to take any questions."

If asked something not yet covered: "I have not covered that yet, but it is on my Semester [N] roadmap."
Never guess or bluff.

---

## PREPARED TABS AND TERMINAL

- Browser tab 1: GitHub profile
- Browser tab 2: cse103-lab-LAB3 repository
- Browser tab 3: developer-portfolio repository with LEARNING_ROADMAP.md open
- Browser tab 4: live GitHub Pages website
- Browser tab 5: LinkedIn profile
- Terminal: in the LAB 2 scripts folder with `script6_sysreport.sh` ready to run
- Keep the HackerRank certificate tab open only if it was genuinely earned

**Practice requirement:** time the full talk at least twice alone, then once in front of a classmate.
