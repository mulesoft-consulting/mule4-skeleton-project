# mule4-skeleton-project
The skeleton-project is an example application that can be used as a template for building a Mule application.

## Uses

The project contains examples using:

* The minimal-logging connector, 
* The secure property connector (formally called the secure-property-placeholder),
* Maven deployment using the mule-maven-plugin descriptor.

## Purpose
This project is an example only. It contains a scheduling component to periodically (every ten minutes), use the minimal-logging operations to generate a new transaction id, display three (enter, warning and exit) log messages.

