# Data
-   **[Dataset]**: Description of the dataset 

# Codebook for [chosen] Dataset

## Variable Names and Descriptions:

Based on the provided column descriptions, here's a template for a README.md file explaining the dataset:

Data README
Overview
Welcome to the data folder of [Your Dataset Name]! This folder contains a dataset detailing data breaches, including information about the organizations affected, the number of records lost, the date of the breach, the sector affected, and more.

Dataset Details
- organisation: Name of the organization that lost data.
- alternative name: Alternative name for the organization.
- records lost: Number of records lost in the data breach (int64).
- year: Year in which the data breach occurred (int64).
- date: Date of the data breach.
- story: Description of the data breach incident.
- sector: Sector affected by the data breach.
- method: Method through which the data breach occurred.
- interesting story: Interesting story related to the data breach.
- data sensitivity: Level of data sensitivity (1, 2, 3, 4, 5) (float64).
- displayed records: Displayed records in the data breach.


## Data Types:
Data Types:
- organization: object
- alternative name: object
- records lost: int64
- year: int64
- date: object
- story: object
- sector: object
- method: object
- interesting story: object
- data sensitivity: float64




