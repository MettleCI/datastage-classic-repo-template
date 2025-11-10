     __  __      _   _   _       ____ ___
    |  \/  | ___| |_| |_| | ___ / ___|_ _|
    | |\/| |/ _ \ __| __| |/ _ \ |    | |
    | |  | |  __/ |_| |_| |  __/ |___ | |
    |_|  |_|\___|\__|\__|_|\___|\____|___|
    MettleCI DevOps for DataStage
    (C) 2021-2022 Data Migrators

An example GitLab CI pipeline can be found in `.gitlab-ci-devops.yaml`. 

These templates make use of the following reusable pipeline workflows:

| File                     | Description |
|--------------------------|-------------|
| `.templates/ccmt-template.yml`       | CCMT Pipeline Template |
| `.templates/compliance-template.yml` | Compliance Pipeline Template |
| `.templates/deploy-template.yml`     | Deployment Pipeline Template |
| `.templates/unittest-template.yml`   | Unit Test Pipeline Template |

For GitLab to be able to make use of these example pipelines you'll need to copy the contents of this directory into the root directory of your repository.

See the documentation [here](https://docs.mettleci.io/gitlab).

_(Data Migrators source reference: gitlab-devops)_