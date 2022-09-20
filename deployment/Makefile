VERSION := screw-classification-v0.0.1
IMAGE_NAME_BASE=tensorflow2-prepackaged
IMAGE_BASE=infuseaidev/${IMAGE_NAME_BASE}

build:
	docker build . -t ${IMAGE_BASE}:${VERSION}

push:
	docker push ${IMAGE_BASE}:${VERSION}
