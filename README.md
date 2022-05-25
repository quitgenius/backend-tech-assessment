# Overview

As part of the user platform, user information is received in bulk as a file from some of the partners, and these files need to be parsed and saved in the data store. This process involves parsing, some data cleaning and saving the result in the data store to be used later by different parts of the platform.

## Requirements

Requirements will be provided at the beginning of the exercise.

## File Structure

File has a very basic structure which is in CSV format and each row represents a user with the following order of fields:
id, firstName, lastName, dateOfBirth(dd.mm.yyyy), email, postcode, membershipType, status

### Sample Data

```
1,John,Brown,01.01.1981,john.brown@example.com,sw186tx,standard,active
2,Jane,Smith,11.02.1961,jane.smith@example.com,w57dy,standard,inactive
3,Ben,Cooke,10.12.1972,ben.cooke@example.com,w13xy,premium,active
4,Robert,White,20.10.1982,robert.white@example.com,s11tw,premium,active
```

## Prerequisites

* AWS account setup on local machine, see instructions [here](https://www.youtube.com/watch?v=BNH4i7CQ4Oc). Note: this exercise should be covered by AWS always free tier.
* NodeJS, version 14+

## Instructions

* Clone and setup the exercise by running `npm i`.
* Read the requirements and ask any questions for points that are not clear.
* Implement your solution and deploy it to AWS as often as you want by running `npm run deploy`.
* Run and test your solution with the proctor at the end of the exercise.
* Finally, remove the service from AWS by running `npm run remove`.

## Commands

```
# install dependencies
npm i

# deploy to AWS
npm run deploy

# remove from AWS once exercise ended
npm run remove
```

## Suggestions and Notes

* `Serverless.yml` and `handler.js` are provided in the repo, please use it as a starting point for your task.
* Feel free to use google and any online documentation, treat it as how you would implement this in your daily job.
* Implement the solution the way you think it is the
* Don't worry if you can't finish all the requirements, we are more interested in how you approach the task at hand and how you implement the solution.
* The aim is to complete the assessment to the best of your ability within 45-50 minutes, leaving us 10-15 minutes to talk through your result, your approach, what you might have done differently given more time, and what you would change for next time.
* The proctor's camera will be off during the time you spend coding, but they will be available for any questions you might have during the assessment. Anything related to the logistics or expectations of the task can be answered, but we can't offer any technical guidance.
