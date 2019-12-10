![Rentancy](assets/logo.png)
# Rentancy ~ Inventory GraphQL Explorer

## What it should do
The application should consume the [JSON data](data/) files and create an in-memory data structure.
You should then create a simple GraphQL implementation that adheres to the [GraphQL Schema](schema.graphql) using the 
in-memory data.

## Rules
The test application can be written using any language you believe to be pertinent to the position you are applying for.
You are free to use any libraries that aid the creation of the application, but be conscious that the purpose of this
exercise is to demonstrate your abilities.

In addition:
 
 1) All dependent libraries must be publicly available. 
 1) Clear and concise instructions for how to build and run the application should be included within the code, e.g. `README.md`
 1) The code must be your own work. If you have a strong case to use a small code snippet of someone else's e.g. a
 boilerplate function, it must be clearly commented and attributed to the original author.
 1) The JSON data cannot be changed, and must be loaded from the JSON files supplied, so it can easily be replaced with others files.

## Instructions
First, ``checkout`` this project to obtain the [tenants](data/tenants.json), [tenants](data/properties.json), 
[agreements](data/agreements.json) JSON files and [GraphQL Schema](schema.graphql), then create a separate project for 
your application using your chosen tech stack.

## Data
There are three JSON files:
1) [tenants.json](data/tenants.json)
1) [properties.json](data/properties.json); and 
1) [agreements.json](data/agreements.json)

This data represents three tenancy agreements for three properties and three and tenants. This data should map directly 
onto the model outlined in the [schema.graphql](schema.graphql).

The inventory property within the agreements represents a score from 1 to 5 for the current condition of the item, 1
being very poor, and 5 being excellent.

There should be no tricks in this data, if there is a problem mapping it to the GraphQL schema, please let me know at
[declan.newman@sourcestream.co.uk](mailto:declan.newman@sourcestream.co.uk) so we can rectify it.

## Summary
The aim of this test is to understand your coding style, skills and approach to solving problems. We understand that you
probably have plenty of other things that you'd rather be doing, so for that reason we estimate that the test should
take approximately 3 ~ 4 hours. If after that time you have an unfinished project, that's fine. Just document what you
would have done to complete it, and submit to us.

**_You should choose an approach that you feel demonstrates your expertise and suitability for the position._**

## How to submit your test
**PLEASE DO NOT TRY AND PUSH YOUR CODE INTO THIS REPOSITORY.** This project is merely a location to hold the test data 
and description of the test.

Preferably you will submit your code via a public repository you own e.g. your own [Github](https://github.com/) or 
[Bitbucket](https://bitbucket.org/) account. However, you may also submit your code via email or file sharing mechanism 
- e.g. Dropbox - using an archive, such as zip file or tarball (please consider the size of the file before emailing). 
