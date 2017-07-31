# Overview

The mvn-java-parent project is a maven parent project to extend for specific java projects.

## Key features:

1. Provides several plugins in the pluginManagement section that are useful for java projects.
2. Provides several dependencies in the dependencyManagement section that are useful for java projects.
3. Provides several profiles for signing, deploying, delombok and update license header.

## License

The source code comes under the liberal Apache License V2.0, making mvn-java-parent great for all types of java applications.

# Build status

[![Build Status](https://travis-ci.org/lightblueseas/mvn-java-parent.svg?branch=master)](https://travis-ci.org/lightblueseas/mvn-java-parent)

## Maven Central

[![Maven Central](https://maven-badges.herokuapp.com/maven-central/de.alpharogroup/mvn-java-parent/badge.svg)](https://maven-badges.herokuapp.com/maven-central/de.alpharogroup/mvn-java-parent)

## How to use it

Add as parent project in the `pom.xml` file:
```xml
	<parent>
		<groupId>de.alpharogroup</groupId>
		<artifactId>mvn-java-parent</artifactId>
		<version>2.27.0</version>
		<relativePath></relativePath>
	</parent>	
```

## Open Issues
[![Open Issues](https://img.shields.io/github/issues/lightblueseas/mvn-java-parent.svg?style=flat)](https://github.com/lightblueseas/mvn-java-parent/issues) 

## Want to Help and improve it? ###

The source code for mvn-java-parent are on GitHub. Please feel free to fork and send pull requests!

Create your own fork of [lightblueseas/mvn-java-parent/fork](https://github.com/lightblueseas/mvn-java-parent/fork)

To share your changes, [submit a pull request](https://github.com/lightblueseas/mvn-java-parent/pull/new/develop).

## Contacting the Developers

Do not hesitate to contact the mvn-java-parent developers with your questions, concerns, comments, bug reports, or feature requests.
- Feature requests, questions and bug reports can be reported at the [issues page](https://github.com/lightblueseas/mvn-java-parent/issues).

## Note

No animals were harmed in the making of this library.

# Donate

If you like this library, please consider a donation through 
<a href="https://flattr.com/submit/auto?fid=r7vp62&url=https%3A%2F%2Fgithub.com%2Flightblueseas%2Fmvn-java-parent" target="_blank">
<img src="http://button.flattr.com/flattr-badge-large.png" alt="Flattr this" title="Flattr this" border="0">
</a>
