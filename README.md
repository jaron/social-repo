# My Social Repo

This is a local repository for libraries I use but that aren't included in the Maven Central repository, it currently consists of:

* Parse v1.4.1 (https://parse.com/downloads/android/Parse/latest)
* Facebook Android SDK v3.6.0 (https://developers.facebook.com/docs/android)

To add files to the repository, use the following command and then commit the changes:

    mvn deploy:deploy-file -Dfile=[file to deploy] -DgroupId=[group] -DartifactId=[artifact] -Dversion=[x.x.x] -Dpackaging=[type] -Durl=file:releases
