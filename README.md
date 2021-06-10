#  REST API PROJECT EXERCISE

##### TOOLS AND EXPLANATIONS
>- The project has been prepared based on Cucumber BDD style.    
>- Maven build management tool is used in this project by Java language.
>- LOG4J and SL4J information is provided as a logging design.
>- In the project that includes two scenarios, the first scenario verifies by receiving information from the live API server(https://petstore.swagger.io), 
>while the second scenario verifies by receiving information over the prepared Wire Mock Server.
>- For the test, a study has been done in the `v2 / pet / findByStatus` end point.
>- A special tag(`@wire_mock`,`@live`) was used in the project. Thus, the desired feature can be run in Runner.

##### HOW TO RUN TESTS
```sh
 -> Under the runner package "Runner" right click and run Runner. "src > test > java > runner > Runner"
 -> mvn test --> in the IDE console or navigate project path in command line and run.
```
 
Ahmet VURDEM
QA Automation Engineer     
https://www.linkedin.com/in/ahmet-vurdem