Electricity Grid Data Repository

This repository contains datasets and preprocessing resources for the Australian electricity grid.

## Overview

The repository provides both raw and processed datasets used for analytics and machine learning models, including electricity pricing and grid performance metrics.

## Contents

- Raw electricity market data
- Cleaned and structured time-series datasets
- Feature-engineered datasets for prediction models

## Data Sources

- Open Electricity APIs
- Internal data pipelines
- AWS S3 storage (latest 120-day datasets)

## Usage

This data is used by:
- Electricity Grid API (data serving)
- Pricing Prediction Model (training & inference)

## Updating Data

Data is periodically updated and stored in AWS S3.  
Ensure the latest datasets are pulled before model training or analysis.

## Notes

- Data formats: CSV / time-series
- Ensure consistency in timestamps and schema before use
