# Random-User-API-Performance-Test

## Technology and Tools Used
- Java
- Apache JMeter

## Scenerio
Finding the actual TPS, if 120000 user give load for 12 hours.
Performing load test on this URL: https://random-data-api.com/api/v2/users
- Finding if the expected TPS (Transaction Per/Second) meet the above requirement. Breaking down the expected TPS in excel sheet and finding the actual TPS.
- Creating another excel sheet where tring to find out the bottleneck/stress test point. (At which point the system starts to show 1% error)

## How to run this project
- Clone this project
- Run the .jmx file on Apache JMeter

## Prerequisite
- Java needed to be installed
- Apache JMeter needed to be installed

## Load Test Strategy Report
![Load test](https://user-images.githubusercontent.com/52536969/215562474-34ebfe0d-e239-4b68-a76c-9cd105863f6a.png)

## Stress Test Strategy Report
![Stress test](https://user-images.githubusercontent.com/52536969/215562560-a2b3385c-31a8-4d63-abc3-76fe5a9ab26f.png)
