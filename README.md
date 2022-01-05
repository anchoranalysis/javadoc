# javadoc

This is part of the source-distribution for the [Anchor Image Analysis](http://www.anchoranalysis.org) software.

It creates combined Javadoc, aggregated across Java repositories related to Anchor.

Please see the relevant section of the [Developer Guide](https://www.anchoranalysis.org/developer_guide_repositories_javadoc.html) for updating and usage instructions.

## Adding a new module

To add a new Java module to the automatically-generated documentation, please update the following:

* The `pom.xml` in the repository root, adding the modules to the respective variables. Note the trailing semi-colon.
* The `anchor-all/pom.xml` adding a `<module>` entry for the respective modules (unless GUI-related).
* The `OTHER_DIRECTORY/pom.xml` adding a `<module>` entry for the respective modules, with `OTHER_DIRECTORY` depending on where the project module belongs.

## What is Anchor?

Anchor is a platform for image analysis, developed by [Owen Feehan](http://www.owenfeehan.com) at:

* ETH Zurich
* University of Zurich
* Hoffmann la Roche
* ongoing as a open-source personal/community project

## Documentation

Please consider:

* the [user guide](https://www.anchoranalysis.org/user_guide.html)
* the [developer guide](https://www.anchoranalysis.org/developer_guide.html), especially [anchor-assembly](https://www.anchoranalysis.org/developer_guide_repositories_anchor_assembly.html) for an overview of all modules in this repository.

Before reading the source code, please:

* Understand Maven and [multi-module projects](https://www.anchoranalysis.org/developer_guide_environment_maven.html).
* Consider Anchor's [architecture](https://www.anchoranalysis.org/developer_guide_architecture_overview.html).
* Consider the role of each [module](https://www.anchoranalysis.org/developer_guide_repositories_anchor.html) in the repository.
