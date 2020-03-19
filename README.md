# HEDIS (Healthcare Effectiveness Data and Information Set)

HEDIS® Implementation Guide

This project provides the source for the HEDIS® Implementation Guide.

Commits to this repository will automatically trigger a new build of the IG, which will then be published to the following location:

[http://build.fhir.org/ig/cqframework/hedis-ig-r4](http://build.fhir.org/ig/cqframework/hedis-ig-r4)

Build log is available here:
[http://ig-build.fhir.org.s3-website-us-east-1.amazonaws.com/logs/cqframework/hedis-ig-r4](http://ig-build.fhir.org.s3-website-us-east-1.amazonaws.com/logs/cqframework/hedis-ig-r4)

Full debugging information is available here:
[http://build.fhir.org/ig/cqframework/hedis-ig-r4/debug.tgz](http://build.fhir.org/ig/cqframework/hedis-ig-r4/debug.tgz)

## Local Build

The HL7 IG Publisher is committed to this repository to make building as easy as possible. To build locally, clone the repository and run the following scripts:

    MAC
        1. _updatePublisher.sh
        2. _genonce.sh

    Windows
        1. _updatePublisher.bat
        2. _genonce.bat

## Dependencies

Before the instructions in the above "Local Build" section will work, you
need to install several primary dependencies.

### Java

Go to [http://www.oracle.com/technetwork/java/javase/downloads/](
http://www.oracle.com/technetwork/java/javase/downloads/) and download the
latest (version 8 or higher) JDK for your platform, and install it.

### Ruby

Jekyll requires Ruby version 2.1 or greater.  Depending on your operating
system, you may already have Ruby bundled with it.  Otherwise, or if you
need a newer version, go to [https://www.ruby-lang.org/en/downloads/](
https://www.ruby-lang.org/en/downloads/) for directions.

### Jekyll

Go to [https://jekyllrb.com](https://jekyllrb.com) and follow the
instructions there, for example `gem install jekyll bundler`.  The end
result of this should be that thebinary "jekyll" is now in your path.
