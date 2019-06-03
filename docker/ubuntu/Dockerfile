FROM ubuntu:latest

MAINTAINER Alex Beis <alexbeis09@gmail.com>

ENV DEBIAN_FRONTEND=noninteractive

RUN apt-get update && apt-get install -y \
	sudo \
	git \
	bzip2 \
	cron \
	wget \
	nano \
	vim \
	pv \
	iputils-ping 

RUN apt-get install -y \
	python3 \
	python-dev \ 
	ipython \ 
	python-numpy \ 
	python-matplotlib \
	python-scipy \ 
	cython