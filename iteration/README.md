[⬅️ Back to Home](../README.md)
# Project Iteration Guide

This document provides a step-by-step guide for performing an iteration on your Odoo project, specifically when using Odoo.sh and Cluedoo modules.

## Prerequisites

Before starting the iteration process, ensure you have access to the following:
- Odoo.sh account
- Project repository on Odoo.sh
- Cluedoo modules (if applicable)
- Git access to your project repository

## Steps for Iteration

### 1. Backup and Database Setup
- **Go to Odoo.sh**: If there has been a previous iteration, begin by backing up the existing database.
- **Create a New Database**: After the backup, set up a new database on Odoo.sh for the iteration.

### 2. Cluedoo Module Integration
- **Check for Cluedoo Modules**: If your project utilizes Cluedoo, ensure that the Cluedoo module is added as a submodule in Odoo.sh.

### 3. Upgrade the Database
- **Upgrade Process**: Perform an upgrade on the database and allow sufficient time for the process to complete.

### 4. Branch Management
- **Clone the Upgrade Branch**: Clone the branch that you are planning to upgrade.
- **Remove Odoo v16 References**: Edit the configuration files and `.gitmodules` to remove any references to Odoo version 16.

### 5. Module Handling
- **Add an Empty Module**: Insert an empty module as part of your iteration process.

### 6. Push Changes
- **Push to the New Branch**: Finally, push your changes to the newly created branch for the upgrade.

## Notes

- Make sure to monitor the upgrade process to avoid any unexpected issues.
- Ensure that all references to previous Odoo versions are removed correctly.
- Confirm that the Cluedoo module is working properly after adding it to the submodules.

