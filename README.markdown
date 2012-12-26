Maven Android SDK Deployer
--------------------------

Author and Project Maintainer including numerous fixes and changes:

Manfred Moser manfred@simpligility.com  at [simpligility technologies inc](http://www.simpligility.com)

The Playhaven development team uses a slightly modified maven-android-sdk-deployer project for installing exotic dependencies such as the maps library. Before using this dependency, developers should install all the add-ons via the Android SDK manager as detailed in the Android developer docs.

The `repo.url` property in `pom.xml` enables developers to push Android SDK libraries from their local machine to the central build server.