# CommBank Web – Goal Icon Enhancement

## Overview

This project is a React and TypeScript frontend application developed as part of the CommBank virtual experience program.

The objective of this task was to enhance the existing Goal Management feature by introducing customizable goal icons and emoji selection functionality.

## Features Implemented

### Goal Model Enhancement

* Extended the Goal data model to support an icon property.
* Updated TypeScript interfaces and related components to handle goal icons.

### Goal Card Updates

* Modified the Goal Card component to display the selected icon alongside goal information.
* Improved visual representation of user goals.

### Emoji Picker Integration

* Integrated Emoji Mart to allow users to select emojis as goal icons.
* Added an intuitive icon selection experience within the application.

### Goal Manager Enhancements

* Enabled users to add an icon when creating a new goal.
* Enabled users to update an existing goal's icon.
* Ensured icon data is maintained across goal management workflows.

## Technologies Used

* React
* TypeScript
* Redux
* Material UI
* Emoji Mart
* Git
* GitHub

## Project Structure

Key files modified during implementation:

```text
src/
├── api/
│   └── types.ts
├── ui/
│   ├── features/
│   │   └── goalmanager/
│   │       └── GoalManager.tsx
│   └── pages/
│       └── Main/
│           └── goals/
│               ├── GoalCard.tsx
│               ├── GoalIcon.tsx
│               └── AddIconButton.tsx
```

## Learning Outcomes

Through this project, I gained practical experience in:

* Modifying existing React applications
* Working with TypeScript interfaces and models
* Managing component state and props
* Integrating third-party libraries
* Enhancing user interface functionality
* Using Git and GitHub for version control

## Repository

This repository contains my completed solution for the CommBank Frontend Enhancement Task.
