# Cypress Testing Project

## Installation

```bash
yarn install
```

## Running Tests

### Debug Mode (Open Cypress Test Runner)
```bash
yarn cypress open
```

### Headless Mode
```bash
yarn cypress run
```

## Additional Commands

- Run specific test file:
  ```bash
  yarn cypress run --spec "cypress/e2e/your-test.cy.js"
  ```

- Run tests in a specific browser:
  ```bash
  yarn cypress run --browser chrome
  ```

- Run tests with environment variables:
  ```bash
  yarn cypress run --env environment=staging
  ```

## Documentation

- [Git Branching Strategy](docs/git-strategy.md)
- [VSCode Hotkeys Reference](docs/hotkeys.md)
