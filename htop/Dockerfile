# htop in a container
#
# docker run --rm -it \
# 	--pid host \
# 	jess/htop
#
FROM alpine:latest
MAINTAINER Jessie Frazelle <jess@linux.com>

RUN apk --no-cache add \
	htop

CMD [ "htop" ]
