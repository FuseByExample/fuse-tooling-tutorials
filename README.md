# Red Hat Fuse Tooling Tutorials

This zip file contains two folders:

## Messages folder
This folder contains six `message#.xml` files (1 through 6) for the Red Hat Fuse Tooling Tutorials. 

As described in the _Setting up your environment_ tutorial, copy these `message#.xml` files into your sample project’s `src/data/` folder.

## blueprintContexts Folder
This folder contains three files: `blueprint1.xml`, `blueprint2.xml`, and `blueprint3.xml`.  After you complete the _Setting up your environment_ tutorial, which is the only tutorial you must complete to be able to work through the remaining tutorials, you can use these files to complete the following tutorials:

* `blueprint1.xml`is the routing context resulting from completing the _Defining a Route_ tutorial. You can use it as the starting point for the following tutorials:
 _Running a Route_
 _Adding a Content-Based Router_

* `blueprint2.xml`is the routing context resulting from completing the _Adding a content-based router_ tutorial. You can use it as the starting point for the  _Adding another route to the routing context_ tutorial.

* Use `blueprint3.xml` to complete any of the following tutorials:
_Debugging a routing context_, 
_Tracing a message through a route_,
_Testing a route with JUnit_, 
and _Publishing a Fuse project to Red Hat JBoss Fuse_.

To use any of these `blueprint#.xml` files:

1. Unzip this file to a convenient location external to your Developer Studio workspace.
2. Complete the _Setting up your environment_ tutorial.
2. Delete or rename the `blueprint.xml` file from the ZooOrderApp project's `/src/main/resources/OSGI-INF/blueprint/` folder. 
3. Copy the `blueprint#.xml` file corresponding to the tutorial that you want to complete into the vacated `CBRroute/src/main/resources/OSGI-INF/blueprint/` folder.
4. Rename the `blueprint#.xml` file to `blueprint.xml`.
5. Follow the instructions for completing the tutorial.


