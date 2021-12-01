# cloud-native-release-workflow
![alt text](https://salesforcegraells.files.wordpress.com/2017/10/gitflow-workflow.jpg)

Builds on "develop" branch produce container images tagged with a "-SNAPSHOT" suffix + "latest" tag

Periodic builds on "develop" branch (Nightly builds) produce container images tagged with a "-SNAPSHOT" suffix + "latest" tag

Builds on "release" branch produce container images tagged with a "-RC" suffix + "latest" tag

Builds on TAGS  produce Final container images with final version tags + "latest" tag