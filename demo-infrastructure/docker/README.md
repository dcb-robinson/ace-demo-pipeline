# Docker images for build pipelines to use

Building on top of ace-minimal (see https://github.com/tdolby-at-uk-ibm-com/ace-docker/tree/master/experimental/ace-minimal for more information) to create a builder image that contains build-time code that should not be pushed into the final application.

- ace-minimal-build is used for running the Tekton pipeline for the demo application build. Normally built using the ace-minimal-build-image-build-and-push task in the "tekton" directory in this repo, as that job will build and push in the cloud, but this image can be built locally if desired.
