Maven based pipeline which:

* creates a new version then builds and deploys the project into the Nexus repository
* runs an integration test in the **Test** environment
* stages the new version into the **Stage** environment for the project
