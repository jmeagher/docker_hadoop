FROM centos
MAINTAINER John Meagher "john.meagher@gmail.com"

RUN yum -y update
RUN yum -y groupinstall "Development Tools"
RUN yum -y install curl libxml2-dev libxslt-dev git
RUN curl -L https://www.opscode.com/chef/install.sh | bash
RUN echo "gem: --no-ri --no-rdoc" > ~/.gemrc
RUN /opt/chef/embedded/bin/gem install berkshelf
