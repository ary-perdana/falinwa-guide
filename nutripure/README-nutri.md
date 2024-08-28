# Nutripure Connector: Handling Validate Picking Errors

## Overview

This document provides guidance on resolving the "Validate Picking" error within the Nutripure connector. When processing orders, this error may occur and can be resolved by following specific steps to ensure the sales order is correctly managed within the system.

## Problem Description

The error appears during the Validate Picking process, specifically tied to sales orders, with a common example being an order such as `TNDCLTRGN`. This issue requires manual intervention to ensure that all items are correctly reserved or marked as unavailable.

## Steps to Resolve

To resolve the "Validate Picking" error, follow the steps below:

1. **Identify the Sales Order**:
    - Go to the **Job Queue** in the system.
    - Copy the sales order reference (e.g., `TNDCLTRGN`).

2. **Locate the Sales Order in External Order Data**:
    - Navigate to the **External Order Data** section.
    - Search for the sales order reference you copied earlier.

3. **Update the Sales Order**:
    - Open the identified sales order.
    - Go to the **Delivery** tab.
    - Open the **Operation** tab.
    - In the **Reserved** column, click on "Not Available" and ensure the quantity (`qty`) is set to `0`.

## Additional Notes

- Ensure that all changes are accurately made to avoid recurrence of the error.
- If issues persist, further investigation may be required, such as checking system logs or reaching out to technical support.

## Contact Information

For further assistance, please contact the Nutripure technical support team or refer to the internal documentation for more detailed troubleshooting.
