# Red Hat JBoss Fuse: Tooling Tutorials

This zip file contains two folders:

## blueprintContexts Folder
This folder contains two prefabricated `blueprint#.xml` files (5 and 6) that enable you to run through individual tutorials 5, 6, 7, 8 and 9, without having to complete any preceding tutorial, except tutorial 2, _To Create a New Route_, which is the only tutorial you must complete to be able to work through the remaining tutorials.

* Use `blueprint5.xml`, which is the routing context resulting from completing tutorial 4, to complete tutorial 5, _To Add Another Route to the CBR Routing Context_.
* Use `blueprint6.xml` to complete any of the tutorials 6 through 9:
_To  Debug a Routing Context_, 
_To Trace a Message Through a Route_,
_To Test a Route with JUnit_, and _To Publish a Fuse Project to Red Hat JBoss Fuse_.

To use either of the prefabricated `blueprint#.xml` files:

1. Unzip this file in a convenient location external to the CBRroute project’s workspace.
2. Delete or rename the `blueprint.xml` file from the `CBRroute/src/main/resources/OSGI-INF/blueprint/` folder. 
3. Copy the `blueprint#.xml` file corresponding to the tutorial that you want to complete into the vacated `CBRroute/src/main/resources/OSGI-INF/blueprint/` folder.
4. Rename the `blueprint#.xml` file to `blueprint.xml`.
5. In the Red Hat JBoss Fuse: Tooling Tutorials guide, follow the instructions for completing the target tutorial.

## Messages folder
This folder contains six prefabricated `message#.xml` files (1 through 6) that jumpstart your working through any of the eight tutorials in the Red Hat JBoss Fuse: Tooling Tutorials guide. If you are working through tutorial 1, _To Create a New Route_, you need not install `message1.xml`.

Copy the prefabricated `message#.xml` files into your CBRroute project’s `src/data/` folder.
