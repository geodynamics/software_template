FROM ubuntu

LABEL maintainer <rene.gassmoeller@mailbox.org>

RUN apt update && \
    apt upgrade -yq && \
    apt install git -yq

# Clone SOFTWARE_TEMPLATE
RUN git clone https://github.com/geodynamics/software_template.git /home/software_template

# Add any other build instructions for SOFTWARE_TEMPLATE
# RUN cd /home/software_template && \
#     cmake . && \
#     make && \
#     make install

WORKDIR /home/software_template
