# FIRM PROFILE

## Table of Contents

- [FIRM PROFILE](#firm-profile)
  - [Table of Contents](#table-of-contents)
  - [About Project](#about-project)
  - [Built With](#built-with)
  - [Getting Started](#getting-started)
  - [API Interactions](#api-interactions)
  - [Contributing](#contributing)
  - [Authors](#authors)
  - [Acknowledgements](#acknowledgements)
  - [Show your support](#show-your-support)

## About Project

FIRM PROFILE is a web application that allows user to search for a company, view its profile, and stock prices.
This project relies on [Financial Modeling Prep API](https://financialmodelingprep.com/developer/docs) which provides companies' stock data.

![screenshot](./src/images/FIRM-PROFILE.png)

<!-- ### [Live Demo - Netlify]() -->
<!-- 
### [Project Presentation - YouTube]() -->

## Built With

- ReactJS
- Redux

## Getting Started

- Clone this repo <https://github.com/mugberto/firm-profile>

    ```bash
    git clone https://github.com/mugberto/firm-profile.git
    ```

- Navigate to space-travelers-hub folder/directory

    ```bash
    cd firm-profile
    ```

- On the comandline, at the project's root, run ```npm install``` to install app dependencies

- Next, run ```npm start``` which will run the app in the development mode.

- Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

- ALTERNATIVELY

  - Just run ```npm run build``` which will build the project and generate output files into the ```build``` directory.

  - Go to ```build``` directory and manually open ```index.html``` to interact with the app

- Run ```npm run test``` to run tests.

## API Interactions

Financial Modeling Prep API, this app is interacting/consuming the following endpoints:

- **Fetching company profile - Method(GET)** - <https://financialmodelingprep.com/api/v3/profile/AAPL?apikey=YOUR_API_KEY>
- **Fetching Company list - Method(GET)** - <https://financialmodelingprep.com/api/v3/stock/list?apikey=YOUR_API_KEY>
- **Fetching Stock Historical Prices - Method(GET)** - <https://financialmodelingprep.com/api/v3/historical-chart/1min/AAPL?apikey=YOUR_API_KEY>

Take a look at the [DOCUMENTATION](https://financialmodelingprep.com/developer/docs) for further insights.

## Contributing

Contributions, issues, and feature requests are welcome!

Feel free to check the [issues page](https://github.com/mugberto/firm-profile/issues)

  1. Fork the Project
  2. Create your Feature Branch (`git checkout -b feature/newFeature`)
  3. Commit your Changes (`git commit -m 'Add some newFeature'`)
  4. Push to the Branch (`git push -u origin feature/newFeature`)
  5. Open a Pull Request

## Authors

👤 **Hubert Mugabo**

- GitHub: [@githubhandle](https://github.com/mugberto)
- Twitter: [@twitterhandle](https://twitter.com/mugberto)
- LinkedIn: [LinkedIn](https://www.linkedin.com/in/hubert-mugabo-23144b6a/)

## Acknowledgements

- [ReactJS Organization](https://reactjs.org/) for the amazing [Documentation](https://reactjs.org/docs/getting-started.html) on React.
- [Redux Organization](https://redux.js.org/) for the amazing [Redux Essentials Tutorial](https://redux.js.org/tutorials/essentials/part-1-overview-concepts) on Redux.
- [Financial Modeling Prep](https://financialmodelingprep.com/) for the amazing API.

## Show your support

Give a ⭐️ if you like this project!