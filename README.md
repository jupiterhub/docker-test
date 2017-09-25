# docker-test
trying out docker

# Docker only works with Windows Pro (needs Hyper-V)
- Use The Docker Toolbox instead of Upgrading to PRO (will save about 100USD)

# Run
- Install Docker Windows Pro- https://store.docker.com/editions/community/docker-ce-desktop-windows
- Install Docker Windows Home - https://www.docker.com/products/docker-toolbox
- Get the IP of the docker using the following command ```docker-machine ip default```
- ```docker run -p 4000:80 friendlyhello```
- Access from your browser ```http://{VM-IP}:4000```