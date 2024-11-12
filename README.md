# Kanban Board
## Description
A Kanban Board built using React.js. It has the following features:
- Fetches data from [API](https://api.quicksell.co/v1/internal/frontend-assignment )
- Dynamic grouping of data based on the following parameters
  1. **By Status**: Group tickets based on their current status.
  2. **By User**: Arrange tickets according to the assigned user.
  3. **By Priority**: Group tickets based on their priority level.
- Dynamic ordering of tickets based on the following parameters
  1. **Priority**: Arrange tickets in descending order of priority.
  2. **Title**: Sort tickets in ascending order based on their title.
- Responsive design for smaller screen sizes
- Vanilla CSS styling
- Components structured in a reusable and maintainable manner
- Persistance of State

## Technology used
- React.js - Frontend
- Postman - testing API
- Vercel - Hosting Service

## Setup Instructions
### Frontend
- Step 1: Clone repo using `https://github.com/Aishwarya8s/Quicksell-Kanban-Board.git`
- Step 2: Navigate to the folder and run `npm i` to install all required dependencies
- Step 3: Run the frontend using `npm run start`

## Demo
The platform has been hosted for demo purposes - https://quicksell-kanban-board-aish.vercel.app/
The app can be grouped based on status, ordered by Tile; grouped based on user ordered on Priority; and Grouped based on Priority, ordered based on Priority. The created app is hosted on vercel and has a responsive design can be used easily on Mobile screens as well.

