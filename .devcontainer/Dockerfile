# Use Ubuntu 24.04 Image
FROM mcr.microsoft.com/devcontainers/base:ubuntu-24.04

# Update all packages and install python (3.11) full suite
RUN sudo apt-get -y update && sudo apt-get -y dist-upgrade
RUN sudo apt-get -y install software-properties-common
RUN sudo add-apt-repository universe multiverse
RUN sudo add-apt-repository ppa:deadsnakes/ppa
RUN sudo apt -y install python3.11-full python3.11-lib2to3 python3.11-venv python3.11-tk python3.11-dev python3.11-distutils libpython3.11 libpython3.11-dbg libpython3.11-dev libpython3.11-minimal libpython3.11-stdlib libpython3.11-testsuite python3.11-dbg python3.11-examples python3.11-gdbm python3.11-gdbm-dbg python3.11-tk-dbg
RUN curl -sS https://bootstrap.pypa.io/get-pip.py | python3.11
