# Theme Switching in Blazor Web App

This sample demonstrates theme switching in a .NET 10 Blazor Web App by using reusable components, layout files, and static assets.

## Overview

The sample includes:

- A reusable theme switcher component (`ThemeSwitcher.razor`)
- A main layout with theme support (`MainLayout.razor`)
- A navigation menu (`NavMenu.razor`)
- Sample pages such as Home, Counter, and Weather
- Application styles and static assets under `wwwroot`
- A root app component (`App.razor`) that handles routing and theme selection

The selected theme is applied through the `theme` query string parameter.

## Features

- **Dynamic theme switching** without manual page edits
- **Responsive layout** based on Bootstrap
- **Reusable components** for maintainable UI composition
- **Interactive sample pages** that demonstrate Blazor functionality
- **Built-in error handling** and 404 support

## Prerequisites

- [.NET 10 SDK](https://dotnet.microsoft.com/en-us/download/dotnet)
- [Visual Studio Code](https://code.visualstudio.com/) with the [C# Dev Kit](https://marketplace.visualstudio.com/items?itemName=ms-dotnettools.csdevkit) extension
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