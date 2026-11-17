# Foundations capstone

One small, reproducible data investigation that uses every Foundations skill: a script to rerun it, Python to pull and clean public data with tests, SQL to query it, and a short recommendation with its limits.

Built on the [Stacc Foundations roadmap](https://app.getstacc.org/learn/foundations). Stacc verifies this repository once, at the end of Foundations.

## Plan

1. Pick a question you can answer with public data.
2. Pull and clean the data in Python, with tests.
3. Query it with SQL.
4. Write a short recommendation and say what could make it wrong.
5. Make the whole thing rerun with one command.
6. Do the work on a branch and merge at least one pull request.

## What Stacc checks

- `README.md` with sections: Question, Data, Reproduce, Limitations, Live, Walkthrough
- `run.sh`
- `requirements.txt`
- `src/ingest.py`
- `src/clean.py`
- `tests/test_clean.py`
- `sql/analysis.sql`
- `analysis/findings.md` with sections: Recommendation, Evidence, Limitations
- `AI_USE.md` with sections: Prompts, Verification
- `tests/test_ingest.py`
- `analysis/reproduction_checks.md`
- `.github/workflows/publish.yml`
- GitHub Actions job `test` passes on the submitted commit
- at least one merged pull request
- README Walkthrough section links an HTTPS demonstration
- the link under the README Live section answers when checked

Your latest commit must pass the GitHub Actions assessment job named `test` in this repository, and the repository must show a merged pull request.
Replace this file with your own README. It needs sections named Question, Data, Reproduce, Limitations and Walkthrough.
Walkthrough must link your HTTPS demonstration. Include analysis/reproduction_checks.md with guided/independent case inputs, expected results, actual results and revisions.

## Sources

Pick any public indicator question you care about. The World Bank Indicators API needs no key and is free to reuse with attribution.

- [World Bank Indicators API](https://datahelpdesk.worldbank.org/knowledgebase/articles/889392-about-the-indicators-api-documentation)
