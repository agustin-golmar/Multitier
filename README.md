[![...](.resource/image/readme-header.svg)](https://github.com/agustin-golmar/Multitier)
[![...](https://img.shields.io/badge/Java-v12-red.svg?logo=java&logoColor=white)](https://www.oracle.com/technetwork/java/javase/downloads/index.html)
[![...](https://img.shields.io/badge/Infer-v0.17.0-ffc210.svg?logo=facebook&logoColor=white)](https://fbinfer.com/)
[![...](https://img.shields.io/github/issues/agustin-golmar/Multitier?color=purple&label=issues&logo=git&logoColor=white)](https://github.com/agustin-golmar/Multitier/issues)
[![...](https://img.shields.io/badge/release-v0.0.0-blue.svg)](https://github.com/agustin-golmar/Multitier/releases)
[![...](https://www.travis-ci.com/agustin-golmar/Multitier.svg?branch=master)](https://www.travis-ci.com/agustin-golmar/Multitier)
[![...](https://snyk.io/test/github/agustin-golmar/Multitier/badge.svg?targetFile=pom.xml)](https://snyk.io/test/github/agustin-golmar/Multitier?targetFile=pom.xml)
[![...](https://img.shields.io/lgtm/alerts/g/agustin-golmar/Multitier.svg?logo=lgtm&logoWidth=18)](https://lgtm.com/projects/g/agustin-golmar/Multitier/alerts/)
[![...](https://codecov.io/gh/agustin-golmar/Multitier/branch/master/graph/badge.svg)](https://codecov.io/gh/agustin-golmar/Multitier)
[![...](https://api.codacy.com/project/badge/Grade/bc5b0a92562c487f877b48bacdf8e663)](https://app.codacy.com/app/agustin-golmar/Multitier?utm_source=github.com&utm_medium=referral&utm_content=agustin-golmar/Multitier&utm_campaign=Badge_Grade_Settings)
[![...](https://img.shields.io/lgtm/grade/java/g/agustin-golmar/Multitier.svg?logo=lgtm&logoWidth=18)](https://lgtm.com/projects/g/agustin-golmar/Multitier/context:java)
[![...](https://ci.appveyor.com/api/projects/status/9vpc18sb4k6wwl0c?svg=true)](https://ci.appveyor.com/project/agustin-golmar/multitier)
[![...](https://cloud.drone.io/api/badges/agustin-golmar/Multitier/status.svg)](https://cloud.drone.io/agustin-golmar/Multitier)
[![...](https://dev.azure.com/agustin-golmar/Multitier/_apis/build/status/agustin-golmar.Multitier?branchName=master)](https://dev.azure.com/agustin-golmar/Multitier/_build/latest?definitionId=3&branchName=master)
[![...](https://app.codeship.com/projects/7d5f7c60-e8f0-0138-71e9-3a05a7e0f5b6/status?branch=master)](https://app.codeship.com/projects/370115)
[![...](https://api.codeclimate.com/v1/badges/2c8c91b05967d3633d56/maintainability)](https://codeclimate.com/github/agustin-golmar/Multitier/maintainability)
[![...](https://circleci.com/gh/agustin-golmar/Multitier/tree/master.svg?style=svg)](https://circleci.com/gh/agustin-golmar/Multitier/tree/master)
[![...](https://app.fossa.com/api/projects/git%2Bgithub.com%2Fagustin-golmar%2FMultitier.svg?type=small)](https://app.fossa.com/projects/git%2Bgithub.com%2Fagustin-golmar%2FMultitier?ref=badge_small)

[![...](https://sonarcloud.io/api/project_badges/quality_gate?project=agustin-golmar_Multitier)](https://sonarcloud.io/dashboard?id=agustin-golmar_Multitier)

# Multitier Application

A template for multitiered applications.

## Build

You need _Apache Maven +3.6.0_, and _Java SE +12 Release_. Then run:

```bash
$ mvn clean package
```

## Execution

In the root folder, just run:

```bash
$ java -jar multitier.jar
```

You can provide the following additional VM arguments:

* `log.level`: any level supported by _Logback_ (default is _INFO_).
* `log.timezone`: any timezone supported by _Logback_ (default is _America/Argentina/Buenos\_Aires_).

## Correctness

This project uses the following tools to augment its correctness:

* [Checkstyle Validation](https://checkstyle.org/)
* [PIT Mutation Testing](https://pitest.org/)
* [PitMP Testing](https://github.com/STAMP-project/pitmp-maven-plugin)
* [PMD+CPD Source Code Analyzer](https://pmd.github.io/)

## License

[![...](https://app.fossa.io/api/projects/git%2Bgithub.com%2Fagustin-golmar%2FMultitier.svg?type=large)](https://app.fossa.io/projects/git%2Bgithub.com%2Fagustin-golmar%2FMultitier?ref=badge_large)

## Designer

This project has been built, designed and maintained by:

* [Agustín Golmar](https://github.com/agustin-golmar)

## Bibliography

__"Title"__. Author. _Metadata. Date_.

__"Title"__. Author. _Access Date. [[https://github.com/agustin-golmar/Multitier]](https://github.com/agustin-golmar/Multitier)_
