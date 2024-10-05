### Task Report: Task 3 - Nested Routing in React Router

# 1. Task Description
Set up nested routes using React Router for a multi-level menu. The project contains a homepage and a dashboard with sub-pages like Profile and Settings. The Settings page has further nested routes for General and Account settings. The navigation allows users to seamlessly move between different levels of the app and manage their profiles and settings in a structured manner.

# 2. Task Output Screenshot
<img width="524" alt="image" src="https://github.com/user-attachments/assets/e8acb62e-c498-40ea-90d8-7d92ad8d6691">
<img width="524" alt="image" src="https://github.com/user-attachments/assets/eded152a-4ad6-416e-b219-70fba29e8faf">
<img width="524" alt="image" src="https://github.com/user-attachments/assets/575bbb32-bbde-4e7d-a5e2-03a586c146f3">
<img width="524" alt="image" src="https://github.com/user-attachments/assets/db820775-d7ea-46d0-96b7-5ed261aaa359">
<img width="524" alt="image" src="https://github.com/user-attachments/assets/5acca16a-142e-4850-b226-ed03c07def43">
<img width="524" alt="image" src="https://github.com/user-attachments/assets/8c87227d-6603-428d-be53-451fde01236d">


# 3. Widgets/Algorithm Used in Task
React Router (BrowserRouter, Routes, Route, and Link):
oUsed to handle routing between different components in the app.

BrowserRouter: Wraps the entire app, enabling navigation between pages.
Routes and Route: Define the routing structure, with nested routes allowing for a hierarchical navigation flow.
Link: Provides the clickable links for navigation between routes without reloading the page.

Nested Routes:
Implemented to create multi-level routing.
The Dashboard component contains routes for Profile and Settings, while Settings itself has nested routes for General and Account.
Nested routes help structure the app in a way that simulates different sections, each with their own navigation and content.

Route Structure:
Home: Displays the welcome page with a basic description.
Dashboard: Provides links to sub-pages for managing user profile and settings.
Profile: A simple page showing the user’s profile information.
Settings: Contains further links to General settings (theme, notifications) and Account settings (password, email), creating a deep nesting of routes.

React Components:
App Component: Contains the main navigation and routing setup. The top-level routes include Home and Dashboard.
Dashboard Component: Serves as a nested route containing further links to Profile and Settings pages.
Settings Component: A nested route within Dashboard that contains sub-pages for General and Account settings.
Profile, General, and Account Components: Display simple static content for their respective pages.

CSS Styling:
App.css: Provides layout styles for the entire application, including the navbar and content areas.
Sub-navbar: A dedicated section for the dashboard and settings sub-navigation, making it easy to navigate between nested routes.
Content Area: Styling ensures that nested routes load content dynamically without page refreshes.

React State Management:
While no direct state is managed for routing, the hierarchical routing structure ensures each component manages its content individually based on the current route.
