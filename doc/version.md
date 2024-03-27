# Version Scheme

The version is composed according SEMVER (https://semver.org).

![Version](version.svg)

## Pre-Releases

The **pre-release** is composed by tokens separated by dot (`.`):

- **Release**
- **Readiness** (last token) according Simplest Technology Readiness Level (https://dhbmarcos.gitlab.io/strl)

![Version Pre-Release](version-pre-release.svg)

## Build

Product build instant code.

![Version Build](version-build.svg)

Specification of build value:
- First five digits:
    - digits 1 and 2: year of build;
    - digits 3 and 4: week number of build;
    - digit  5:       day of week of build;
- separator (`.`);
- Second from start of day;
