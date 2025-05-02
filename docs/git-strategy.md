# Git Branching Strategy

## Main Branches

- `main` - Production-ready code
- `develop` - Integration branch for features

## Branch Types

- `feature/*` - For new features
- `bugfix/*` - For bug fixes
- `hotfix/*` - For urgent production fixes

## Workflow

1. Create feature branch from `develop`:
   ```bash
   git checkout develop
   git checkout -b feature/my-feature
   ```

2. Work on your changes and commit regularly:
   ```bash
   git add .
   git commit -m "meaningful commit message"
   ```

3. Keep your branch up to date:
   ```bash
   git pull origin develop
   ```

4. Push your changes:
   ```bash
   git push origin feature/my-feature
   ```

5. Create Pull Request to `develop`

6. After review and approval, merge to `develop`

7. Periodically merge `develop` into `main` for releases

## Branch Naming

- Feature branches: `feature/description`
- Bug fixes: `bugfix/issue-description`
- Hotfixes: `hotfix/issue-description`

## Commit Messages

- Use clear, descriptive messages
- Start with a verb in present tense
- Keep first line under 50 characters
- Add detailed description if needed

Example:
```
Add user authentication feature

- Implement login form
- Add JWT token handling
- Create user session management
```
