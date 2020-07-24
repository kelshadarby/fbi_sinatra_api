![Sinatra API Logo (1)](https://user-images.githubusercontent.com/55028065/88423267-bf8b5200-cda8-11ea-8e2c-f05ed51bbd8b.png)

## Contents
- [About](#about)
- [Getting Started](#getting-started)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Running the Tests](#running-the-tests)
- [End to End Testing](#end-to-end-testing)
- [Built With](#built-with)
- [API's & Tools](#api-tools)
- [Contributors](#contributors)

## <a name="about"></a> About

The FBI Sinatra API is a background worker for the Crime Time app, viewable [here](https://github.com/kelshadarby/crime_time). This API gathers data from the [FBI's Crime Statistics API](https://crime-data-explorer.fr.cloud.gov/api) and returns it in serialized JSON to the Crime Time app. The app can then render the data to the user in an easily digestable way.

The FBI Sinatra API uses __Services__, __PORO's__ and __Netflix's [FastJsonapi](https://github.com/Netflix/fast_jsonapi)__ to gather serailize the data in an easily usable fashion.

## <a name="getting-started"></a> Getting Started

Follow the steps below to get you a copy of the project up and running on your local machine for development and testing purposes. 

1. Clone this repo onto your local machine

2. Run the following command in your terminal to get the code up and running on your local machine 

- Make sure to run this without the $

```
$ bundle install
```

### <a name="prerequisites"></a> Prerequisites

You will need to have the following in order to run this app on your local machine.

```
Ruby 2.5.3
Bundler version 2.1.4
```

### <a name="installation"></a> Installation

Follow the steps below to view this app locally

Step 1:
    Start the local rails server by running the following command
```
$ rails s
```

Step 3:
  View the website locally by visiting http://localhost:3000/

## <a name="running-the-tests"></a> Running the tests

__To run the entire test suite on your local machine run the following command__
```
$ bundle exec rspec
```

Note: You may be able to run this command using just `exec`


__To run a specific test file run the following command__

```
$ rspec <file_path>
```

Note: Your file path may look something like `spec/features/items/index_spec.rb`


__To run a specific test within a test file run the following command__
```
$ rspec <file_path>:<line_number>
```

Notes:
- Your line number should be the line of the beginning of the `it` block
- Example: `spec/features/items/index_spec.rb:15`

### <a name="end-to-end-testing"></a> End to End Testing

These tests were written to check that the API endpoints were working as well as checking tha the data is returned as expected. The OAuth process was also tested.

__API Test Example__
```
Example
```

## <a name="built-with"></a> Built With

* [Rails](https://rubyonrails.org/) - The web framework used

## <a name="api-tools"></a> API's & Tools Used

* [FBI Crime Data](https://crime-data-explorer.fr.cloud.gov/api) - Crime Statistics API

## <a name="contributors"></a> Contributors

* [**Kelsha Darby**](https://github.com/kelshadarby)
