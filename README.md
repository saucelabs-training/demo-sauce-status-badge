# Sauce Labs Status Badge Demo
[![CircleCI](https://circleci.com/gh/saucelabs-training/demo-sauce-status-badge.svg?style=svg)](https://circleci.com/gh/saucelabs-training/demo-sauce-status-badge)

#### Status Badge
![Sauce Test Status](https://app.saucelabs.com/buildstatus/spider-sauce-tests)

#### Browser Matrix
![Sauce Test Status](https://app.saucelabs.com/browser-matrix/spider-sauce-tests.svg)

<br />

## Prerequisites:
* [Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)
* [Node/NPM](https://nodejs.org/en/download/)
* [Sauce Labs Account](www.saucelabs.com)

<br />

## How to Run This Demo:

1. Clone this repository:
    ```
    git clone https://github.com/saucelabs-training/demo-sauce-status-badge.git
    ```
2. [Set your Sauce Labs Credentials as environment variables](https://wiki.saucelabs.com/display/DOCS/Best+Practices+for+Running+Tests#BestPracticesforRunningTests-UseEnvironmentVariablesforAuthenticationCredentials)
3. Add the username for the badge and matrix URLs like so:

    * Build Status Badge Example URL:
        ```
        [![Build Status](https://app.saucelabs.com/buildstatus/SAUCE_USERNAME)](https://app.saucelabs.com/u/SAUCE_USERNAME)

        ```
    * Browser Matrix Example URL:
        ```
        [![Browser Matrix](https://app.saucelabs.com/browser-matrix/SAUCE_USERNAME.svg)](https://app.saucelabs.com/u/SAUCE_USERNAME)
        ```
4. Navigate to the project directory and run:
    ```
    npm install
    ```
5. Run the tests with the following command:
    ```
    npm test
    ```

 > Note that the demo pulls build status data from the last automated build. Create a sub-account in order to access specific  individual project data. For more details refer to the following wiki page:
 > [Using the Status Badges and the Browser Matrix Widget to Monitor Test Results](https://wiki.saucelabs.com/display/DOCS/Using+Status+Badges+and+the+Browser+Matrix+Widget+to+Monitor+Test+Results)

<br />
