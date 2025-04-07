# App of Apps

Welcome to the App of Apps! This is the gateway to get your services deployed
on our infrastructure.

## How it Works

The App of Apps repository contains folders that correspond to each of our
available environments. Currently those are:

* development
* production

Each folder contains a subfolder that corresponds to a deployed service. The
subfolders contain an [Argo CD Application manifest](https://argo-cd.readthedocs.io/en/latest/user-guide/application-specification/)
that defines how the service is deployed.

## Deploying your Application

To deploy your application:

1. Make sure it's registered as a Component in the internal developer portal.
1. Verify that the application has a corresponding manifests repository in our GitHub Org.
1. Use the **Deploy Application to Environment** Template in the internal developer portal.

Using the **Deploy Application to Environment** template will open a pull
request against the App of Apps repository. The [Platform Engineering team](https://github.com/orgs/rhdh-demo-gh/teams/platform-engineering)
will review and merge the pull request.