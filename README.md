# news-reader-react

A news reader app made using ReactJS and Redux.

### 

## Features

- When the app is opened for the first time, the user is asked to choose between
  **one or more** news sources from a list of available news sources
- After that, the user is shown a list of news from the selected sources (sorted by
  publish-time, descending)
- Clicking on the news story will redirect to the relevant news page
- At any point, the user can update their news source selection, thereby updating
  the list of news in the feed
- The user’s choice of news sources should persists across browser sessions. So if you are using the app for the
  second time, you should directly hit the news-list page.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

_Node.JS and npm must be installed. Download and install them from [here](https://nodejs.org)._

### Installing

Follow these steps to run this project in your local computer.

```
$ git clone https://github.com/Anvit3/react-news-reader/
$ cd react-news-reader
$ npm i
```

Now, to run both the project on port `3000`, run:

```
$ npm start
```

Go to `http://localhost:3000` to view the app.

## Built With

- [React.JS](https://reactjs.org/) -Frontend library used in the project.
- [Redux](https://redux.js.org/) - Used in addition to React.JS for state management.
- [News API](https://newsapi.org) - Used for fetching news from different sources.

## Authors

- **Anvit D** - [Anvit3](https://github.com/Anvit3)

## License

This project is licensed under the MIT License.
