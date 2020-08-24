# anchor-javadoc

This is part of the source-distribution for the [Anchor Image Analysis](http://www.anchoranalysis.org) software.

It creates Javadocs for different Java repositories related to Anchor.

## Usage

**Precondition:** this repository (`anchor-javadoc`) exists in the same top-level directory in which the other anchor repositories are cloned i.e. `anchor-javadoc` and `anchor` and `anchor-plugins` etc. are adjacent.

In the relevant directory, execute:

```
mvn site javadoc:aggregate
```

and the javadocs will be generated in `target/site/apidocs`.

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
