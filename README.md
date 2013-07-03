generate-p2-repository-from-maven-artifacts
===========================================

This Maven POM project demonstrates how to generate a categorized P2 repository from given Maven artifacts.
It is used Maven Plugins and Maven Tycho Plugins (in version 0.18.0).
The procedure is the following one.
1. Define the Maven artifacts, that should be add to the P2 reposiory, in the    <dependencies>     section.
2. Copy these defined artifacts to the source location of the Feature and Bundle Publisher.
3. Generate P2 repository with the Feature and Bundle Publisher.
4. Add categories to the P2 metadata, so that you can see your P2 repository in Eclipse Target Platform Wizard.
5. Zip P2 repository.
6. Attach zipped P2 repository to be installed and deployed in the Maven repository during the deploy phase.

#### Helping Links
[First hint, how to do it.](https://docs.sonatype.org/display/TYCHO/Tycho-extras+-+FeaturesAndBundlesPublisher)
[Creating a P2 repository with Eclipse standard tools](http://maksim.sorokin.dk/it/2010/11/26/creating-a-p2-repository-from-features-and-plugins/)
[Tycho's P2 Extra Plugin] (http://www.eclipse.org/tycho/sitedocs-extras/tycho-p2-extras-plugin/plugin-info.html)


