# DotNETCore_BlazorApplication

Steps
- Open the command palette in VS Code by pressing **CTRL+SHIFT+P**.
- **Type .NET:** to see the commands you can run with C# Dev Kit!
- Find and **select .NET: New Project** to create a new .NET project.
- Scroll down and **select Blazor Web App**.
- **Choose the folder location** you'd like to save your project.
- **Name the project BlazorApp** in the command palette when prompted. Press Enter to confirm.
  
Setup Notes:
- When you encounter an **error while using the run/debug button** and are unable to add the BlazorApp default configuration to the launch.json file right away, select another configuration, then re-add the configuration by clicking 'C#' and selecting 'Blazor Default.
- **Set up Hot Reload** when encountering issues with a Blazor page not loading, even after updating texts or adding components. Make sure the 'Watch' JSON properties in launchSettings.json and the 'hotReloadEnabled' property are present to enable Hot Reload. Then add watch in launch.json configuration.
