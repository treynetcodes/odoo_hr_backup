# Odoo HR Backup
**Odoo HR Backup** is a Python-based utility developed to extract and back up employee-related data from an Odoo ERP system. The tool focuses on exporting structured HR information into a JSON format, making it easier to archive, transfer, or process externally.

## Purpose

This script is intended to support HR data management by generating a snapshot of employee records from Odoo. It can be used for:

- Creating offline backups of HR data
- Migrating employee data between Odoo instances
- Integrating HR data with external systems or reporting tools

## Features

- Extracts employee data from Odoo
- Outputs structured JSON files
- Includes support for employee images (optional)
- Simple and customizable Python scripts

## Repository Structure
- `scripts/`: Contains the main Python scripts for data extraction
- `emp_img/`: Optional folder for storing employee images
- `hr_backup.json`: Example output file with backed-up HR data
- `README_HR_BACKUP.md`: Additional documentation 

## Requirements

- Python 3
- Access to an Odoo instance with HR modules installed

## Usage
1. Configure access to your Odoo instance.
2. Run the script located in the `scripts/` folder.
3. The output will be saved as a JSON file (`hr_backup.json`) containing employee records.
