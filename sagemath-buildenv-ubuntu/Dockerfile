FROM ubuntu:wily

MAINTAINER Matthias Koeppe <mkoeppe@math.ucdavis.edu>

RUN    apt-get update -qq \
    && apt-get install -y wget build-essential gfortran automake m4 dpkg-dev sudo python libssl-dev git texlive-latex-recommended

RUN    adduser --quiet --shell /bin/bash --gecos "Sage user,101,," --disabled-password sage \
    && chown -R sage:sage /home/sage/

