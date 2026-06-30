# Vue Scheduler Integrate with ASP.NET CORE application

This sample demonstrates integrating the [Vue Scheduler](https://www.syncfusion.com/vue-components/vue-scheduler) with an ASP.NET Core application, combining a Vue.js frontend with backend services to build a complete scheduling solution. It showcases data binding, event handling, and real-time updates, providing a practical example of creating modern web applications with interactive scheduling features and efficient frontend–backend communication.

## Features

* **Vue Scheduler Integration**: Fully functional Scheduler component from Syncfusion EJ2 library
* **ASP.NET Core Backend**: RESTful API endpoints for data management
* **Interactive UI**: Responsive and intuitive user interface for event scheduling
* **Data Management**: Complete CRUD operations for scheduler events
* **Modern Architecture**: Separation of concerns between frontend and backend

## Prerequisites

* Visual Studio 2022
* Node.js and npm (for Vue.js development)
* .NET 6.0 SDK or later

## Project Structure

```
VueDemoWithAsp.NetCore/
├── client-app/          # Vue.js frontend application
│   ├── src/             # Source files including components
│   ├── public/          # Static assets
│   └── package.json     # Node.js dependencies
├── Controllers/         # ASP.NET Core API controllers
├── VueCoreConnection/   # Database connection and services
└── Properties/          # Application configuration
```

## How to run the project

1. Checkout this project to a location in your disk
2. Open the solution file using Visual Studio 2022
3. Restore the NuGet packages by rebuilding the solution
4. Navigate to the `client-app` directory and install npm dependencies: `npm install`
5. Run the project from Visual Studio (this will start both backend and frontend)

## Getting Started

For detailed information on getting started with Vue.js and .NET Core 3, refer to [this guide](https://www.c-sharpcorner.com/article/getting-started-with-vue-js-and-net-core-32/).

## Documentation Links

For comprehensive documentation on Vue Scheduler and ASP.NET Core integration, refer to:

**Vue Framework Documentation:**
* [Vue Introduction](https://ej2.syncfusion.com/vue/documentation/introduction)
* [Vue Schedule Component](https://ej2.syncfusion.com/vue/documentation/schedule/getting-started)

**ASP.NET Core Documentation:**
* [ASP.NET Core Introduction](https://ej2.syncfusion.com/aspnetcore/documentation/introduction)
* [ASP.NET Core Schedule Component](https://ej2.syncfusion.com/aspnetcore/documentation/schedule/getting-started)

## Configuration

The application uses configuration files located in the project root:
* `appsettings.json` - Production settings
* `appsettings.Development.json` - Development-specific settings

## Support

For additional support and resources, visit the [Syncfusion documentation portal](https://help.syncfusion.com/).
