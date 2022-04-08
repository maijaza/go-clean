# Go Clean Architecture
Example 

#### Structure:
- api 
    * for swagger
- cmd
    * for start up application
- config
    * for configuaration
- deployment
    * for deployment yaml and docker and jenkins 
- infrastruture
    * for all about framework
    * database
        * for create connection
    * handler
        * for handler route
    * logger
        * for logging
    * repository
        * for implementation repo
- internal
    * for internal package & store usecase and domain
    * {packageName}
        * domain
            * for domain model & entiry
        * usecase
            * for usecase (service interface & implement)
        * repository
            * for repository interface
        
