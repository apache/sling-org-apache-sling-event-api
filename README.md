[<img src="https://sling.apache.org/res/logos/sling.png"/>](https://sling.apache.org)

 [![Build Status](https://ci-builds.apache.org/job/Sling/job/modules/job/sling-org-apache-sling-event-api/job/master/badge/icon)](https://ci-builds.apache.org/job/Sling/job/modules/job/sling-org-apache-sling-event-api/job/master/) [![Test Status](https://img.shields.io/jenkins/tests.svg?jobUrl=https://ci-builds.apache.org/job/Sling/job/modules/job/sling-org-apache-sling-event-api/job/master/)](https://ci-builds.apache.org/job/Sling/job/modules/job/sling-org-apache-sling-event-api/job/master/test/?width=800&height=600) [![Coverage](https://sonarcloud.io/api/project_badges/measure?project=apache_sling-org-apache-sling-event-api&metric=coverage)](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-event-api) [![Sonarcloud Status](https://sonarcloud.io/api/project_badges/measure?project=apache_sling-org-apache-sling-event-api&metric=alert_status)](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-event-api) [![Maven Central](https://maven-badges.herokuapp.com/maven-central/org.apache.sling/org.apache.sling.event.api/badge.svg)](https://search.maven.org/#search%7Cga%7C1%7Cg%3A%22org.apache.sling%22%20a%3A%22org.apache.sling.event.api%22) [![JavaDocs](https://www.javadoc.io/badge/org.apache.sling/org.apache.sling.event.api.svg)](https://www.javadoc.io/doc/org.apache.sling/org.apache.sling.event.api) [![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://www.apache.org/licenses/LICENSE-2.0) [![event](https://sling.apache.org/badges/group-event.svg)](https://github.com/apache/sling-aggregator/blob/master/docs/groups/event.md)

# Apache Sling Event API

This module is part of the [Apache Sling](https://sling.apache.org) project.

For user documentation see https://sling.apache.org/documentation/bundles/apache-sling-eventing-and-job-handling.html. 
This README contains information on the API details.

Note that the default implementation has been spun-off into a separate bundle: sling.event.resource

## Bundle

Sling Event API defines the API for Jobs. It defines Job, JobManager and Queue, as well as consumer Apis for a 
JobConsumer. There are ancillary APIs to support the work of these core interfaces. The core APIs are exported from 
org.apache.sling.event.jobs with the consumers exported from org.apache.sling.event.jobs.consumer.
