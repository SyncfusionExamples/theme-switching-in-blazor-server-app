# Theme Switching in Blazor Web App

This repository contains a sample .NET 10 Blazor Web App demonstrating how to implement dynamic theme switching using reusable components, a shared layout, and static assets.

## Features

- **Dynamic Theme Switching**: Updates the active Blazor theme without reloading the app
- **Reusable Theme Switcher Component**: Maintains a `ThemeSwitcher.razor` component for consistent UI composition across pages
- **Shared Layout Experience**: Keeps the theme switcher available across all pages via `MainLayout.razor`
- **Runtime Stylesheet Updates**: Swaps theme stylesheets on demand during runtime
- **Interactive Sample Pages**: Includes Home, Counter, and Weather pages demonstrating Blazor functionality
- **Query String Parameter Support**: Enables theme selection and persistence through URL parameters

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
- [Theme Studio for Blazor components](https://blazor.syncfusion.com/documentation/appearance/theme-studio)