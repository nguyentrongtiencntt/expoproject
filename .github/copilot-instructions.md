# Copilot Instructions for AI Coding Agents

## Project Overview
This is an Expo React Native app using TypeScript, created with `create-expo-app`. The main source code is in the `app/` directory, which uses file-based routing. Components are organized in `components/`, with UI subcomponents in `components/ui/`. Assets are stored in `assets/images/`.

## Key Workflows
- **Install dependencies:**
  ```bash
  npm install
  ```
- **Start development server:**
  ```bash
  npx expo start
  ```
- **Reset to blank project:**
  ```bash
  npm run reset-project
  ```
  This moves starter code to `app-example/` and creates a blank `app/`.

## Architectural Patterns
- **File-based routing:** Pages and modals are defined in `app/` and `app/(tabs)/` using Expo Router conventions. Example: `app/(tabs)/explore.tsx` is a tab page.
- **Component organization:** Shared components are in `components/`, with reusable UI elements in `components/ui/`.
- **Theming:** Theme logic is in `constants/theme.ts` and hooks like `hooks/use-theme-color.ts`.
- **TypeScript:** All source files use TypeScript for type safety.

## Project Conventions
- **Use Expo Router for navigation.**
- **Assets:** Place images in `assets/images/` and reference them with relative paths.
- **Hooks:** Custom hooks are in `hooks/` and follow the `use-` naming convention.
- **No backend integration is present by default.**

## External Dependencies
- **Expo**: Core framework for app development and build.
- **React Native**: UI and platform APIs.
- **EAS (Expo Application Services):** Configuration in `eas.json` for builds/deployment.

## Example Patterns
- To add a new tab, create a file in `app/(tabs)/` and update `_layout.tsx` as needed.
- To add a new component, place it in `components/` and import where needed.
- For theming, use the hooks in `hooks/` and theme definitions in `constants/theme.ts`.

## References
- See `README.md` for setup and workflow details.
- See `app/` for routing and page structure.
- See `components/` for reusable UI logic.

---
**Feedback:** If any section is unclear or missing important project-specific knowledge, please specify so it can be improved.