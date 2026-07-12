# CI/CD Pipeline with Automated Testing

## Objective

This project demonstrates how to integrate automated testing into a CI/CD pipeline using GitHub Actions.

## Project Files

- app.py
- test_app.py
- requirements.txt
- .github/workflows/ci.yml

## CI/CD Workflow

1. Developer pushes code to GitHub.
2. GitHub Actions starts automatically.
3. Python environment is created.
4. Dependencies are installed.
5. Unit tests are executed using Pytest.
6. Workflow completes successfully if all tests pass.

## Commands

Install dependencies

```bash
pip install -r requirements.txt
```

Run tests locally

```bash
pytest
```

## Test Cases

- Verify addition of positive numbers.
- Verify addition of negative and positive numbers.

## Expected Result

All tests should pass successfully.

## What I Learned

- CI/CD fundamentals
- GitHub Actions
- Automated testing with Pytest
- Continuous Integration best practices

## Challenges Faced

Understanding GitHub Actions workflows and integrating automated tests into a CI/CD pipeline was initially challenging. Learning how tests run automatically after each code change helped me understand continuous integration and code quality practices.
