
# Covid-19 tracker

this project is meant to track the statistics of covid cases around the world



## API Reference

#### using disease.sh API (https://disease.sh/) [free]

```http
  GET https://disease.sh/v3/covid-19/historical/all?lastdays=all
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `all (for all countries)`| `string`   | it gets u all the countries new cases |

#### Get cases for each country

```http
  GET https://disease.sh/v3/covid-19/countries/usa
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `country_name`      | `string` | **Required**: country_name to fetch |




## Features

- cards for numbers of cases
- a table with sorted data for cases of all world countries
- world map
- chart to display the statistics


## Run Locally

Clone the project

```bash
  git clone https://github.com/oussamachah2020/covid-19-tracker.git
```

Go to the project directory

```bash
cd covid-19-tracker
```

Install dependencies

```bash
  npm install
```

Start the server

```bash
  npm start
```


## 🔗 Links
[![portfolio](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://katherineoelsner.com/)
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/)
[![twitter](https://img.shields.io/badge/twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/OussamaChahidi6)

