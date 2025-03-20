
# FE Component Library Seed

A modern component library seed repo with **Storybook 7**, **Vite**, and **Chromatic** for blazing-fast development and deployment. Built with **TypeScript**, **SCSS**, and **PNPM**.

## 🚀 Tech Stack

- **Vite** (Builder)
- **Storybook 7** (`@storybook/html-vite`)
- **TypeScript**
- **SCSS/Sass**
- **ESLint** + **Prettier**
- **Chromatic** (CI/CD for Storybook)
- **PNPM**

## 📁 Folder Structure

```
root
├── .github/workflows/         # GitHub Actions for Chromatic CI
├── .storybook/                # Storybook configuration
├── src/components/            # Component source files
├── package.json               # Project metadata & scripts
├── tsconfig.json              # TypeScript config
└── README.md                  # You are here!
```

## ⚙️ Getting Started

### Install Dependencies

```
pnpm install
```

### Start Storybook

```
pnpm storybook
```

### Build Storybook Static Site

```
pnpm build-storybook
```

### Publish to Chromatic (CI runs this on PR/Push)

```
pnpm chromatic
```

## ✅ Features

- **Framework Agnostic** (HTML/JS base, extensible to React/Vue)
- **TypeScript** for type safety
- **SCSS** styling support
- **Chromatic Deployment** with GitHub Actions
- **Linting/Formatting** out-of-the-box
- **PNPM** for fast dependency management

## 🌱 Extending This Seed

- Add components to `src/components`
- Stories live alongside components or in their own files
- Easily swap in **React/Vue** versions later
- Add tests (Vitest/Jest/Playwright recommended)

## 📦 Future Improvements (Optional)

- Add unit/e2e testing
- Bundle publishing for NPM
- React/Vue starter components

---

### Apt & Nimble LLC

