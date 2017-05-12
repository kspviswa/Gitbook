# Get ONOS blackbox

One of the best way to learn ONOS is to just start using it as a [blackbox](https://en.wikipedia.org/wiki/Black_box). Thankfully ONOS project had did a good job on packing ONOS as a self-contained package. Currently there are 3 different ways in which you can actually get ONOS up & running, just like that. Lets learn more...

## ONOS docker image

Docker has been the most preferred way of packaging nowadays. ONOS is no stranger to docker. Every official release of ONOS will be available in docker environment. Apart from official release, if you like to generate a docker container for your own distribution, that is also provided as a simple sleek command.

Before trying to understand how to create your own docker container, lets learn how to use official ONOS docker images.

### ONOS in dockerhub

You can find present / latest & previous release of ONOS in docker hub @  [https://hub.docker.com/r/onosproject/onos/ ](https://hub.docker.com/r/onosproject/onos/)

![](/assets/onos-docker.png)

As noted in docker page, all you need to do is to pull onos docker image as follows :

Install docker if you don't have one \( on ubuntu preferably \)

`sudo apt-get remove docker docker-engine`

Once done, you can easily pull docker images 

