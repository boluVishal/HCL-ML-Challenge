# HCL ML Hiring Challenge

My solution for the HCL ML hiring challenge (Developer roles, Noida). The task involved extracting data from balance sheets.

## Approach

Skipped heavy ML entirely — the balance sheet data had consistent enough formatting that regex and basic string manipulation were sufficient to pull out the values. Spent time observing patterns in the documents and writing rules around them.

**Final score: 179 / 500** (highest in the challenge: 211)

## Files

| File | What it is |
|---|---|
| `Soln.ipynb` | Main solution notebook |
| `Problem Statement explanation.docx` | Challenge brief |
| `68702a3a-6-HCL_ML_Challenge1.zip` | Original dataset |

## Notes

The approach was deliberately simple — pattern matching on known balance sheet structures rather than training a model. Given the dataset size and the structured nature of financial documents, this turned out to be competitive.
