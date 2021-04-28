# teamcity-rest-api

**DEPRECATION NOTICE** This is deprecated as Jetbrains (finally) created a nice [reference documentation](https://www.jetbrains.com/help/teamcity/rest/teamcity-rest-api-documentation.html). Thanks for using this.

A Swagger generated documentation of the Teamcity REST Api

This is a generated documentation made using swagger and the TeamCity Swagger endpoint at https://<your teamcity server>/app/rest/swagger.json.

To regenerate:

    curl https://<your teamcity server>/app/rest/swagger.json  > teamcity.json
    swagger-codegen generate -i teamcity.json -l html -o .   

Note: The downloaded json file includes your ci server name. If you don't want it to be included, please remove it from the json file before pushing.
