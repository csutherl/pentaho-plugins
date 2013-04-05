pentaho-plugins
===============

Repository to house plugins that I plan to work on for Pentaho!

In order to start development of a new plugin with the Demo as a base, just copy the Demo directory and update the code base/build.xml/plugin.xml to reflect the new plugin info.

For each of the build.xml's in the individual plugin projects, it references the compile-time-libs that are located up one directory from the project itself. If you move the project outside of the git repo directory, note that the libraries will need to go as well (or at least update the references).

Props to Slawomir Chodnicki for the code!! Find this and a few other sample SDK usages here: https://pentaho.box.com/extending-and-embedding-pdi
