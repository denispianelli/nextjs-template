# Next.js Template

![Next.js Template](/src/app/opengraph-image.jpg)

[![Vercel Deployment](https://img.shields.io/static/v1?label=Deploy&message=Vercel&color=black)](https://vercel.com/)
[![Next.js](https://img.shields.io/badge/Next.js-v14-black)](https://nextjs.org/)

## Introduction

This template is an optimized Next.js project setup with modern tools for efficient development. It includes configurations for Prettier, ESLint, Husky, Jest, and GitHub Actions, allowing you to quickly start a new Next.js project with best practices in place.

## Tech Stack

- **Framework**: [Next.js 14](https://nextjs.org/)
- **Language**: [TypeScript](https://www.typescriptlang.org/)
- **Code Formatting**: [Prettier](https://prettier.io/)
- **Linting**: [ESLint](https://eslint.org/)
- **Git Hooks**: [Husky](https://typicode.github.io/husky/)
- **Pre-commit Code Checking**: [Lint-staged](https://github.com/lint-staged/lint-staged)
- **Testing Framework**: [Jest](https://jestjs.io/fr/)
- **CI/CD**: [GitHub Actions](https://github.com/features/actions)

## Prerequisites

- [Node.js](https://nodejs.org/) (Node.js 18.17.0 or later installed)
- [pnpm](https://pnpm.io/) (for dependency management)

## Installation

1. **Clone the repository**:

     ```bash
     git clone https://github.com/denispianelli/nextjs-template.git
     cd nextjs-template
     ```

2. **Install dependencies**

     ```bash
     pnpm install
     ```

## Usage

- Start the development server:  
  `pnpm dev`
- Run tests:  
  `pnpm test`
- Format with Prettier:  
  `pnpm format`
- Lint the code with ESLint:  
  `pnpm lint`

## GitHub Actions Configuration

This template includes a GitHub Actions configuration file for CI. Tets and
linting checks will automatically run on `main` and `dev` branches during pull
requests.

## Deploy

Follow the deployment guides for [Vercel](https://nextjs.org/learn-pages-router/basics/deploying-nextjs-app/deploy).
