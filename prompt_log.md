# Prompt Log

## AI model/tool(s) used

Claude (Anthropic) — used for designing the app specification and generating the implementation code.

## Key prompts that shaped the implementation

### Prompt 1 (initial build spec)

> Build a real-time currency exchange rate website using the Frankfurter API ([https://frankfurter.dev/](https://frankfurter.dev/)). The UI should be themed primarily in red and black, with a "fancy" and "cool" aesthetic. It must feature a central wallet visual: when the user inputs an amount in one currency (e.g., 100 CNY) and selects a target currency (e.g., JPY), the input amount visually deposits into the wallet, transforms, and the converted amount emerges from the wallet with a visual effect emphasizing the increased quantity. This should work generically for any currency pair supported by the API. The site should be responsive, handle API errors and loading states gracefully, and be production-ready.

### Prompt 2 (GitHub publishing)

> Publish the completed currency converter project to the existing GitHub repository at [https://github.com/david555787/currency_converter](https://github.com/david555787/currency_converter), including initializing git, adding a .gitignore, writing a README.md with setup instructions and tech stack, committing, and pushing to the main branch — while checking for and excluding any secrets or API keys before pushing.
