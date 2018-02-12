# Base Image
FROM biocontainers/biocontainers:latest

# Metadata
LABEL base.image="biocontainers:latest"
LABEL version="2"
LABEL software="AdapterRemoval"
LABEL software.version="2.2.2"
LABEL description="Searches for and removes remnant adapter sequences from High-Throughput Sequencing (HTS) data "
LABEL website="https://github.com/MikkelSchubert/adapterremoval"
LABEL documentation="https://github.com/MikkelSchubert/adapterremoval"
LABEL license="https://github.com/MikkelSchubert/adapterremoval/blob/master/LICENSE"
LABEL tags="Genomics"

# Maintainer
MAINTAINER Maxime

RUN  conda install -c maxibor adapterremoval2

WORKDIR /data/

CMD ["AdapterRemoval"]
