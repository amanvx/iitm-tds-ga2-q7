# IITM TDS - Graded Assignment 2, Question 7

This repository contains the solution for Graded Assignment 2 (GA2), Question 7 for the **IIT Madras BS Degree - Tools in Data Science (TDS)** course.

## Objective

The goal of this assignment is to optimize Continuous Integration (CI) pipelines by implementing dependency caching using GitHub Actions.

## Implementation Details

A GitHub Actions workflow has been created in the `.github/workflows` directory to satisfy the specific assignment requirements:

* **Caching Action:** Utilizes `actions/cache@v4` to cache dependencies and speed up workflow execution.
* **Target Cache Key:** Uses the specified key `cache-c286803` to prime the cache.
* **Verification Step:** Includes a dedicated step named `prime-cache-c286803` that explicitly echoes the cache hit/miss result to the workflow logs for grading inspection.

## Repository Structure

* `.github/workflows/` - Contains the YAML workflow file demonstrating the caching mechanism.
* `README.md` - Assignment documentation.

---
*Note: This repository is submitted for grading purposes. Reviewers can inspect the most recent GitHub Actions run to verify the successful execution of the cache step.*
