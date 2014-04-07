# My Social Repo

This is a local repository for libraries I use but that aren't included in the Maven Central repository, it currently consists of:

* Parse v1.4.2 (https://parse.com/downloads/android/Parse/latest)
* Facebook Android SDK v3.8.0 (https://developers.facebook.com/docs/android)
* Mobile-Parse-API v0.0.1 (https://code.google.com/p/mobile-parse-api/)
* Google Play Services v15.0.0 (4.2.42) (http://developer.android.com/google/play-services/index.html)

To add files to the repository, use the following command and then commit the changes:

    mvn deploy:deploy-file -Dfile=[file to deploy] -DgroupId=[group] -DartifactId=[artifact] -Dversion=[x.x.x] -Dpackaging=[type] -Durl=file:releases
