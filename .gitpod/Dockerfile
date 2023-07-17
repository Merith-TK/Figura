FROM gitpod/workspace-base

USER gitpod

# Install Java 8 and 16
RUN sudo apt-get -q update && \
    sudo apt install -yq openjdk-8-jdk openjdk-16-jdk openjdk-17-jdk

# This is so that you can use java 8 until such a time as you switch to java 16
RUN sudo update-java-alternatives --set java-1.17.0-openjdk-amd64