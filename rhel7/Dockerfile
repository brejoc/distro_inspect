FROM registry.access.redhat.com/ubi7/ubi

VOLUME /script
RUN curl https://bootstrap.pypa.io/get-pip.py -o get-pip.py
RUN python get-pip.py
RUN pip install distro
