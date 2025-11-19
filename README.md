<img width="241" height="305" alt="image" src="https://github.com/user-attachments/assets/12392903-82ee-4faa-bec6-f7a79a09140b" /># Heatmap
---------

Heatmap is an ASP.NET Core web application for visualizing data through interactive heatmaps and KPI dashboards. It demonstrates modular Razor Pages architecture, responsive UI design, and basic analytics components.

## Architecture

- **Framework**: ASP.NET Core (Razor Pages)
- **UI**: Bootstrap 5, custom CSS
- **Routing**: Razor Pages with shared layout
- **Components**:
  - Heatmap grid with randomized values
  - Statistics dashboard (Users, Revenue, Sessions, Conversion Rate)
  - Navigation sidebar with modular page links

## Setup

### Prerequisites
- .NET SDK 7.0+
- Visual Studio 2022+
- Local HTTPS trust (for development)

### Run Locally  
```bash
dotnet dev-certs https --trust
dotnet run

Or run directly in Visual Studio with F5 (debug) or Ctrl+F5 (without debugging).

### Notes
Heatmap values are randomized for demo purposes.
KPI metrics are placeholders and can be connected to real data sources.
