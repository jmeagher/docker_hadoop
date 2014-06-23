Be patient, this is just getting started.

Things to look at while this is getting up and running:

* http://tech.paulcz.net/2013/09/creating-immutable-servers-with-chef-and-docker-dot-io.html
* https://github.com/continuuity/hadoop_cookbook


Problems you may run into:

* brew install boot2docker installs an older version, use brew cask install brew2docker instead
* If you're using something like boot2docker you will need to increase the RAM for the VM, if you don't do this there will be a big native code build error when it tries to build gecode.

