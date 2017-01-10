
Training Materials:
Required for the workshop.
Github repository, Docker Orchestration Workshop, https://github.com/jpetazzo/orchestration-workshop
Slides, Advanced Docker and Orchestration, https://jpetazzo.github.io/orchestration-workshop/

Supplemental Materials:
The following material will deepen your knowledge of how Docker and supporting technology works.

Intro to Docker 
http://view.dckr.info/DockerIntro.pdf

Play with Docker without installing it 
http://play-with-docker.com/

Swarm kit 
https://github.com/docker/swarmkit/blob/master/design/nomenclature.md

Custom shell prompt to work with docker machine 
https://github.com/jpetazzo/orchestration-workshop/blob/master/prepare-vms/scripts/postprep.rc#L68

Consensus protocols RAFT and Paxos 
https://raft.github.io/
https://en.wikipedia.org/wiki/Raft_(computer_science)
https://en.wikipedia.org/wiki/Paxos_(computer_science)

Docker overlay networking, VXLAN 
http://blog.nigelpoulton.com/demystifying-docker-overlay-networking/

Building 12 Factor Applications 
https://12factor.net/

Linux Kernel IPVS load balancer 
http://www.linuxvirtualserver.org/software/ipvs.html
https://www.youtube.com/watch?v=oFsJVV1btDU&index=5&list=PLkA60AVN3hh87OoVra6MHf2L4UR9xwJkv

## Instructions
This will create five CentOS 7 VMs with Docker, Docker Machine and Docker Compose.

1. Clone this repository.
2. Run `vagrant up`
3. You will have five VMs, docker1 ... docker5.