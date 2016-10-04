FROM jenkins
USER root
RUN apt-get install python2.7
RUN curl -O https://bootstrap.pypa.io/get-pip.py
RUN python get-pip.py
RUN pip install awscli
USER jenkins