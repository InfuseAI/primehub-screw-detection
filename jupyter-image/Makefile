VERSION := tensorflow-notebook-v2-5-0-ca154071-screw
IMAGE_NAME_BASE=docker-stacks
IMAGE_BASE=infuseaidev/${IMAGE_NAME_BASE}

build:
	docker build . -t ${IMAGE_BASE}:${VERSION}

push:
	docker push ${IMAGE_BASE}:${VERSION}

save:
	docker save ${IMAGE_BASE}:${VERSION} | gzip > ${VERSION}.tgz

load:
	gunzip -c ${VERSION}.tgz | docker load
