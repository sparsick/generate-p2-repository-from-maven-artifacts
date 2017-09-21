generate-p2-repository-from-maven-artifacts
===========================================

This Maven POM project demonstrates how to generate a P2 repository (with features and non-feature-based plugins) from given Maven artifacts.
It is used Maven Plugins and Maven Tycho Plugins (in version 1.0.0):
- [p2-maven-plugin](https://github.com/reficio/p2-maven-plugin): For creating the P2 repository from given Maven artifacts.
- [tycho-p2-repository-plugin](https://eclipse.org/tycho/sitedocs/tycho-p2/tycho-p2-repository-plugin/plugin-info.html): Pack the P2 repostory as a zip file.
- [build-helper-maven-plugin](http://www.mojohaus.org/build-helper-maven-plugin/index.html): Attach the zip file, so that Maven Deploy Plugin can deploy it to a Maven Repository Manager.
