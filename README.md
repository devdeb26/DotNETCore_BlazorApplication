# DotNETCore_BlazorApplication

Setup Notes:
- When you encounter an **error while using the run/debug button** and are unable to add the BlazorApp default configuration to the launch.json file right away, select another configuration, then re-add the configuration by clicking 'C#' and selecting 'Blazor Default.
- **Set up Hot Reload** when encountering issues with a Blazor page not loading, even after updating texts or adding components. Make sure the 'Watch' JSON properties in launchSettings.json and the 'hotReloadEnabled' property are present to enable Hot Reload. Then add watch in launch.json configuration.
