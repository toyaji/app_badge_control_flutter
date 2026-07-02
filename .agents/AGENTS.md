# AI Agent Guidelines for app_badge_control_flutter

This document defines specific rules and constraints that all AI coding assistants must strictly adhere to when interacting with this repository.

## Git & Commit Guidelines

1. **Do Not Commit per Minor Fix**:
   - In order to prevent expensive CI environment runs and save billing costs, **do NOT create git commits incrementally** for every small bug fix, lint correction, or minor refactoring.
   - Consolidate all related changes and modifications. Perform git commits **only** when a feature, bug fix, or validation phase is fully completed, stable, and locally verified.
2. **Follow Staging Rules**:
   - Only stage files explicitly using `git add <file_path>`. Never use wildcards or `git add .` to avoid committing unstaged local changes made by the user.
