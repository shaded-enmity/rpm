---
layout: default
title: Documentation
---
This page attempts to track the various relevant documentation that exists for RPM.

### User Documentation
* [RPM Tutorial](http://fedoranews.org/alex/tutorial/rpm/)
* [Fedora RPM Guide](http://docs.fedoraproject.org/en-US/Fedora_Draft_Documentation/0.1/html/RPM_Guide/index.html)
* In wiki:
  * [RPM Frequently asked questions (FAQ)](doc_faq.html)
  * [RPM Database Recovery](doc_db_recovery.html)
  * [RPM Query Formats](doc_query_format.html) 

### Packager Documentation
* [Creating RPMS](http://www.gurulabs.com/GURULABS-RPM-LAB/GURULABS-RPM-GUIDE-v1.0.PDF) slides from [Guru Labs](http://www.gurulabs.com/)
* [Fedora RPM Guide](http://docs.fedoraproject.org/en-US/Fedora_Draft_Documentation/0.1/html/RPM_Guide/index.html)
* In wiki:
  * [Conditional Builds (rpmbuild &#8211;&#8211;with/&#8211;&#8211;without)](doc_conditional_builds.html)
  * [Dependencies](doc_dependencies.html)
  * [More on Dependencies](doc_more_dependencies.html)
  * [Dependency Generators](doc_dependency_generators.html) (new in 4.9)
  * [Automated, VCS integrated patch application](doc_autosetup.html) (new in 4.11)
  * [Macros](doc_macros.html)
  * Embedded Lua interpreter
  * Runtime scriptlet expansion (new in 4.9)
  * Building Packages so that multiple versions of the same package can co-install 

### RPM Language Bindings Documentation
* [RPM Python](http://www.ukuug.org/events/linux2004/programme/paper-PNasrat-1/rpm-python-slides/frames.html) slideset / tutorial
* [Programming RPM with Python](http://docs.fedoraproject.org/en-US/Fedora_Draft_Documentation/0.1/html/RPM_Guide/ch-rpm-programming-python.html) from Fedora RPM Guide
* [Programming RPM with Perl](http://docs.fedoraproject.org/en-US/Fedora_Draft_Documentation/0.1/html/RPM_Guide/ch-programming-perl.html) from Fedora RPM Guide 

### Developer Documentation
* [Programming RPM with C](http://docs.fedoraproject.org/en-US/Fedora_Draft_Documentation/0.1/html/RPM_Guide/ch-programming-c.html) from Fedora RPM Guide
* RPM API:
  * RPM 4.12.0.1 API
  * RPM 4.11.1 API
  * RPM 4.10.x API
  * RPM 4.9.x API
  * RPM 4.8.0 API
  * RPM 4.7.0 API
  * RPM 4.6.0 API
  * RPM 4.4.2.2 API 
* Plugin Interface (RPM >= 4.12)
* Maintainer documentation:
 * Release Process
 * Other maintainer guidelines 

* Miscellaneous docs in rpm.org wiki:
  * How to ensure Large File Support for tools using the rpm API
  * Description of RPM internal state machines
  * Description of RPM file format 

### Books
The following books have been published regarding RPM:

* **Maximum RPM** A book written by Ed Bailey. It is available in hardback (442 pages), and has recently been re-printed by Sams in soft-cover (450 pages - ISBN: 0672311054). The hardcover edition includes a quick reference card. An on-line version of the original book is also available, and a more up to date, work in progress version can be found [here](http://www.rpm.org/max-rpm-snapshot/). 
* **Red Hat RPM** Guide A more recent book by Eric Foster-Johnson, this has recently been released under the Open Publication License and a draft close to the published version is available on-line as [Fedora RPM Guide](http://docs.fedoraproject.org/en-US/Fedora_Draft_Documentation/0.1/html/RPM_Guide/index.html). This book covers everything from basic usage to advanced tricks, package creation and API programming. Participation in updating the Guide can be done via the [Fedora Documentation Project](http://fedoraproject.org/wiki/DocsProject). Discussions about moving this content and work upstream to rpm.org can occur on [fedora-docs-list](http://www.redhat.com/mailman/listinfo/fedora-docs-list). 



