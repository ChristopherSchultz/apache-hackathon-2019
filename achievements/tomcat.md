# Apache Tomcat

Prior to the Hackathon the Tomcat commiters created a [wiki page](https://cwiki.apache.org/confluence/display/TOMCAT/EU+FOSSA+May+2019) with topics to work on and discuss.

## GraalVM
Some of the people at the Tomcat table got interested in getting Tomcat to run on GraalVM. 
Because we already knew that Tomcat would not run with the latest published version of GraalVM, we started with compiling the master branch of GraalVM from Github. There is a commit in master just done a few days before the event that should fix some issues that appeared before.

Compiling GraalVM from source turned out to be a little bit tricky, because it did not compile with a regular version of the Java VM but required a special JVM.

## Community and Builds
The team instructed a few attendees on how to build Apache Tomcat from source either from checking-out the code from git or from a release package. Also gave instructions for forking the project on GitHub for future hacking and pull-requests.

## Fixes

One enhancement request was completed fixed.

One new bug was filed.
