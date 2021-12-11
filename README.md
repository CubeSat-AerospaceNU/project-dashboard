# project-dashboard
The central project management dashboard for CubeSat@AerospaceNU

This dashboard serves the following purposes:
- Create project items for each team. Each project item contains:
	-- Title
	-- General description
	-- Point of contact
	-- Start date
	-- Estimated time of completion
	-- Net budget
	-- Overall progress
	-- Multiple work items
- Create work items for each project item. Each work item contains:
	-- Title
	-- General description
	-- Technical requirements
	-- Point of contact
	-- Team [it is associated with]
	-- Start date
	-- Estimated time of completion 
	-- Budget
	-- Progress (perhaps autocalculated)
- Filter work items based on:
	-- Budget
	-- If it's overdue
	-- Team
- See which work items are waiting on which other work items (dependency graph)
- Misc features to be implemented later:
	-- Budget and order management
	-- Active roster handling (taking attendance, etc.)
	-- Ability to create forms to handle interest/signups/lead transitions

The following features are in development (v0.0.1):
|    | Item | Description |
| -- | ---- | ----------- |
| [] | Install react, ejs, express | Basic server side stuff |
| [] | Build home page | Build the home page with ejs and bootstrap |