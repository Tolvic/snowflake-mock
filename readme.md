# Snowflake Stubbing POC
A very simple proof of concept where we stub response from the Snowflake API using Mountebank

## How to setup
Install mount using:

```powershell
npm install -g mountebank
```

## How to run
To run Mountebank run:

```powershell
mb --configfile imposters.ejs
```

You can then call the api using a tool like Postman. A Postman collection is included within this project for you to import.

## Useful Links
* [Mountebank website](https://www.mbtest.org/)
* [Confluence page](https://payroc.atlassian.net/wiki/spaces/RE/pages/2025718013/Mountebank+Configuration+Guide)
* [Lunch and Learn Vid](https://web.microsoftstream.com/video/d4b93080-49f3-4235-b08a-71cba746689b)
* [Tutorial for connecting to Snowflake via Postman](https://community.snowflake.com/s/article/Connect-to-SQL-API-using-Postman)