# mod_cfml
Mod_cfml is a community-driven suite of programs that automatically configures Tomcat hosts to match hosts created in Apache or IIS. 

Mod_cfml removes the need to configure web sites twice - once in your web server and again in Tomcat - and performs this task automatically for you.

### Lucee Fork as the old repo is abandoned

Branches

- *master** is v2, with jakarta support, for Tomcat 10+
- **v1-javax** is v1, supporting javax servlets, Tomcat 9 and earlier

Builds

[![Java CI v1](https://github.com/lucee/mod_cfml/actions/workflows/ci.yml/badge.svg?branch=v1-javax)](https://github.com/lucee/mod_cfml/actions/workflows/ci.yml)
[![Java CI v2](https://github.com/lucee/mod_cfml/actions/workflows/ci.yml/badge.svg)](https://github.com/lucee/mod_cfml/actions/workflows/ci.yml)

### Support

As with all Lucee projects, issue tracking is all done in our jira, not per repo.

Please post to the [developer forum](https://dev.lucee.org/) support, before creating tickets in jira.

Issues: https://luceeserver.atlassian.net/issues/?jql=labels%20%3D%20%22modcfml%22

### Official Site

Installation and Configuration documentation can be found on the mod_cfml site here:

[http://viviotech.github.io/mod_cfml/](http://viviotech.github.io/mod_cfml/)

Note that the previous modcfml.org site has been depreciated in favor of the GitHub site in order to better facilitate community contributions and updates.

### Compiling the Apache module
See [C/README.md](C/README.md) for instructions.
