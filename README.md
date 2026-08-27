# Gen AI for Data Analytics — Learning Roadmap

An interactive, single-file HTML roadmap for data analysts learning to apply generative AI to their existing SQL and Python workflow. Framed as a SQL query pipeline — six stages, each named after a clause (`SELECT`, `FROM`, `JOIN`, `WHERE`, `GROUP BY`, `ORDER BY`) — with checkable tasks, a progress tracker, and a hands-on project per stage. 

Link: https://dheerajsk26.github.io/Gen-AI-Roadmap-For-Data-Analysts/

![progress](https://img.shields.io/badge/stages-6-E8A33D) ![type](https://img.shields.io/badge/format-single--file%20HTML-4FBBA6)

## Why this exists

Most "AI for data analysts" content is either a course sales page or a generic list of buzzwords. This roadmap is scoped narrowly on purpose: it assumes you already know SQL and Python, and already have some exposure to prompting and calling an LLM API. It skips the "what is ChatGPT" material and goes straight into the sequence that actually matters for turning that exposure into a job-ready, demonstrable skill — culminating in packaging it for interviews.

## The six stages

| Clause | Focus | Roughly |
|---|---|---|
| `SELECT` | Sharpen prompting and API fundamentals you already have | 1 week |
| `FROM` | Wire an LLM into your existing SQL/Python stack | 1.5 weeks |
| `JOIN` | Retrieval-augmented generation (RAG) basics | 2 weeks |
| `WHERE` | Validating and catching AI-generated errors — the real analyst edge | 1 week |
| `GROUP BY` | Light agentic automation of a real workflow | 2 weeks |
| `ORDER BY` | Packaging projects and stories for the job market | 1–1.5 weeks |

Each stage includes 4 concrete tasks and one practice project designed to leave you with a portfolio artifact, not just notes.

## Features

- Six collapsible stages with a task checklist and a suggested project each
- Live progress bar and a query-pipeline strip at the top that fills in as clauses are completed
- Zero dependencies — a single HTML file with inline CSS and vanilla JavaScript
- No build step, no backend, no tracking


## Who this is for

Data analysts or data engineers who:
- Are comfortable with SQL and Python
- Have used an LLM chat interface and made at least one API call
- Want a structured path toward using generative AI credibly in analytics work, not just as a novelty


## License

MIT — feel free to fork, adapt, and reuse.
