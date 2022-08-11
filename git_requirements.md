# Requirements for the git server

## Main goals

* Have a separete repository for each project
* Each project should be accessible to users specified by the project owner
* Possibility to add external users for cooperation (interns, R&D partners, subcontractors)
* Self hosted for safety reasons?

## Important features

* User friendly GUI to allow/track simultanious development
* Basic git workflow (branches, pull, push, merge)
* Pull requests (merge requests) - code review and approval

## Not necesarily needed

* CI/CD (continuous integration / continuous deployment)
  * automatic testing
  * package building
* Release control (versions)
* Security testing (automatic testing for security leaks)

## Good to have

* Bitrix integration oportunity

## Possible solutions

* [GitLab](https://about.gitlab.com/pricing/)
  * Possible to self-host
  * free community edition

* [GitHub](https://github.com/pricing#compare-features)
  * Not self-hosted (only at enterprise level)
  * Easy to start-with
  * Possible to have "private" repository
  * Free storage limit: 500Mb
  * Free user limit: unlimited

* [BitBucket](https://www.atlassian.com/software/bitbucket/pricing)
  * Not self-hosted (only at enterprise level)
  * Easy to start-with
  * Possible to have "private" repository
  * Free storage limit: 1 GB (large file storage)
  * Free user limit: 5
