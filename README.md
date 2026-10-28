# NM1130 · AI & Digital Skills Lab

A compact portfolio of eight Python experiments for the **Naan Mudhalvan NM1130 AI and Digital Skills** course. The examples cover introductory machine learning, productivity automation, practical AI applications, professional branding, cybersecurity, version-control concepts, sales analytics, and career planning.

> These are educational demonstrations. Model predictions and security checks are simplified examples, not production or professional advice.

## Experiments

| No. | Topic | Program | What it demonstrates |
|---:|---|---|---|
| 01 | AI Fluency | [`01.ai_fluency.py`](01.ai_fluency.py) | Classification, regression, clustering, gradient descent, a neural network, and basic sentiment analysis |
| 02 | AI Productivity | [`02.ai_productivity.py`](02.ai_productivity.py) | Email drafts, extractive summaries, action-item detection, proposals, and sales insights |
| 03 | AI Applications | [`03.ai_applications.py`](03.ai_applications.py) | Educational examples for healthcare classification, fraud detection, recommendations, and crop-yield prediction |
| 04 | LinkedIn Profile Analyzer | [`04.linkedin_profile_analyzer.py`](04.linkedin_profile_analyzer.py) | Profile checklist scoring, improvement suggestions, and a before/after chart |
| 05 | Cybersecurity Toolkit | [`05.cybersecurity_toolkit.py`](05.cybersecurity_toolkit.py) | Password strength and generation, password hashing, URL risk checks, TOTP, and SHA-256 integrity |
| 06 | Mini Git | [`06.mini_git.py`](06.mini_git.py) | A small in-memory version-control simulator covering commits, branches, merges, and pull requests |
| 07 | Power BI-style Sales Dashboard | [`07.power_bi_dashboard.py`](07.power_bi_dashboard.py) | Data cleaning, KPIs, visualisation, and CSV export |
| 08 | Career Essentials | [`08.career_essentials.py`](08.career_essentials.py) | Skills self-assessment, gap analysis, SMART goals, and the Eisenhower matrix |

## Repository files

All eight Python programs are in the repository root. The accompanying sample data and generated examples are also stored in the root:

- Sales data: [`07.sales_raw.csv`](07.sales_raw.csv) and [`07.sales_clean.csv`](07.sales_clean.csv)
- Sales dashboard preview: [`07.sales_dashboard.png`](07.sales_dashboard.png)
- LinkedIn profile chart preview: [`04.profile_improvement.png`](04.profile_improvement.png)
- Career skills radar preview: [`08.career_skills_radar.png`](08.career_skills_radar.png)
- Dependencies: [`requirements.txt`](requirements.txt)

The links above point to the actual filenames in this repository, rather than to folders that are not present.

## Run locally

Python 3.10 or newer is recommended.

1. Download or clone this repository.
2. (Optional) Create and activate a virtual environment:

   ```bash
   python -m venv .venv
   # Windows
   .venv\Scripts\activate
   # macOS/Linux
   source .venv/bin/activate
   ```

3. Install the listed libraries:

   ```bash
   python -m pip install -r requirements.txt
   ```

4. Run an experiment from the repository root, for example:

   ```bash
   python 01.ai_fluency.py
   python 04.linkedin_profile_analyzer.py
   python 07.power_bi_dashboard.py
   python 08.career_essentials.py --interactive
   ```

Experiments 2, 5, and 6 use only the Python standard library for their core demonstrations. Experiment 2's optional live model call requires the optional `anthropic` package and an `ANTHROPIC_API_KEY` environment variable.

## Output notes

The chart-producing programs save their charts beside the script when run. The sales dashboard program also creates cleaned data files. Existing preview images and CSV files are included so the repository can be inspected without running the programs first.

## Learning notes

- Start with Experiments 1–3 to see different ways AI models are trained or applied.
- Experiment 5 is a useful place to compare hashing, randomness, and URL heuristics.
- Experiment 6 illustrates version-control ideas in a simplified in-memory model; it is not a replacement for Git.
- Experiment 7 follows a data workflow: collect → clean → calculate → visualise.
- Experiment 8 turns a self-assessment into a short action plan.

## Possible next improvements

- Add automated tests for input validation and edge cases.
- Move each experiment and its generated files into its own folder once the root-level version is understood.
- Add screenshots of sample terminal output and document the Python version used.
