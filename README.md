# booster-archetype
A Maven archetype to quickly get a skeleton booster.

## General steps needed for a complete Booster implementation

1. A new maven module is required that will reside in a new github repo
2. Spring Boot BOM should be revisited as some starters or dependencies could be missing
3. The code needs to be developed including a web page
4. Create Unit and Integration tests
5. Upstream documentation needs to be created that describes how one can play with the mission
6. A new entry needs to be added within the Booster catalog
7. The Jenkins jobs need to be updated in order to test the new Booster
8. Create Openshift templates
9. Extend Testsuite