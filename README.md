# Innovations Using Dynatrace APIs
## Pull Data from Dynatrace APIs and Export it to Excel
#### Current State
##### Host Details
Tool for fetching host details that are installed with OneAgent. It will fetch all the hosts that are installed with OneAgent even if it is disabled. 

##### Fetch Problems in Dynatrace Environment
Problem details will be fetched from the Dynatrace Environment. Problem details, such as Problem **Display Name, Status, Root Cause (Boolean), Impacted Entity, Start Time, and End Time** of all the problems specified in the given timeline. 

### What it Uses?
This uses Dynatrace APIs to fetch the details that are monitored in the Dynatrace portal. 

### Get Started
This tool supports offline installation thus, you can clone it and run it anywhere. As an online version, it is hosted in Firebase. To access, please visit [here](https://dtis-hosts.web.app)

* Host Details: [here](https://dtis-hosts.web.app)
* Problem Details: [here](https://dtis-hosts.web.app/problems.html)

#### Conditions to access Online Version
Please make sure, Dynatrace Tenant is accessible for the internet and also it is configured with an SSL certificate. 

#### Offline Version
No servers need to be installed to run the application. Just copy all the files in the public folder to anywhere you want and run index.html in any browser, this will start working and then you can export the data to excel or PDF or to CSV version. 

## Contribution
Since this is an open-source, feel free to contribute to this project and we suggest you add more features other than fetching only hosts data. 

## Future Updates
We will update to all sets of APIs other than hosts in the environment.

## Libraries Used
1. Materialize for Frontend
2. Datatables to display data

## Compaitability Browsers
* Microsoft Edge
* Google Chrome
* Mozilla Firefox

_Note: Please use the latest browser for better experience_

## Commit Changes
#### v0.0.2
* Added Problem Details Fetch
* Bug Fixes

#### v0.0.1
* Fetch Host Details
* Initial Commit