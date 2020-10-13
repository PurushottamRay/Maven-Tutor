A Build Lifecycle is Made Up of Phases
For example, the default lifecycle comprises of the following phases (for a complete list of the lifecycle phases, refer to the Lifecycle Reference):

<b>validate</b> - validate the project is correct and all necessary information is available

<b>compile</b>  - compile the source code of the project

<b>test</b>  - test the compiled source code using a suitable unit testing framework. These tests should not require the code be packaged or deployed

<b>package</b>  - take the compiled code and package it in its distributable format, such as a JAR.

<b>verify</b>  - run any checks on results of integration tests to ensure quality criteria are met

<b>install</b>  - install the package into the local repository, for use as a dependency in other projects locally

<b>deploy</b>  - done in the build environment, copies the final package to the remote repository for sharing with other developers and projects.

<I>In this, project different kind of maven configurations setting has been added in pom.xml to give a glipse of different need for future reference</I>
