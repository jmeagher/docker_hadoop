FROM docker_hadoop/base
MAINTAINER John Meagher "john.meagher@gmail.com"

ADD . /chef_base
RUN cd /chef_base && /opt/chef/embedded/bin/berks vendor /chef_base/cookbooks
RUN chef-solo -c /chef_base/solo.rb -j /chef_base/solo.json

