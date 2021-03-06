# Changelog

## 05/03/2017 - Version 0.4.22

Release changes:

* Bumps some library versions ([#308](https://github.com/47deg/sbt-org-policies/pull/308))


## 05/02/2017 - Version 0.4.21

Release changes:

* Wait between each GitHub request ([#305](https://github.com/47deg/sbt-org-policies/pull/305))


## 05/02/2017 - Version 0.4.20

Release changes:

* Enables Coursier by default ([#303](https://github.com/47deg/sbt-org-policies/pull/303))
* Refactor GithubOps and FileHelper ([#274](https://github.com/47deg/sbt-org-policies/pull/274))
* Fixes commit images ([#304](https://github.com/47deg/sbt-org-policies/pull/304))


## 05/01/2017 - Version 0.4.19

Release changes:

* Fixes Autocheck Dependency Triggering ([#261](https://github.com/47deg/sbt-org-policies/pull/261))
* Adds basic docs to create a new project ([#262](https://github.com/47deg/sbt-org-policies/pull/262))
* Adds Logging Statements ([#264](https://github.com/47deg/sbt-org-policies/pull/264))
* Adds syntax to make easier the use of command aliases ([#270](https://github.com/47deg/sbt-org-policies/pull/270))
* Improves GitHubOps ([#271](https://github.com/47deg/sbt-org-policies/pull/271))
* Add iota-core as a 47 dependency ([#276](https://github.com/47deg/sbt-org-policies/pull/276))


## 04/27/2017 - Version 0.4.18

Release changes:

* Fixes maven and scalacenter badges ([#260](https://github.com/47deg/sbt-org-policies/pull/260))


## 04/25/2017 - Version 0.4.17

Release changes:

* Dependencies auto-check Enhancements ([#258](https://github.com/47deg/sbt-org-policies/pull/258))


## 04/25/2017 - Version 0.4.16

Release changes:

* Adds New default settings for sbt-microsites ([#256](https://github.com/47deg/sbt-org-policies/pull/256))
* Adds Optional publishMicrosite ([#257](https://github.com/47deg/sbt-org-policies/pull/257))


## 04/24/2017 - Version 0.4.15

Release changes:

* Fixes maven central badge ([#245](https://github.com/47deg/sbt-org-policies/pull/245))
* Fixes pom.xml in afterSuccess sbt task ([#251](https://github.com/47deg/sbt-org-policies/pull/251))
* Unifies FileType and validation types ([#252](https://github.com/47deg/sbt-org-policies/pull/252))


## 04/21/2017 - Version 0.4.14

Release changes:

* orgPublishRelease shouldn't be invoked as aggregated task ([#239](https://github.com/47deg/sbt-org-policies/pull/239))


## 04/20/2017 - Version 0.4.13

Release changes:

* Method for updating ref with dir contents ([#232](https://github.com/47deg/sbt-org-policies/pull/232))
* Script Runnable Items Enhancements ([#233](https://github.com/47deg/sbt-org-policies/pull/233))


## 04/19/2017 - Version 0.4.12

Release changes:

* Creates the scalafmt in orgCreateFiles and update docs task ([#220](https://github.com/47deg/sbt-org-policies/pull/220))
* Avoids committing files not modified by the plugin ([#226](https://github.com/47deg/sbt-org-policies/pull/226))


## 04/19/2017 - Version 0.4.11

Release changes:

* Update docs and commit files in release process ([#174](https://github.com/47deg/sbt-org-policies/pull/174))
* Filtered Badges in case of sbt-plugins ([#175](https://github.com/47deg/sbt-org-policies/pull/175))
* Fixes the aggregated `publishSigned` for multimodule projects ([#176](https://github.com/47deg/sbt-org-policies/pull/176))
* Makes the autocheck module Self-Managed ([#215](https://github.com/47deg/sbt-org-policies/pull/215))


## 04/18/2017 - Version 0.4.10

Release changes:

* Changes the default badge configuration ([#162](https://github.com/47deg/sbt-org-policies/pull/162))
* Avoids some task executions in non-root modules ([#171](https://github.com/47deg/sbt-org-policies/pull/171))
* Adds a new setting for defining the project name ([#172](https://github.com/47deg/sbt-org-policies/pull/172))
* ScalaJS Testing Bug fix ([#173](https://github.com/47deg/sbt-org-policies/pull/173))


## 04/17/2017 - Version 0.4.9

Release changes:

* Replace text engine ([#156](https://github.com/47deg/sbt-org-policies/pull/156))
* Maven Central Badge ([#157](https://github.com/47deg/sbt-org-policies/pull/157))
* Bumps monix and http4s versions ([#160](https://github.com/47deg/sbt-org-policies/pull/160))


## 04/13/2017 - Version 0.4.8

Release changes:

* Sorts contributors out by name ([#144](https://github.com/47deg/sbt-org-policies/pull/144))
* Readme common badges ([#143](https://github.com/47deg/sbt-org-policies/pull/143))
* Do not import everything by default ([#145](https://github.com/47deg/sbt-org-policies/pull/145))
* Fixes maven central and github isses badges ([#147](https://github.com/47deg/sbt-org-policies/pull/147))
* Bumps mockito version ([#149](https://github.com/47deg/sbt-org-policies/pull/149))
* Removes trailing space from changelog template ([#150](https://github.com/47deg/sbt-org-policies/pull/150))
* SOP-138 Fixes Enforcement Tasks ([#153](https://github.com/47deg/sbt-org-policies/pull/153)) 
      

## 04/11/2017 - Version 0.4.7

Release changes:

* Turns orgPublishRelease into a sbt command ([#142](https://github.com/47deg/sbt-org-policies/pull/142)) 
      

## 04/11/2017 - Version 0.4.6

Release changes:

* orgGithubTokenSetting as Env Var Name ([#136](https://github.com/47deg/sbt-org-policies/pull/136))
* Fixes the check for cross scala ([#137](https://github.com/47deg/sbt-org-policies/pull/137))
* Enforces a "used by" section in the README file ([#139](https://github.com/47deg/sbt-org-policies/pull/139))
* Bumps g4s version. Adds other minor changes ([#140](https://github.com/47deg/sbt-org-policies/pull/140)) 
      

## 04/10/2017 - Version 0.4.5

Release changes:

* Adds New Libraries ([#131](https://github.com/47deg/sbt-org-policies/pull/131))
* Adds tests for GitHubOps ([#134](https://github.com/47deg/sbt-org-policies/pull/134))
* SOP-28 - Enforce travis.yml file with standard tasks ([#133](https://github.com/47deg/sbt-org-policies/pull/133)) 
      

## 04/07/2017 - Version 0.4.4

Release changes:

* Removes Compilation Warnings ([#128](https://github.com/47deg/sbt-org-policies/pull/128))
* SOP-122 - Switch from CrossVersion.full to CrossVersion.patch ([#129](https://github.com/47deg/sbt-org-policies/pull/129)) 
      

## 04/07/2017 - Version 0.4.3

Release changes:

* SOP-119 After CI Success as a Command ([#121](https://github.com/47deg/sbt-org-policies/pull/121))
* SOP-80 Auto checking Deps from SBT module ([#123](https://github.com/47deg/sbt-org-policies/pull/123))
* Fixes Github Token ([#124](https://github.com/47deg/sbt-org-policies/pull/124))
* Fixes Unstaged Modified Files issue ([#127](https://github.com/47deg/sbt-org-policies/pull/127)) 
      