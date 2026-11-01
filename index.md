# Assignment 8.4 - Dashboard with Grid and Flexbox

## Where Grid Is Used

- The outer .dashboard container uses display: grid with two columns (220px and 1fr) and two rows (80px and 1fr). The layout is set with grid-template-areas: the header spans the top, and the sidebar and main content sit below it.
- The .stats container uses a second grid with repeat(4, 1fr) to place the four statistic cards in four equal columns, with gap: 20px between them.

## Where Flexbox Is Used

- .stat-card uses display: flex with align-items: center, so the icon and the text sit side by side and are vertically centered.
- .stat-icon is a flex container with justify-content: center and align-items: center, which centers the emoji inside the round icon.
- .stat-info uses flex-direction: column to stack the title above the number.
- The header uses justify-content: space-between to put the title on the left and the welcome text on the right.
- The sidebar nav uses flex-direction: column to stack the links.

## Recent Activity

A small table below the cards shows the recent activity of students.

## Grid Inspector

I used the Grid inspector in Chrome DevTools. In the Elements tab, I clicked the grid badge next to the .dashboard element, which shows the grid lines, the named areas and the gaps on the page.

## Responsive Layout

Below 900px the cards change to 2 columns. Below 600px the layout becomes one column, with the sidebar above the main content.

