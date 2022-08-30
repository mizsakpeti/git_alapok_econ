# Requirements for the git server

## Current status

* Increasing number of coding related project
* All project stored separetly, diverse folder structure
* Command line only - high adaption effort
* No approval process, can get chaotic with multiple users
* Sharing with 3rd. party through OwnCloud:
  * complex to set up
  * unintentional delete
  * syncronization issues
  * file conflicts
* Redundant data storage in Q

## Main goals

* Have a separete repository for each project
* Each project should be accessible to users specified by the project owner
* Possibility to add external users for cooperation (interns, R&D partners, subcontractors)
* Self hosted for data security reasons?

## Important features

* User friendly GUI to allow/track simultanious development
* Basic git workflow (branches, pull, push, merge)
* Pull requests (merge requests) - code review and approval

## Good to have

* Bitrix integration oportunity

## Not necesarily needed

* CI/CD (continuous integration / continuous deployment)
  * automatic testing
  * package building
* Release control (versions)
* Security testing (automatic testing for security leaks)

## Next steps

### Step 0: git tutorial and training

* In progress. Responsible:
  * [Anna Nagy](mailto:anna.nagy@econengineering.com)
  * [Gergely Erdős](mailto:gergely.erdos@econengineering.com)
  * [Milán László](mailto:milan.leszlo@econengineering.com)
  * [Péter Mizsák](mailto:peter.mizsak@econengineering.com)
* [git_alapok](https://github.com/mizsakpeti/git_alapok_econ)

### Step 1: git.econgngineering.com

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
  * Not self-hosted (only with DataCenter)
  * Easy to start-with
  * Possible to have "private" repository
  * Free storage limit: 1 GB (large file storage)
  * Free user limit: 5
