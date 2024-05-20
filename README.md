# Thesis-GitLab-API-PipelineMetrics

## Introduction

This project aims to gather and analyze pipeline metrics from GitLab using its API. It fetches data such as pipeline duration, status, and stage durations for specified projects and stores the information in an Excel workbook for further analysis.

## Usage

1. Clone this repository to your local machine.
2. Install the required Python libraries by running:
    ```
    pip install requests openpyxl
    ```
3. Open the `pipeline_metrics.py` file and update the `api_url` and `access_token` variables with your GitLab API URL and access token respectively.
4. Update the `project_stage_names` dictionary with the project IDs and their corresponding stage names.
5. Run the script using:
    ```
    python pipeline_metrics.py
    ```

## Dependencies

- Python 3.x
- requests
- openpyxl

## Sample Output

The script generates an Excel workbook (`pipeline_info.xlsx`) containing pipeline information such as pipeline ID, project ID, status, individual stage durations, and total duration for each pipeline. Each project has its own worksheet within the workbook.

## Disclaimer

This project is provided as-is, without any warranty. Use it at your own risk.

