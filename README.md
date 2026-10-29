# Experiment 06 — Continuous integration with GitHub Actions

**Student:** [Your name]  
**Register number:** [Your register number]  
**Course:** Collaborative Development and DevOps

## Aim

Run a Python smoke check automatically when changes are pushed or a pull request targets `main`.

## Files

- `app.py` — a small program the workflow will execute.
- `.github/workflows/ci.yml` — the CI definition.

## Run locally

```sh
python --version
python app.py
```

## GitHub Actions workflow

The workflow installs Python 3.12, checks syntax, and executes the program. Push both files to the `main` branch, then open the **Actions** tab and inspect the run.

## What to record

Include the workflow run link and its status, plus any failure and the correction you made. A green badge or a local run alone is not proof that GitHub Actions ran.

## Result

Complete this section after the workflow has run in GitHub Actions. Do not report a successful run until you have verified it in the Actions tab.

## Reference and attribution

The topic follows the GitHub Actions CI theme in [Smirk1308/DevOps_LAB_06](https://github.com/Smirk1308/DevOps_LAB_06). This repository contains a separately written workflow and example.