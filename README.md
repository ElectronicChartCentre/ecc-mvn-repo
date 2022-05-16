ecc-mvn-repo
============

ECC Maven Repository

Install new JAR files:

mvn install:install-file  -Dfile=[the jar file] -DgroupId=[the group id] -DartifactId=[the artifact id] -Dversion=1.0 -Dpackaging=jar

The JAR file is installed to the local .m2 repository.

Copy the folder into the releases folder and commit to github.

The directory are automatically synced to https://ecc-mvn.ams3.digitaloceanspaces.com/ using Github Action
