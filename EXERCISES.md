# Exercises Sheet

## Documentations
[Rest assured documentation](https://github.com/rest-assured/rest-assured/wiki/Usage)

[Swagger Validator Rest Assured documentation](https://bitbucket.org/atlassian/swagger-request-validator/src/b295b1aad09dbb214107340a7acc2a978db50813/swagger-request-validator-restassured/?at=master)

## Specs

For each test, you have to write the specs as the following example:

````
SCENARIO: I wanna blablabla...
GIVEN:
    I have blublublu...
WHEN:
    I <action> bliblibli...
THEN:
    I should have blobloblo...
````

Write tests for:

    Basic:
        1) Get all users
        2) Get one user
        3) /!\ Special /!\: Disable a user
        4) Delete a user
        
    5) Implement new function: 
        Allow to sort the users by firstname/lastname/age/active
        Example: http://localhost:8080/users?sortBy=age
                
    Implement more fun <3 :
        6) Get only enabled/disabled users
        7) Delete multiple users
        8) Update a user