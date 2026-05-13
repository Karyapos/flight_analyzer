# Airport Taxi_Out Automation (InProgress)

## Project Summary

This repository documents an automated analytical workflow applied to any CSV file that meets a few basic structural requirements. The system processes 
the input and returns a full analysis report.Across four phases, it explains:

**which factors mostly influence taxi‑out performance and how**.

The [data](data) folder includes example datasets as well as a [sample‑data creator](data/samples_creator.py). All commands are executed in a **Python** environment.

## Phase 1

In this [phase](Phase1_pipeline), the CSV file is validated, checked for missing values and outliers. A rule-based filter determines which columns carry genuine outliers based on spread-adjusted fences. In addition, an agent validates the data produced and saves exploratory plots giving an immediate first view of the dataset. 

_Running [**agent.py**](Phase1_pipeline/agent.py) followed with the name of your csv file will trigger the whole pipeline._

## Closing Note

Handling every possible input variation is an ongoing challenge, the pipeline will keep evolving.
The pipeline logic is entirely my own work, built line by line while Agent scaffolding was AI-assisted.
