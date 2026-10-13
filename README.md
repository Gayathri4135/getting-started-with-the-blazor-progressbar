# Getting Started with the Blazor ProgressBar Component

## Overview

This sample demonstrates the Syncfusion [Blazor ProgressBar](https://www.syncfusion.com/blazor-components/blazor-progressbar) component in a Blazor application. The implementation renders a linear ProgressBar configured with segmented visualization, striped styling, animation, active state rendering, and annotation support. The sample shows how ProgressBar appearance and behavior can be customized using built-in properties while displaying a custom loading message inside the progress indicator. This serves as a practical starting point for implementing status tracking and loading experiences in Blazor applications.

## Key Features

- Renders a linear `SfProgressBar` with a value of `50` in a `0–100` range.
- Displays segmented progress using `SegmentCount="8"`.
- Enables striped and active visual states with `IsStriped` and `IsActive`.
- Applies custom track and progress colors using `TrackColor` and `ProgressColor`.
- Uses `ProgressBarAnimation` with a 2000 ms duration.
- Shows a custom `Loading...` message through `ProgressBarAnnotation`.
- Hides the default progress value using `ShowProgressValue="false"`.

## Prerequisites

- [Visual Studio 2022](https://visualstudio.microsoft.com/vs/) or [Visual Studio Code](https://code.visualstudio.com/)
- [.NET SDK](https://dotnet.microsoft.com/en-us/download/dotnet) compatible with the project's target framework

## How to Run the Project

**Visual Studio 2022**

1. Clone or download this repository.
2. Open the `GettingStarted.sln` solution file.
3. Restore NuGet packages.
4. Build the solution.
5. Run the application using **Ctrl+F5**.

**Visual Studio Code**

1. Clone the repository.
2. Open the repository folder in Visual Studio Code.
3. Open the integrated terminal.
4. Navigate to the startup project directory for the hosted application.

```bash
dotnet restore
dotnet run
```

5. Open the local URL displayed in the terminal after the application starts.

## Project Structure

- `GettingStarted.sln` — Visual Studio solution file containing the sample projects.

- `Client/Pages/Index.razor` — Contains the `SfProgressBar` component demonstration and ProgressBar configuration.

## Support and Feedback

- For general product questions, visit the [Syncfusion Community Forum](https://www.syncfusion.com/forums) or [Syncfusion Support](https://www.syncfusion.com/support).
- To report an issue specific to this sample, open a GitHub issue in this repository.
- For implementation details, see the [relevant official Syncfusion documentation](https://blazor.syncfusion.com/documentation/progress-bar/getting-started).

## License

This is a Syncfusion sample project provided to demonstrate product usage. Review the [Syncfusion license terms](https://www.syncfusion.com/sales/pricing?category=ui-components) before using Syncfusion components in your own applications.