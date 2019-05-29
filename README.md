Template
---------

Template is an Eclipse RCP project that creates an empty workspace application.

To refactor this to a project identity of your choice you will need to edit the following files:

###pom.xml

Update the groupId and artifactId

###releng/pom.xml

Update the groupId and artifactId

Change build configurations elsewhere in the POM (t.b.c.)...

###releng/uk.org.whitecottage.template.target/pom.xml

Update the parent groupId and artifactId

###releng/uk.org.whitecottage.tamplate.target/uk.org.whitecottage.template.target.target

Change the target name (in the Definition tab) and rename - the file name should still end in ".target.target"

###releng/uk.org.whitecottage*

Rename directories

