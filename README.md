# Individual Development Plan (IDP) template

The purpose for this repository is to provide a template Individual Development Plan (IDP) using a GitHub repository and project. 
This should allow individuals to create and manage their personal and/or professional development plan using all of the tools and benefits availailable within GitHub, such as:

* Issues and issue templates to support goals, actions to achieve them, regular reflections on your progress, etc.
* Labels for organizing your development plan
* Pull requests, if sharing with a coach, support partner, manager
* Projects for visualizing and managing your progress towards your development goals
* Reflection issue and reminder action for weekly, personal reflections on progress towards your IDP

## Templates

The [templates folder](./templates) contains development plan templates. The templates can be used alone, or in combination with issues and the "My IDP Project".

## Reflection

A reflection is intended to review progress towards goals in an IDP. It is an opportunity to learn and adapt, as well as look back at the changes one has made over time.

### Reflection reminder

When enabled and configured, [this action](./.github/workflows/reflection_reminder.yml) will run on a weekly (Monday) schedule to automatically create a "reflection" issue that can be updated throughout the week.

To use this action:
- Create a personal access token (`ACTIONS_REFLECTION_PAT`) with the ability to write issues.
- Enable the workflow

This will run on a schedule or can be run manually. The title will default to the current work week's date range and populate the issue body based on [this template](./.github/content-templates/reflection.md).

🚧 More to come soon!
