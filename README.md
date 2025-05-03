## CI/CD Pipeline Rules

- **CI** (build, test, publish) runs on `main` only
- **CI/CD** (full pipeline including deploy) runs on `release` only
- **Code scanning** runs on both `main` and `release`
- **Other branches** (e.g., `feature/*`) do not trigger any pipeline
