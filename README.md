# mule4-skeleton-project
The skeleton-project is an example application that can be used as a template for building a Mule application.

Note, the scope features of minimal-logging are not displayed correctly by Studio 7.1 or 7.2. Support for displaying SDK connector scopes is expected in Studio 7.3.

## Uses

The project contains examples using:

* The minimal-logging connector, 
* The secure property connector (formally called the secure-property-placeholder),
* Maven deployment using the mule-maven-plugin descriptor.

## Purpose
This project is an example only. It contains a scheduling component to periodically (every ten minutes), use the minimal-logging operations to generate a new transaction id, display three (enter, warning and exit) log messages.


## Runtime properties

The properties mule.env and mule.key need to be set in the Mule runtime in order for the property configurations to be located. 
For Studio, add the following VM command line values when running the API:

 -Dmule.env=local -Dmule.key=Mulesoft12345678