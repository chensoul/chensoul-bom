# chensoul-bom

[![Build Status](https://github.com/chensoul/chensoul-bom/actions/workflows/maven-build.yml/badge.svg)](https://github.com/chensoul/chensoul-bom/workflows/maven-build.yml)
[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)
[![Maven Central][maven-image]][maven-url]

ChenSoul BOM and server-side library

This is the Bill of Materials and server-side library:

- chensoul-dependencies
- chensoul-framework


## Prerequisites

- Jdk 21+
- Maven 3.2.5


## How to?

```bash
# Clone the repository
$ git clone https://github.com/chensoul/chensoul-bom.git
cd chensoul-bom

./mvnw install -Dgpg.skip=true
```

## Sonar Analysis Result

[![sonar-quality-gate][sonar-quality-gate]][sonar-url] [![sonar-coverage][sonar-coverage]][sonar-url] [![sonar-bugs][sonar-bugs]][sonar-url] [![sonar-vulnerabilities][sonar-vulnerabilities]][sonar-url]

## References

- [https://github.com/jhipster/jhipster-bom](https://github.com/jhipster/jhipster-bom)


[maven-image]: https://maven-badges.herokuapp.com/maven-central/com.chensoul/chensoul-bom/badge.svg
[maven-url]: https://maven-badges.herokuapp.com/maven-central/com.chensoul/chensoul-bom

[sonar-url]: https://sonarcloud.io/dashboard?id=chensoul-framework
[sonar-quality-gate]: https://sonarcloud.io/api/project_badges/measure?project=chensoul-framework&metric=alert_status
[sonar-coverage]: https://sonarcloud.io/api/project_badges/measure?project=chensoul-framework&metric=coverage
[sonar-bugs]: https://sonarcloud.io/api/project_badges/measure?project=chensoul-framework&metric=bugs
[sonar-vulnerabilities]: https://sonarcloud.io/api/project_badges/measure?project=chensoul-framework&metric=vulnerabilities