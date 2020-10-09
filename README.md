[![Gitter](https://img.shields.io/gitter/room/nwjs/nw.js.svg?style=flat)](https://gitter.im/FasterXML/jackson-databind)  [![Open Source](https://badges.frapsoft.com/os/v1/open-source.svg?v=103)](https://opensource.org/)

# Hacktoberfest2020

Central repository for FasterXML activities related to Hacktoberfest 2020 by DigitalOcean (https://hacktoberfest.digitalocean.com/).

## Contributing

### General

All FasterXML projects are participating in  [Hacktoberfest 2020](https://hacktoberfest.digitalocean.com/), so contributions are eligible for the main prizes.

### Indeed + Hacktoberfest

In addition to the main event, [Indeed.com](https://indeed.com) is sponsoring additional activities --
see [Indeed Hacktoberfest 2020](https://engineering.indeedblog.com/indeed-hacktoberfest-2020/) for details -- that can get you additional swag: Jackson is one of OSS projects eligible and supported
(being heavily used by Indeed, see [Jackson overview](https://engineering.indeedblog.com/blog/2020/09/jackson-more-than-json-for-java/) at Indeed Engineering Blog).

The only additional requirement is that issues to solve / PRs MUST be labeled with "hacktoberfest"
(if such label is missing you may ask maintainers to check if issue should have it).

<br>

### Hacktoberfest Open Office Hours
Join us for open office hours to talk about issues, propose ideas, help review code, and more.

| Date         | Time           | Register  |
| ------------- |:-------------:| -----:|
| Friday, October 9 | 10AM-11AM PT | (completed) |
| Friday, October 16 | 10AM-11AM PT | [register](https://organize.mlh.io/participants/events/5014-virtual-fasterxml-jackson-office-hours) |
| Friday, October 23 | 10AM-11AM PT |[register](https://organize.mlh.io/participants/events/5013-virtual-fasterxml-jackson-office-hours) |
| Friday, October 30 | 10AM-11AM PT |[register](https://organize.mlh.io/participants/events/5010-virtual-fasterxml-jackson-office-hours) |
<br>

### Contribution Guidelines

Details of making contributions can be found from main
[Contributing.MD](https://github.com/FasterXML/jackson/blob/master/CONTRIBUTING.md).

### Where to add Design (gfx, styles) files?

To allow for easier merging of content contributions, there is folder
[design/](design/) which is intended as the merging target for contributions:
the idea is that you create a sub-folder named same as your Github id, and then
you can add all content you want there without risk of merge conflict.

For example, Jackson author would create folder --

    design/cowtowncoder

and optionally sub-folders beyond that, if there are multiple files -- to contain
his submissions, as part of Pull Request.

This space is not meant as the ultimate target but simply as a simple mechanism to
share content outside of Pull Requests, so that merging is easy and merged components
can be more easily accessed by community members (for purposes of feedback, and
possibly voting for ones they prefer, if there are multiple submissions for same
requests).

-----

## Good First Issues

[Issues for New Contributors](https://github.com/FasterXML/jackson/wiki/Issues-For-New-Contributors)
page is being updated (more) actively during Hacktoberfest and is a good place to check for
issue over Jackson repositories.

## Projects specifically looking for help

Although all repositories under [FasterXML](https://github.com/FasterXML) org in Github are happy to receive contributions (and will qualify for possible prizes and rewards), there are ones that
we recommend in particular. Here are some

### Jackson Kotlin module

Kotlin module (https://github.com/FasterXML/jackson-module-kotlin) adds support for Kotlin-specific
data types, as well as some convenience methods to simplify usage to be more "Kotlin style".
Due to Kotlin's rapid development there are sometimes new things to support.

See [Issue Tracker](https://github.com/FasterXML/jackson-module-kotlin/issues/) for specific issues

### Jackson Scala module

Scala module (https://github.com/FasterXML/jackson-module-scala) adds support for Scala-specific
data types (such as collection types that do not extend JDK Collections).
Main issues are related to making sure that module takes advantage of the latest `jackson-databind`
features.

See [Issue Tracker](https://github.com/FasterXML/jackson-module-scala/issues/) for specific issues

### Java 8 date/time datatype module

[Issue Tracker](https://github.com/FasterXML/jackson-modules-java8/issues) (note: there are other
Java 8 issues too, but most are Date/Time releated)

### Joda date/time datatype module

[Issue Tracker](https://github.com/FasterXML/jackson-datatype-joda/issues/)

### Hibernate datatype module

[Hibernate module](https://github.com/FasterXML/jackson-datatype-hibernate/) does currently
not have a maintainer and is lagging behind other data type modules, so it would
benefit from someone "adopting" it. Jackson team would be happy to find a new owner for
it -- but all contributions are welcome.
Specific challenges include compatiblity across Hibernate versions (there are actually 3
different modules currently, for Hibernate versions 3.x, 4.x and 5.x+):

[Issue Tracker](https://github.com/FasterXML/jackson-datatype-hibernate/issues)

## Bigger / Future Ideas

There is [Jackson Future Ideas](https://github.com/FasterXML/jackson-future-ideas/)
repository which contains ideas that do not fit into existing projects.

[Issue Tracker](https://github.com/FasterXML/jackson-future-ideas/issues)

-----

## Support

### Forums

There are a few channels for getting support with Hacktoberfest contributions:

* Gitter "jackson-databind" chat: https://gitter.im/FasterXML/jackson-databind
* Jackson mailing list ("jackson-users"): https://groups.google.com/forum/#!forum/jackson-user

### Documentation, Further reading

* Hacktoberfest2020 Jackson blog posts
    * [Jackson: more than JSON for Java](https://engineering.indeedblog.com/blog/2020/09/jackson-more-than-json-for-java/)

