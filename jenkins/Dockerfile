FROM jenkins/jenkins:lts

USER root

# Install Docker
RUN apt-get update && \
    apt-get install -y apt-transport-https \
                        ca-certificates \
                        curl \
                        gnupg \
                        lsb-release \
                        software-properties-common && \
    apt-get update && \
    apt-get install -y docker.io