# Frontend Cars Test

Please create a new git repo (don't fork this one) and follow the instructions below.

Once you have finished, please email us the URL to your repo and provide instructions to run the application.

It's expected that you will spend 2-3 hours on the test. 

## The Epic

"As a User, I would like a UI to be able to add, retrieve, update and remove cars to an existing RESTFul API."

## Stories

This epic has been divided into stories ordered by priority (lowest to highest):

1. Create a car
1. List created cars
1. Update a car
1. Delete a car

*Note:* This isn't a test of your design skills.

## The backend API 

To do this test you will need to run the backend API on your local machine using docker.

Instructions on the API and how to get it running are here: 

https://github.com/ecsdigital/cars-test-api

NOTE: If you can't get the api to work, for whatever reason, don't spend a lot of time fixing it or let it block you.
Stub out your API requests with fake responses using an appropriate asynchronous stub (`setTimeout` or `Promise.resolve` etc). 

### Testing

All features should be covered by some tests; what kind of test is up to you. 
They don't need to be extensive (we just need an idea of your general approach to testing your application).

## Limitations

You can use whatever you want to bootstrap the application (e.g. CRA).

You can use whatever online resources you want (aside from copy-pasting large chunks of code).

You are encouraged to use any frameworks or libraries you feel comfortable with.

You will be asked about the code you submit, so you should be able to explain why every line is there.

Typescript is fine but not required.

## Subsequent stories

These are stretch goals if you have time (you can do them in any order):

1. Apply styling to your components (we are interested how you tackle this rather than how it looks).
1. Handle frontend form validation (e.g. string length or data-type checks)
1. More tests! (e2e? cypress?)
1. Apply sorting to the list of cars
1. Apply filtering to the list of cars
1. Host you application on some free hosting (e.g. https://zeit.co/)
