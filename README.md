# ICLR 2024 Scores from OpenReview

A simple script to extract scores of publicly available ICLR submissions from OpenReview.

Prerequisite: Install the OpenReview Python client following Step 1 in https://docs.openreview.net/getting-started/using-the-api/installing-and-instantiating-the-python-client

Run `pip install -r requirements.txt` for insatlling basic requirements

Run `python3 main.py` to get a spreadsheet including paper titles and scores, in CSV format. The result is saved in `output.csv`.

Update: `output.csv` is sorted according to average score

Note: Withdrawn papers are excluded from the output.

**Recommendation:** Let's not overload the OpenReview server, so don't run this too often :)