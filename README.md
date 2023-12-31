# Realtime Weather App

A command-line weather app which can display real-time weather data for any location on earth. It is built using Node modules and APIs like WeatherStack.

## GET API KEY

Create an account on Weather Stack and get thier free API key, paste the API key in utils/forecast.js where "weatherUrl" is defined and you are done.

## Run Locally

Clone the project

```bash
  git clone https://github.com/yuvraj0028/command-line-weather-app.git
```

Go to the project directory

```bash
  cd command-line-weather-app
```

Install dependencies

```bash
  npm install
```

Run command

```bash
  node app.js get --location="{Your Location}"
```

## Tech Used

**npm modules** - postman-request, yargs

**client** - NodeJS
