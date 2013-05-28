Simple archetype to build eclipse plugin.

Example of usage:

mvn archetype:generate -DarchetypeGroupId=net.orcades.maven.archetype -DarchetypeArtifactId=eclipse-plugin-archetype -DarchetypeVersion=4.2.1 -DartifactId=org.mycommunity.eclipse.dummy -DgroupId=org.mycommunity.eclipse.dummy -Dversion=1.0.0-SNAPSHOT -Dcategory="Dummy category" -DclassPrefix=Dummy  -Dname=Dummy

Note that if "version" must be maven style, it may be specified as "SNAPSHOT" but not "qualifier". Nevertheless when set to "SNAPSHOT" the OSGi/eclipse related files will use the "qualifier". 
