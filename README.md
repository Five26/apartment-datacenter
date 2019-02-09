# apartment-datacenter
tools and documentation on how to provision/manage home infrastructure

## Hardware

### Servers
* [Intel NUC](https://www.intel.com/content/www/us/en/products/boards-kits/nuc.html) - Small footprint host with decent power
* [Raspberry Pi](https://www.raspberrypi.org/) - low-power and highly customizable tiny computer 

### Networking

#### Firewalls
* [Ubiquiti](https://www.ui.com/) - Newer networking vendor with easy setup and monitoring dashboards

#### Switches
* [Ubiquiti](https://www.ui.com/) - Newer networking vendor with easy setup and monitoring dashboards

#### Wireless
* [Ubiquiti](https://www.ui.com/) - Newer networking vendor with easy setup and monitoring dashboards

### Storage
* [FreeNAS](https://freenas.org/) - open source NAS Software with extensive  hardware compatibility

* [Synology](https://www.synology.com/en-us) - easy to use and expensive NAS platform

## Software

### Containerization

* [Docker](https://www.docker.com/) - duh
* [Docker Registry](https://docs.docker.com/registry/) - Store docker images in a local registry
* [Kubernetes](https://kubernetes.io/) - industry favorite container orchestration 
* [Nomad](https://www.nomadproject.io/intro/index.html) - Hashicorp's container orchestration

### Monitoring
* [Grafana](https://grafana.com/) - pretty dashboards
* [InfluxDB](https://www.influxdata.com/) - time series database for metrics/events
* [Prometheus](https://prometheus.io/) - popular monitoring tool
* [Sensu](https://sensu.io/) - popular monitoring tool

### Provisioning Tools

* [Ansible](https://www.ansible.com/)
* [Digital Rebar Provisioning](http://rebar.digital/) - Alternative to Foreman and has ability to provision via terraform
    - _Note: vendor pushy by requiring login for certain features, might have to pay for it in the future_

### Virtualization

* [Proxmox](https://www.proxmox.com/en/) - open source hypervisor with paid features
* [VMware ESXi](https://www.vmware.com/products/esxi-and-esx.html) - expensive, but well supported hypervisor. Individual use by expensive VMUG program.
