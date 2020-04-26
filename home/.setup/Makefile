SHELL=/usr/bin/bash

.PHONY: localhost
localhost:
	. bash/system && \
	ansible-playbook \
	-e HOST_OS=${HOST_OS} -e HOST_VER=${HOST_VER} \
	--become --become-method=sudo \
	localhost.yml
