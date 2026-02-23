# CI Challenge

A Next.js + TypeScript project with automated CI via GitHub Actions.

## How to run locally

npm install
npm run dev

## Run tests

npm test

## Run linting

npm run lint

## What the CI pipeline does

On every push and pull request, GitHub Actions automatically:

1. Installs dependencies
2. Runs ESLint
3. Runs Vitest tests

![CI](https://github.com/megwilliams1/ci-challenge/actions/workflows/ci.yml/badge.svg)
