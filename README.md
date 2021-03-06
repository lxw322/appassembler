# Appassembler Maven Plugin

This project contains the [Appassembler Maven Plugin project](http://www.mojohaus.org/appassembler/).

[![The MIT License](https://img.shields.io/github/license/mojohaus/appassembler.svg?label=License)](https://opensource.org/licenses/MIT)
[![Maven Central](https://img.shields.io/maven-central/v/org.codehaus.mojo/appassembler-maven-plugin.svg?label=Maven%20Central)](http://search.maven.org/#search%7Cgav%7C1%7Cg%3A%22org.codehaus.mojo%22%20AND%20a%3A%22appassembler-maven-plugin%22)
[![Build Status](https://travis-ci.org/mojohaus/appassembler.svg?branch=master)](https://travis-ci.org/mojohaus/appassembler)

## Overview

The Application Assembler Plugin is a Maven plugin for generating scripts for
starting java applications. All dependencies and the artifact of the project
itself are placed in a generated Maven repository in a defined assemble
directory. All artifacts (dependencies + the artifact from the project) are
added to the classpath in the generated bin scripts.

Supported platforms:

 * Unix-variants
 * Windows NT (Windows 9x is NOT supported)
 * Java Service Wrapper (JSW)

