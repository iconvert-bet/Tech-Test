# iConvert Technical Test

## Introduction

Welcome to the iConvert Technical Test!

We hope that you find this exercise fun and interesting. There are no trick questions; we want to see your solution to a simple problem with well thought-out and well structured code.

## Tasks

We realise everyone has different levels of skill and experience when it comes to development so we have listed different levels of tasks below for you to choose from. If you do not have the time or the knowledge to complete them all then that's ok, we just want to see how you approach the problem and get a feel for how you code.

There are some tasks that could be too big to implement, but you may also describe how you _would_ tackle them (given more time/resources) in the covering note of your submission.

#### Basic Tasks
* Create an API endpoint to Create and Read "Campaigns"
* A Campaign is a pre-registration promotion for an igaming site and should consist of:
    * Unique ID
    * Title
    * Enabled (true/false)
    * Start Date
    * End Date
    * Voucher Code
* Your endpoint should return JSON

#### Intermediate Tasks
* DB Migrations/Seed data _(it's ok not to actually create the DB, but please show you understand how it would be created and how the API would talk to it)_
* Add Delete and Update operations to your endpoint
* Allow campaigns to be owned by different sites _(the site object doesn't need to be created, but assume it would be represented by some sort of id)_
* Add some Unit/Functional/Integration tests
* Store an image with the campaign

#### Advanced Tasks
* Include a Dockerfile and/or docker-compose.yml
* Authentication
* Authorisation
* What could a deployment look like? (Infra/CI/CD)
* Logging - system/application
* How would you implement API Versioning / API Spec?
* Monitoring / Alerting
* Local development for multiple developers
* ENV variables and secret management
* Code version control and branch/development life-cycle

#### Additional Tasks
* Implement a front end that displays a table of the campaigns _(don't worry too much about design, feel free to use bootstrap or some basic HTML/CSS)_

## Languages

We use a mixture of coding languages at iConvert but out APIs are built in PHP (specifically Laravel), our front-end uses Vuejs and our event streaming system uses NodeJS. But for this tech test we are looking to get a sense of how you code, so please use the language/framework/app/tool with which you feel most comfortable.

## The Deliverable

Please submit a git repository (Github/Bitbucket etc.) that includes your code, along with a README that contains:

* A covering note explaining the technology choices you have made.
* Any instructions required to run your solution and tests in a unix environment.
