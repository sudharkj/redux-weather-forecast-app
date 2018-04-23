# Redux Weather Forecast App

A redux app to forecast weather using ajax requests to [openweathermap/forecast5](https://openweathermap.org/forecast5).

## Background

The project was bootstrapped with [Create React App](https://github.com/facebookincubator/create-react-app).

Find the most recent version of how to perform common tasks at [create-react-app/README.md](https://github.com/facebookincubator/create-react-app/blob/master/packages/react-scripts/template/README.md).

## Run The App

1. Follow [cloning a repository](https://help.github.com/articles/cloning-a-repository/) if the project is not available locally.
1. Go to the root directory of the repository.
1. Install the dependencies and start the app.

```text
$ npm install
$ npm start
```

## Demo Docs

* App starts with only a search bar.

![Initial State](/assets/img/initial_state.png)

* Searching for a city in _US_ shows the weather forecast for next five days. For example, searching for _new york_ updates the app with forecast for next five days.

![New York Select](/assets/img/new_york_search.png)

* Searching for every other city in _US_ updates the city data in the app if exists or adds a new row. For example, searching for _seattle_ updates the app with forecast for next five days. Note that search bar is reset after updating the app with the latest query result.

![Seattle Search](/assets/img/seattle_search.png)