<div align="center">

# Hi, I'm Abdulmalek 👋

Software engineer interested in backend systems, applied ML, and building things end-to-end
— from a data model up through a working UI.

[![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)](https://www.python.org/)
[![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)](https://fastapi.tiangolo.com/)
[![Flask](https://img.shields.io/badge/Flask-000000?style=flat&logo=flask&logoColor=white)](https://flask.palletsprojects.com/)
[![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=flat&logo=sqlalchemy&logoColor=white)](https://www.sqlalchemy.org/)
[![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikitlearn&logoColor=white)](https://scikit-learn.org/)
[![Qt](https://img.shields.io/badge/PySide6%20%2F%20Qt-41CD52?style=flat&logo=qt&logoColor=white)](https://doc.qt.io/qtforpython/)
[![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat&logo=pytest&logoColor=white)](https://docs.pytest.org/)

</div>

## What I work on

A mix of projects across a few different areas of software engineering — domain-modeling
and financial calculations, classic NLP/ML, async REST APIs with real auth, and desktop GUI
application design. Most of these are built the same way: a tested core library first, a
CLI or API on top of it, and a UI last — with CI, linting, and a documented set of
limitations for each one.

## Featured projects

| Project | What it is |
|---|---|
| [**taskflow-api**](https://github.com/abdulmalekazouz/taskflow-api) | An async project/task-management REST API — JWT auth, membership-based authorization, pagination/filtering, background notifications, and a per-IP rate limiter. FastAPI + SQLAlchemy 2.0 (async). |
| [**agent-desk**](https://github.com/abdulmalekazouz/agent-desk) | A desktop AI-agent assistant (PySide6): a chat interface backed by a transparent decide → check-permission → call-tool → reply loop, a revocable permission system, and multi-step workflows — with every step logged to an inspectable trace. |
| [**tax-estimator**](https://github.com/abdulmalekazouz/tax-estimator) | A U.S. federal income tax estimator — progressive bracket math, capital-gains "stacking," self-employment tax, and credit phase-outs — as a library, CLI, and Flask web UI, using `Decimal` throughout for exact currency arithmetic. |
| [**text-insight-toolkit**](https://github.com/abdulmalekazouz/text-insight-toolkit) | A text analysis toolkit — TF-IDF extractive summarization, keyword extraction, and lexicon-based sentiment analysis with negation handling — as a library, CLI, and Flask UI. |
| [**digit-recognizer**](https://github.com/abdulmalekazouz/digit-recognizer) | A handwritten-digit classifier (scikit-learn SVM) with model evaluation metrics and a canvas-based web UI for live predictions. |

Each one has its own README with setup instructions, a features list, and a "Limitations"
section spelling out what it deliberately does and doesn't do.

## How I build

- **Tests first-class, not an afterthought.** Every project above ships with a pytest suite
  and CI (GitHub Actions) that has to pass before anything merges.
- **Small, reviewable pull requests.** Features land one at a time, each with its own PR —
  check any repo's closed PRs to see the incremental build-out.
- **Honest scope.** If something is simplified or simulated (a mock dataset, an in-memory
  rate limiter, a rule-based stand-in for a real model), it's documented, not hidden.
