FROM rocker/tidyverse:4.3.3

LABEL author="louisfaure"

RUN apt-get update
RUN apt-get install -y git wget unzip libxt-dev
RUN apt-get install -y libbz2-dev
RUN apt-get install -y liblzma-dev
RUN apt-get install -y libglpk40
RUN apt-get install -y libhdf5-dev

RUN echo '.libPaths(c("/user-library", .libPaths()))' >> /usr/local/lib/R/etc/Rprofile.site

USER root
