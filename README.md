# Learningsuite Frontend Assignment

## Overview
Your task is to build a simple Kanban board (similar to Trello), where users can manage cards across multiple columns using drag & drop.

A good reference for the UI (React + Material UI):  
https://minimals.cc/dashboard/kanban

This example is only for orientation:
- You **do not** need to match the design
- Cards **do not** need to be clickable
- Focus on functionality and clean implementation

## Goal of this Assignment
We want to evaluate:
- How you approach a problem with unfamiliar libraries
- Your understanding of React & TypeScript fundamentals
- How you structure and write maintainable frontend code

**Important:**  
Code quality is more important than visual polish.

## Technical Requirement
Use `react-beautiful-dnd` for drag & drop:  
https://github.com/atlassian/react-beautiful-dnd  

(The package should be installed in this monorepo.)

## Key Requirements
Your implementation must support:

- Drag & Drop (DND) between columns
- Adding new cards to a column
- Moving cards between columns
- Reordering cards within a column via drag & drop
- A state structure that is serializable to JSON  
  (No need to implement persistence)

## Not Required
The following features are **not** required:

- Deleting cards
- Editing card or column titles
- Images inside cards (optional, nice-to-have)

## Getting Started
From the project root, run:

```bash
yarn
yarn start
