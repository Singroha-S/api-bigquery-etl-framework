# API → BigQuery ETL Framework

A production-style ETL framework that extracts data from REST APIs, transforms it using Python, and loads it into Google BigQuery.

## Overview

This project demonstrates how modern data pipelines can be built using Python and BigQuery while following production engineering practices such as:

- Modular architecture
- Logging
- Error handling
- Retry mechanisms
- Config-driven execution
- Incremental data loading

## Architecture

```text
REST API
    ↓
Extract Layer
    ↓
Transform Layer
    ↓
Load Layer
    ↓
BigQuery
    ↓
Monitoring & Logging
```

## Tech Stack

- Python
- BigQuery
- Pandas
- REST APIs
- Logging
- GitHub

## Project Structure

```text
api-bigquery-etl-framework/

├── README.md
├── docs/
├── images/
├── src/
│   ├── extract/
│   ├── transform/
│   ├── load/
│   ├── utils/
│   └── config/
├── tests/
└── requirements.txt
```

## Planned Features

- API Data Extraction
- Incremental Loading
- Data Validation
- BigQuery Integration
- Logging & Monitoring
- Retry Logic
- Configuration Management

## Status

🚧 Under Development

Currently building the first version of the framework.
