# DataForge30 – Day 4: Error Log Alert Generator

## Project Overview
This is **Day 4** of the **DataForge30 challenge**, where I build **one real-world data project per day**.

In this project, I analyzed server access logs to detect **all error requests (HTTP 4xx and 5xx)**. This type of alert generation is essential for monitoring system health and identifying issues in real-time.

---

## Objective
- Read server access logs
- Identify all error requests (status code ≥ 400)
- List the endpoint and IP responsible for each error
- Generate a simple alert report

---

## Tech Stack
- Python
- Pandas
- Google Colab

---

## Input
- `access.log`  
  A simplified server log containing:
  - IP address
  - HTTP method
  - Endpoint
  - Status code

---

## Output
- `day4_error_alerts.txt`  
  A text report listing error requests with IP, endpoint, and status code.

Example:
