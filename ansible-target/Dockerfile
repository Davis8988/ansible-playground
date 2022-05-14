FROM ansible-base

# Install Python
RUN yum install -y https://repo.ius.io/ius-release-el7.rpm && \
	yum update -y && \
	yum install -y python36u python36u-libs python36u-devel python36u-pip && \
	python3.6 -V


# Install Ansible
RUN python3 -m pip install --user ansible && \
	python3 -m pip install --user paramiko && \
	ansible --version


