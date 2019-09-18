https://lists.apache.org/list.html?dev@fineract.apache.org
Hi!

I have completed seting up public DockerHub images for all Fineract-CN
applications and also updated Docker-Compose scripts to run them. Docker
images are automatically built and uploaded to:
https://hub.docker.com/r/apache/fineract-cn-<projectname>

So if anyone wants to try out Fineract-CN at their own computer then there
is one command to start up Postgres, Cassandra ActiveMQ and another command
to start up a set of Fineract CN micro services like this:

docker-compose up provisioner-ms identity-ms office-ms customer-ms
accounting-ms fims-web-app

Documentation is here:
*
https://cwiki.apache.org/confluence/display/FINERACT/DockerHub+images#DockerHubimages-RunningwithDockerCompose
* https://github.com/apache/fineract-cn-docker-compose

Thank you Awasum, Courage, Vishwas and Michael for all the help and
previous work.

Following repositories:
* https://github.com/openMF/fineract-cn-containers
* https://github.com/vishwasbabu/ProvisioningFineractCN
can now be archived as I have defeloped furter the work there and the
outcome is now available here:
https://github.com/apache/fineract-cn-docker-compose

Kind regards
Juhan
