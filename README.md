This repo is meant to serve as a sample app to show the bug in Groovy Android gradle plugin which produces build failure on the first build and
works after wards. Steps to reproduce:

1) Clone the repo and run ./gradlew clean build , from the project root directory. The build fails.
2) Run the same command again and the build is successful.



