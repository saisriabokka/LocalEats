
# LocalEats

![.NET CI](https://github.com/saisriabokka/LocalEats/actions/workflows/dotnet-ci.yml/badge.svg)

This project is structured for modular database change management using Liquibase and .NET. It includes:
- Modular changelogs for Users, Restaurants, Cuisines, Reviews, and Ratings
- Rollback logic and metadata in changelogs
- Automated CI/CD pipeline using GitHub Actions for build, test, and artifact upload

## CI/CD Pipeline
The pipeline runs on every push or pull request to the `dev` branch:
- Builds the .NET solution
- Runs unit tests
- Uploads build artifacts
- Shows logs on failure

## Getting Started
1. Clone the repo
2. Make changes and push to `dev` branch
3. Check Actions tab for build status

## Liquibase
Changelogs are in the `changelogs/` directory. See each XML file for details.
