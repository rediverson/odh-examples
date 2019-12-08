FROM quay.io/opendatahub/spark-cluster-image:spark22python36

USER root

RUN /opt/rh/rh-python36/root/usr/bin/pip3 install sklearn
RUN /opt/rh/rh-python36/root/usr/bin/pip3 install nltk
RUN python -c "import nltk; nltk.download('stopwords'); nltk.download('punkt')"
