# begin the image: FROM, ARG and MAINTAINER
FROM debian
LABEL maintainer=@joshuacook
ARG DEBIAN_FRONTEND=noninteractive

# provision the thin operating system for the miniconda3 image
RUN apt-get update --fix-missing && \
    apt-get install -y \
    wget bzip2 ca-certificates \
    libglib2.0-0 libxext6 libsm6 libxrender1
