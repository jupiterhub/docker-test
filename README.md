# Jupiter's conclusion
Docker used to be just a container service, but the recent introduction ofSwarm and Stack (manages orchestration of scaling multiple containers) had made it more fully featured. 

The tutorial at their site is quite easy to grasp.

You can still use Docker as just a container and let other tech handle the managing (i.e. Kubernates)
Kubernates (a.k.a. k8) is made for that purpose. 

Thus, I recommend using both

# docker-test
trying out docker

# Run
- Install Docker Windows Pro- https://store.docker.com/editions/community/docker-ce-desktop-windows (needs Hyper-V)
- Install Docker Windows Home - https://www.docker.com/products/docker-toolbox
- Get the IP of the docker using the following command ```docker-machine ip default```
- ```docker run -p 4000:80 friendlyhello```
- Access from your browser ```http://{VM-IP}:4000```

# Resources
- https://docs.docker.com/get-started