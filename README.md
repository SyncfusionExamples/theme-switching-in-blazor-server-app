# Theme Switching in Blazor Web App

This sample demonstrates how to switch themes dynamically in a .NET 10 Blazor Web App using reusable components, layout files, and static assets.

## Overview

The sample includes:

- A reusable theme switcher component (`ThemeSwitcher.razor`)
- A main layout with theme support (`MainLayout.razor`)
- A navigation menu (`NavMenu.razor`)
- Sample pages (`Home`, `Counter`, and `Weather`)
- Application styles and static assets under `wwwroot`
- A root app component (`App.razor`) that initializes the Blazor Web App and coordinates routing and layout rendering
- A complete .NET 10 Blazor Web App project structure

## Features

- **Dynamic Theme Switching**: Switch between themes at runtime without a page reload
- **Responsive Design**: Bootstrap-based responsive layout
- **Reusable Components**: Modular component structure for easier maintenance
- **Interactive Pages**: Sample pages demonstrating Blazor interactivity
- **Error Handling**: Built-in error and 404 pages

## Prerequisites

- [.NET 10 SDK](https://dotnet.microsoft.com/en-us/download/dotnet)
- [Visual Studio Code](https://code.visualstudio.com/) with [C# Dev Kit](https://marketplace.visualstudio.com/items?itemName=ms-dotnettools.csdevkit) extension
- A supported browser such as Microsoft Edge, Google Chrome, Firefox, or Safari

## Run the sample in Visual Studio Code

1. Open the project folder in Visual Studio Code.
2. Install the recommended extensions if prompted.
3. Open the integrated terminal (`Ctrl + ~`).
4. Restore NuGet packages:

   ```bash
   dotnet restore
   ```

5. Build the project:

   ```bash
   dotnet build
   ```

6. Run the application:

   ```bash
   dotnet run
   ```

7. Open the URL shown in the terminal. The local port may vary depending on your environment and launch profile.

## References

- [Apply Blazor Themes and Switch Dynamically](https://blazor.syncfusion.com/documentation/appearance/themes)
- [Getting Started with Blazor Web App](https://blazor.syncfusion.com/documentation/getting-started/blazor-web-app)
- [Getting Started with Blazor WebAssembly Standalone App](https://blazor.syncfusion.com/documentation/getting-started/blazor-webassembly-app)