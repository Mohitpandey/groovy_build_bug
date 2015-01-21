This repo is meant to serve as an example to illustrate the bug in Groovy Android gradle plugin which produces build failure on the first build and works after wards. [ https://github.com/groovy/groovy-android-gradle-plugin/issues/34 ]

Steps to reproduce:

1) Clone the repo and run ./gradlew clean build , from the project root directory. The build fails.

2) Run the same command again and the build is successful.

3) Delete the build directory under app directory ( rm -rf app/build,  from project root )

4) Run the ./gradlew clean build and see it fail again.



