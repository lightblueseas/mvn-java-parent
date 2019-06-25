# Overview

<div align="center">

[![license apache2](https://img.shields.io/badge/license-apache2-blue.svg)](http://www.apache.org/licenses/LICENSE-2.0)
[![Build Status](https://travis-ci.org/lightblueseas/mvn-java-parent.svg?branch=master)](https://travis-ci.org/lightblueseas/mvn-java-parent)
[![Open Issues](https://img.shields.io/github/issues/lightblueseas/mvn-java-parent.svg?style=flat)](https://github.com/lightblueseas/mvn-java-parent/issues) 
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/de.alpharogroup/mvn-java-parent/badge.svg)](https://maven-badges.herokuapp.com/maven-central/de.alpharogroup/mvn-java-parent)
[![Donate](https://img.shields.io/badge/donate-❤-ff2244.svg)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=GVBTWLRAZ7HB8)

</div>

The mvn-java-parent project is a maven parent project that can be extended for specific java projects.

# Donations

If you like this library, please consider a donation through paypal: <a href="https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=B37J9DZF6G9ZC" target="_blank">
<img src="https://www.paypalobjects.com/en_US/GB/i/btn/btn_donateCC_LG.gif" alt="PayPal this" title="PayPal – The safer, easier way to pay online!" border="0" />
</a>

or over bitcoin or bitcoin-cash with:

1Jzso5h7U82QCNmgxxSCya1yUK7UVcSXsW

or over ether with:

0xaB6EaE10F352268B0CA672Dd6e999C86344D49D8

or over flattr: <a href="https://flattr.com/submit/auto?fid=r7vp62&url=https%3A%2F%2Fgithub.com%2Flightblueseas%2Fmvn-java-parent" target="_blank">
<img src="http://button.flattr.com/flattr-badge-large.png" alt="Flattr this" title="Flattr this" border="0">
</a>

## Note

No animals were harmed in the making of this library.

## Key features:

1. Provides several plugins in the pluginManagement section that are useful for java projects.
2. Provides several dependencies in the dependencyManagement section that are useful for java projects.
3. Provides several profiles for signing, deploying, delombok and update license header.

## License

The source code comes under the liberal Apache License V2.0, making mvn-java-parent great for all types of java applications.

## How to use it

Add as parent project in the `pom.xml` file:
```xml
	<parent>
		<groupId>de.alpharogroup</groupId>
		<artifactId>mvn-java-parent</artifactId>
		<version>6.3</version>
		<relativePath></relativePath>
	</parent>	
```

## Semantic Versioning

The versions of mvn-java-parent are maintained with the Semantic Versioning guidelines.

Release version numbers will be incremented in the following format:

`<major>.<minor>.<patch>`

For detailed information on versioning you can visit the [wiki page](https://github.com/lightblueseas/mvn-parent-projects/wiki/Semantic-Versioning).
	

## Want to Help and improve it? ###

The source code for mvn-java-parent are on GitHub. Please feel free to fork and send pull requests!

Create your own fork of [lightblueseas/mvn-java-parent/fork](https://github.com/lightblueseas/mvn-java-parent/fork)

To share your changes, [submit a pull request](https://github.com/lightblueseas/mvn-java-parent/pull/new/develop).

## Contacting the Developers

Do not hesitate to contact the mvn-java-parent developers with your questions, concerns, comments, bug reports, or feature requests.
- Feature requests, questions and bug reports can be reported at the [issues page](https://github.com/lightblueseas/mvn-java-parent/issues).

## Credits

|**Travis CI**|
|     :---:      |
|[![Travis CI](https://travis-ci.com/images/logos/TravisCI-Full-Color.png)](https://coveralls.io/github/lightblueseas/mvn-java-parent?branch=master)|
|Special thanks to [Travis CI](https://travis-ci.org) for providing a free continuous integration service for open source projects|
|     <img width=1000/>     |

|**Nexus Sonatype repositories**|
|     :---:      |
|[![sonatype repository](https://img.shields.io/nexus/r/https/oss.sonatype.org/de.alpharogroup/mvn-java-parent.svg?style=for-the-badge)](https://oss.sonatype.org/index.html#nexus-search;gav~de.alpharogroup~mvn-java-parent~~~)|
|Special thanks to [sonatype repository](https://www.sonatype.com) for providing a free maven repository service for open source projects|
|     <img width=1000/>     |


