FROM alpine:3.6

ADD tmp/_output/bin/openstack-operator /usr/local/bin/openstack-operator

RUN adduser -D openstack-operator
USER openstack-operator
