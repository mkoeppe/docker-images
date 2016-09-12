# FROM ubuntu:wily
FROM toopher/centos-i386:centos6
#FROM daald/ubuntu32

MAINTAINER Matthias Koeppe <mkoeppe@math.ucdavis.edu>

ARG SAGE_SRC_TARGET=/opt

RUN yum install -y gmp-devel gcc gcc-c++ gcc-gfortran automake autoconf libtool python openssl-devel git wget
RUN yum install -y tar texlive
RUN yum install -y texlive-latex

RUN adduser --shell /bin/bash --comment "Sage user,101,," --home-dir /home/sage --create-home sage

#USER sage
#ENV HOME /home/sage
#ENV SHELL /bin/bash
#WORKDIR /home/sage
