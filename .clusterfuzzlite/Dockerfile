FROM gcr.io/oss-fuzz-base/base-builder-go@sha256:2a2452777b388c15e6c6078d523acbd4b3653799ea42a4c385c19580da0fff13
COPY . $SRC/atlantis
COPY .clusterfuzzlite/build.sh $SRC/build.sh
WORKDIR $SRC/atlantis
