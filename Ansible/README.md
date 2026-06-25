A lab topology for Containerlabs with 10 routers using XRd Control Plane images and configured with Ansible.

Routers divided into two Autonomous Systems with 5 routers in each. Each Autonomous System runs iBGP and IS-IS, and the two AS's connected through R1 and R6 through eBGP.

IP addresses in hosts.yml intentionally left incomplete as Containerlabs assign different addresses on every deployment.
