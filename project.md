# Project Overview

This project is a React + TypeScript application with a modular component structure focused on layout, navigation, and routed page composition.

## Current Scope

- `src/pages/home.tsx` for the home page content
- `src/components/layout/` for application shell components such as the header, footer, navbar, and main layout
- `src/components/ui/` for reusable UI primitives including navigation menu and sidebar behavior
- `src/main.tsx` for app bootstrap
- `src/app/routes.tsx` for route definitions

## Goals

- Maintain deterministic, repeatable updates across the UI and routing layers
- Keep layout components consistent and reusable
- Ensure navigation and sidebar interactions remain cohesive across the app

## Constraints

- Preserve unrelated sections when making targeted updates
- Keep changes isolated to the intended files and responsibilities
- Avoid introducing behavioral regressions in layout or routing

## Success Criteria

- All listed components reflect the latest completed execution
- Navigation, header, footer, and layout components remain aligned
- Routing continues to work with the updated application shell
- The project description stays accurate to the current codebase state
