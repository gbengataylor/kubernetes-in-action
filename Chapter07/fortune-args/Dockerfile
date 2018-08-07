FROM ubuntu:latest

RUN apt-get update ; apt-get -y install fortune
ADD fortuneloop.sh /bin/fortuneloop.sh

#command to run when container is run
ENTRYPOINT ["/bin/fortuneloop.sh"]
#argument to be passed to the exec
CMD ["10"]
