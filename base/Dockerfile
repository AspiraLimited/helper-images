# SPDX-License-Identifier: GPL-3.0-or-later
# author  : paulfantom

# This image is used to speed up build process for official netdata images.

ARG ARCH=amd64-v3.9
FROM multiarch/alpine:${ARCH} as builder

# Install some prerequisites
RUN apk --no-cache add curl \
                       fping \
                       jq \
                       libuuid \
                       lm_sensors \
                       netcat-openbsd \
                       nodejs \
                       py-mysqldb \
                       py-psycopg2 \
                       py-yaml \
                       python
