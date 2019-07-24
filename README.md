# Sauce Labs Status Badge Demo

[![Sauce Test Status](https://saucelabs.com/buildstatus/jtack4970)](https://app.saucelabs.com/u/jtack4970)

[![Sauce Test Status](https://saucelabs.com/browser-matrix/jtack4970.svg)](https://saucelabs.com/u/jtack4970)

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
2. Change the username for the badge and matrix URL in the `README.md` file:
    
    * Status Badge:
        ```
        [![Sauce Test Status](https://saucelabs.com/buildstatus/SAUCE_USERNAME)](https://app.saucelabs.com/u/SAUCE_USERNAME)

        ```
    * Browser Matrix:
        ```
        [![Sauce Test Status](https://saucelabs.com/browser-matrix/SAUCE_USERNAME.svg)](https://saucelabs.com/u/SAUCE_USERNAME)
        ```
3. Navigate to the project directory and run:
    ```
    npm install
    ```
4. [Set your Sauce Labs Credentials as env variables](https://wiki.saucelabs.com/display/DOCS/Best+Practices+for+Running+Tests#BestPracticesforRunningTests-UseEnvironmentVariablesforAuthenticationCredentials)
5. Run the test with the following command:
    ```
    npm test
    ```
    
 > For more details refer to the following wiki page:
 > [Using the Status Badges and the Browser Matrix Widget to Monitor Test Results](https://wiki.saucelabs.com/display/DOCS/Using+Status+Badges+and+the+Browser+Matrix+Widget+to+Monitor+Test+Results)
   
<br />
