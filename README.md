# Antarctic
A sandbox to design a React/Redux application, with a Django/PostgreSQL API, and basic DevOps.

## Overview
Demonstrate capabilities to go from a concept with a basic data set to a fully functional system.

- Data
- Design
- User Interface implementation
- API Implementation
- Database implementation

### Capabilities

- Ability to design a user interface given list of basic user needs
  - Create a design system for the application
- Ability to implement a user interface based on user flows and user interface designs
  - [React](https://reactjs.org/)
  - [Redux](https://redux.js.org/)
  - [ChartJS](https://github.com/reactjs/react-chartjs)
  - [MapboxGL](https://uber.github.io/react-map-gl/#/)
- Ability to extract data from abstract data sources
  - [List of Research stations in Antarctica](https://en.wikipedia.org/wiki/Research_stations_in_Antarctica)
  - [REference Antarctic Data for Environmental Research](https://www.scar.org/data-products/ref-data-environmental-research/)
- Ability to make data available through a REST API and GraphQL interface
  - PostgreSQL
  - PostGIS
  - Django
  - [Graphene](http://docs.graphene-python.org/projects/django/en/latest/)
- Ability to automate DevOps
  - [Continuous Integration]()
  - [Continuous Deployment]()
  - [Unit Testing with Jest](https://jestjs.io/docs/en/tutorial-react)
  - [Python Code Quality Authority Scanning](https://github.com/PyCQA) (i.e., Bandit, PyDocStyle, PyCodeStyle, pylint-django)
  - [Error Tracking](https://sentry.io/welcome/)
- Ability to create documentation
  - Installation
  - Data Entry
  - Contribution

### Data
We will use a list of Antarctic Research Stations and weather data associated with those stations.

- [List of Research stations in Antarctica](https://en.wikipedia.org/wiki/Research_stations_in_Antarctica)
- [REference Antarctic Data for Environmental Research](https://www.scar.org/data-products/ref-data-environmental-research/)

### Basic User Needs

These are of course imaginary needs and are fabricate around specific tasks. They are not intended to imply any kind of user experience or human centered design process.

#### User Needs 
- Identify research stations
  - by country
  - by status
- Identify environmental data about specific research stations

#### User Data Management Tasks
- Import new list of research stations
- Add a new research station
- Edit an existing research station
- Remote a research station
- View a research station detail page
- View a list of research stations
- Filter a list of research stations
- View all research stations on a map
- View a details about a research station by clicking on a map pin
- Download a GeoJSON file of all research stations (excluding environmental indicators)
- Download a CSV file of all research stations
- Download a Shapefile of all research stations

- Import a list of research station environmental indicators
- Add a new measurement
- Edit an existing measurement
- Remove a measurement
- View multiple measurements on a time series chart
- View a table of measurements

- View sources of all data on site

### Design System
Based on user needs and user tasks listed above the following user interface components will be required in our design system.

- Creating a design system for our application
  - Requirements
    - Color usage
    - Typographic usage
    - Form component
    - Header/Footer component
    - Primary navigation
    - Secondary navigation
    - Card component
    - List component
    - Table component
    - Map component
    - Chart component