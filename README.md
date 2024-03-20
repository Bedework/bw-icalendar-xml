## bw-icalendar-xml [![Build Status](https://travis-ci.org/Bedework/bw-util.svg)](https://travis-ci.org/Bedework/bw-util)

This project provides an XML Icalendar schema for the RFC 6321 specification.

### Requirements

1. JDK 17
2. Maven 3

### Building Locally

> mvn clean install

### Releasing

Releases of this fork are published to Maven Central via Sonatype.

To create a release, you must have:

1. Permissions to publish to the `org.bedework` groupId.
2. `gpg` installed with a published key (release artifacts are signed).

To perform a new release use the release script:

> ./bedework/build/quickstart/linux/util-scripts/release.sh <module-name> "<release-version>" "<new-version>-SNAPSHOT"

When prompted, indicate all updates are committed 

For full details, see [Sonatype's documentation for using Maven to publish releases](http://central.sonatype.org/pages/apache-maven.html).


### Release Notes
#### 5.1.0
* Moved out of bw-xml
