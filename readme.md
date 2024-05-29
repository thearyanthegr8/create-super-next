# NextGen Templates with AI
>**CREATE-SUPER-NEXT**

## Overview

The NextGen Templates (NextJs Template Generator) is an npx package designed to create customized Next.js project templates based on user inputs as a freelancer or an indie developer. Leveraging an AI model, this tool scrapes documentation from specific sites, analyzes the content, and generates a tailored Next.js template with the desired configurations. This streamlines the setup process for Next.js projects by providing ready-to-use templates that meet specific requirements.

## Features

- **User Input Driven**: Generate templates based on user-specified configurations.
- **AI-Powered Scraping**: Automatically scrape and analyze documentation from various sources to understand how to integrate different tools and features.
- **Custom Configurations**: Create Next.js templates with specific setups, such as TypeScript support, CSS frameworks, authentication methods, and more.
- **Easy to Use**: Simple command to generate a project template without manual configuration.

## Installation

You can run the package directly using npx:

```bash
npx create-super-next <your-app-name>
```

## Usage
Upon running the package, you will be prompted to provide details about the desired configuration of your Next.js project. These details might include:
- TypeScript: Do you want to use TypeScript?
- CSS Framework: Which CSS framework do you prefer (e.g., Tailwind, Bootstrap, etc.)?
- Authentication: Do you need authentication setup (e.g., using NextAuth)?
- Database: Which database would you prefer (e.g., supabase, planetscale, etc.)?
- Payments: Payment portals you would want to use.
- Etc.

Based on your inputs, the AI model will scrape the relevant documentation, analyze the best practices, and generate a complete Next.js project template.
