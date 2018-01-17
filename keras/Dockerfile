FROM nvidia/cuda:8.0-cudnn6-runtime
MAINTAINER Borodin Gregory <grihabor@mail.ru>

RUN apt update \
 && apt install -y \
	python3 \
	python3-tk \
	python3-pip

RUN pip3 install --upgrade pip
RUN pip3 install --no-cache-dir numpy
RUN pip3 install --no-cache-dir scipy
RUN pip3 install --no-cache-dir scikit-learn
RUN pip3 install --no-cache-dir scikit-image
RUN pip3 install --no-cache-dir pandas
RUN pip3 install --no-cache-dir tensorflow-gpu
RUN pip3 install --no-cache-dir keras
RUN pip3 install --no-cache-dir h5py
