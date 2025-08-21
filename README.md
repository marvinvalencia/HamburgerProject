# HamburgerProject

Collapsible Nav Menu Bar in Blazor

Steps:
1. <Routes @rendermode="InteractiveServer" /> in App.razor
2. Collapse/expand sidebar by adding/removing style in div - <div class="sidebar" style="@SidebarCssClass">
3. Pass IsCollapsed boolean to NavMenu.razor page - <NavMenu IsCollapsed="@IsCollapsed" />
4. Add if statements in NavMenu.razor to show only icons/icons + name
