[中国](/README.md)

# Openstack Cheat Sheet

## OpenStack project

The latest version of Ocata, data from https://www.openstack.org/software/project-navigator, click to view [full JSON data](openstack_services_format.json).

### Management tools

|Name|LOGO|service|age|deployment rate|maturity|
|----|----|----|----|----|----|
|[Horizon](https://wiki.openstack.org/wiki/Horizon)|![horizon](https://www.openstack.org/software/images/mascots/horizon.png)|Dashboard|6 years|87%|6/7|
|[OSclient (CLI)](https://wiki.openstack.org/wiki/OSclient)|![osclient-(cli)](https://www.openstack.org/software/images/mascots/osclient-(cli).png)|Command-line client|1 year|0%|0/7|
|[Rally](https://wiki.openstack.org/wiki/Rally)|![rally](https://www.openstack.org/software/images/mascots/rally.png)|Benchmark service|1 year|23%|0/7|
|[Senlin](https://wiki.openstack.org/wiki/Senlin)|![senlin](https://www.openstack.org/software/images/mascots/senlin.png)|Clustering service|1 year|0%|0/7|
|[Vitrage](https://wiki.openstack.org/wiki/Vitrage)|![vitrage](https://www.openstack.org/software/images/mascots/vitrage.png)|RCA (Root Cause Analysis service)|1 year|0%|0/7|
|[Watcher](https://wiki.openstack.org/wiki/Watcher)|![watcher](https://www.openstack.org/software/images/mascots/watcher.png)|Optimization Service|1 year|0%|0/7|

### Network & content distribution

|Name|LOGO|service|age|deployment rate|maturity|
|----|----|----|----|----|----|
|[Neutron](https://wiki.openstack.org/wiki/Neutron)|![neutron](https://www.openstack.org/software/images/mascots/neutron.png)|Networking|5 years|93%|7/7|
|[Designate](https://wiki.openstack.org/wiki/Designate)|![designate](https://www.openstack.org/software/images/mascots/designate.png)|DNS Service|3 years|16%|3/7|
|[Dragonflow](https://wiki.openstack.org/wiki/Dragonflow)|![dragonflow](https://www.openstack.org/software/images/mascots/dragonflow.png)|Neutron Plugin|2 years|0%|0/7|
|[Kuryr](https://wiki.openstack.org/wiki/Kuryr)|![kuryr](https://www.openstack.org/software/images/mascots/kuryr.png)|Container plugin|1 year|0%|1/7|
|[Octavia](https://wiki.openstack.org/wiki/Octavia)|![octavia](https://www.openstack.org/software/images/mascots/octavia.png)|Load Balancer|1 year|0%|1/7|
|[Tacker](https://wiki.openstack.org/wiki/Tacker)|![tacker](https://www.openstack.org/software/images/mascots/tacker.png)|NFV Orchestration|1 year|0%|1/7|
|[Tricircle](https://wiki.openstack.org/wiki/Tricircle)|![tricircle](https://www.openstack.org/software/images/mascots/tricircle.png)|Networking Automation for Multi-Region Deployments|1 year|0%|0/7|

### Deployment Tools

|Name|LOGO|service|age|deployment rate|maturity|
|----|----|----|----|----|----|
|[Chef OpenStack](https://wiki.openstack.org/wiki/Chef)|![chef-openstack](https://www.openstack.org/software/images/mascots/chef-openstack.png)|Chef cookbooks for OpenStack|1 year|0%|1/7|
|[Kolla](https://wiki.openstack.org/wiki/Kolla)|![kolla](https://www.openstack.org/software/images/mascots/kolla.png)|Container deployment|1 year|12%|1/7|
|[OpenStack Charms](https://wiki.openstack.org/wiki/OpenStack)|![openstack-charms](https://www.openstack.org/software/images/mascots/openstack-charms.png)|Juju Charms for OpenStack|1 year|0%|0/7|
|[OpenStack-Ansible](https://wiki.openstack.org/wiki/OpenStack-Ansible)|![openstack-ansible](https://www.openstack.org/software/images/mascots/openstack-ansible.png)|Ansible Playbooks for OpenStack|1 year|0%|0/7|
|[Puppet OpenStack](https://wiki.openstack.org/wiki/Puppet)|![puppet-openstack](https://www.openstack.org/software/images/mascots/puppet-openstack.png)|Puppet Modules for OpenStack|1 year|0%|0/7|
|[TripleO](https://wiki.openstack.org/wiki/TripleO)|![tripleo](https://www.openstack.org/software/images/mascots/tripleo.png)|Deployment service|1 year|9%|0/7|

### Used and certified

|Name|logo|.|Give|deploy rate|fresh|
|----|----|----|----|----|----|
|[Keystone](https://wiki.openstack.org/wiki/Keystone)|![keystone](https://www.openstack.org/software/images/mascots/keystone.png)|Identity service|6 years|96%|6/7|
|[Barbican](https://wiki.openstack.org/wiki/Barbican)|![barbican](https://www.openstack.org/software/images/mascots/barbican.png)|Key Management|4 years|9%|4/7|
|[Congress](https://wiki.openstack.org/wiki/Congress)|![congress](https://www.openstack.org/software/images/mascots/congress.png)|Governance|2 years|2%|1/7|
|[Mistral](https://wiki.openstack.org/wiki/Mistral)|![mistral](https://www.openstack.org/software/images/mascots/mistral.png)|Workflow service|1 year|5%|1/7|

### Data & analysis

|Name|LOGO|service|age|deployment rate|maturity|
|----|----|----|----|----|----|
|[Trove](https://wiki.openstack.org/wiki/Trove)|![trove](https://www.openstack.org/software/images/mascots/trove.png)|Database as a Service|4 years|13%|3/7|
|[Sahara](https://wiki.openstack.org/wiki/Sahara)|![sahara](https://www.openstack.org/software/images/mascots/sahara.png)|Big Data Processing Framework Provisioning|3 years|10%|3/7|
|[Searchlight](https://wiki.openstack.org/wiki/Searchlight)|![searchlight](https://www.openstack.org/software/images/mascots/searchlight.png)|Indexing and Search|1 year|0%|0/7|

### Store & backup & restore

|Name|LOGO|service|age|deployment rate|maturity|
|----|----|----|----|----|----|
|[Swift](https://wiki.openstack.org/wiki/Swift)|![swift](https://www.openstack.org/software/images/mascots/swift.png)|Object Store|7 years|52%|6/7|
|[Cinder](https://wiki.openstack.org/wiki/Cinder)|![cinder](https://www.openstack.org/software/images/mascots/cinder.png)|Block Storage|5 years|88%|7/7|
|[Manila](https://wiki.openstack.org/wiki/Manila)|![manila](https://www.openstack.org/software/images/mascots/manila.png)|Shared Filesystems|3 years|14%|5/7|
|[Karbor](https://wiki.openstack.org/wiki/Karbor)|![karbor](https://www.openstack.org/software/images/mascots/karbor.png)|Application Data Protection as a Service|1 year|0%|0/7|
|[Freezer](https://wiki.openstack.org/wiki/Freezer)|![freezer](https://www.openstack.org/software/images/mascots/freezer.png)|Backup, Restore, and Disaster Recovery|2 years|0%|0/7|

### Calculation

|Name|LOGO|service|age|deployment rate|maturity|
|----|----|----|----|----|----|
|[Nova](https://wiki.openstack.org/wiki/Nova)|![nova](https://www.openstack.org/software/images/mascots/nova.png)|Compute Service|7 years|95%|7/7|
|[Glance](https://wiki.openstack.org/wiki/Glance)|![glance](https://www.openstack.org/software/images/mascots/glance.png)|Image Service|7 years|95%|5/7|
|[Ironic](https://wiki.openstack.org/wiki/Ironic)|![ironic](https://www.openstack.org/software/images/mascots/ironic.png)|Bare Metal Provisioning Service|3 years|21%|5/7|
|[Magnum](https://wiki.openstack.org/wiki/Magnum)|![magnum](https://www.openstack.org/software/images/mascots/magnum.png)|Container Orchestration Engine Provisioning|2 years|11%|2/7|
|[Storlets](https://wiki.openstack.org/wiki/Storlets)|![storlets](https://www.openstack.org/software/images/mascots/storlets.png)|Computable Object Store|1 year|0%|0/7|
|[Zun](https://wiki.openstack.org/wiki/Zun)|![zun](https://www.openstack.org/software/images/mascots/zun.png)|Container Management Service|1 year|0%|1/7|

### Application services

|Name|LOGO|service|age|deployment rate|maturity|
|----|----|----|----|----|----|
|[Heat](https://wiki.openstack.org/wiki/Heat)|![heat](https://www.openstack.org/software/images/mascots/heat.png)|Orchestration|5 years|67%|5/7|
|[Zaqar](https://wiki.openstack.org/wiki/Zaqar)|![zaqar](https://www.openstack.org/software/images/mascots/zaqar.png)|Messaging Service|3 years|4%|4/7|
|[Murano](https://wiki.openstack.org/wiki/Murano)|![murano](https://www.openstack.org/software/images/mascots/murano.png)|Application Catalog|2 years|11%|1/7|
|[Solum](https://wiki.openstack.org/wiki/Solum)|![solum](https://www.openstack.org/software/images/mascots/solum.png)|Software Development Lifecycle Automation|1 year|2%|0/7|

### Monitoring & metering

|Name|LOGO|service|age|deployment rate|maturity|
|----|----|----|----|----|----|
|[Ceilometer](https://wiki.openstack.org/wiki/Ceilometer)|![ceilometer](https://www.openstack.org/software/images/mascots/ceilometer.png)|Metering & Data Collection Service|5 years|55%|1/7|
|[CloudKitty](https://wiki.openstack.org/wiki/CloudKitty)|![cloudkitty](https://www.openstack.org/software/images/mascots/cloudkitty.png)|Billing and chargebacks|1 year|0%|0/7|
|[Monasca](https://wiki.openstack.org/wiki/Monasca)|![monasca](https://www.openstack.org/software/images/mascots/monasca.png)|Monitoring|1 years|0%|0/7|
|[aodh](https://wiki.openstack.org/wiki/aodh)|![aodh](https://www.openstack.org/software/images/mascots/aodh.png)|Alarming Service|1 year|0%|0/7|
|[panko](https://wiki.openstack.org/wiki/panko)|![panko](https://www.openstack.org/software/images/mascots/panko.png)|Event, Metadata Indexing Service|7 years|0%|0/7|

## OpenStack service vs. AWS service

|OpenStack|AWS|Service|Description|
|---------|---|-------|-----------|
|Keystone|AWS IAM|Authentication Service|Authentication, Service rules and service tokens|
|Glance|AMI|Mirror service|mirror repository, responsible for mirroring functions such as uploading, registering, retrieving, managing metadata, and downloading|
|Nova|EC2|Compute services|manage compute resources, including virtual machines and bare-metal instances.|
|Neutron|Networking|Network services|Provision of virtual network services.|
|Cinder|EBS|Block storage services|elastic cloud hard disk capabilities for virtual machines.|
|Swift|S3|Object Storage Service|Object Storage Service, similar to Baidu network disk function.|
|Mistral|Amazon SWF|Workflow (Workflow)services|task scheduling and timing task management, such as timing backup, timing switch and so on.|
|Sahara|EMR|Big Data Services|Hadoop/Spark cluster deployment and Job submission.|
|Trove|ElastiCache & RDS|Database services|provide elastic database services, support Mysql, Redis and other databases.|
|Ceilometer|CloudWatch|Resource monitoring service|resource monitoring service to collect resource usage for each component.|
|Heat|CloudFormation|Resource orchestration services|use templates to manage resources in bulk|
|Senlin|Auto Scaling|Clustered elastic scaling services|support for elastic horizontal and vertical scaling of resources|
|Zaqar|SQS & SNS|Message Queuing service, message push service|
|Ironic|-|Bare Metal services|manage Bare Metal resources / AWS and OpenStack manage Bare Metal instances using EC2 and Nova respectively|
|Magnum|-|Container orchestration services|create and manage container orchestration services such as Swarm and k8s|
|Zun|ECS(Amazon EC2 Container Service)|Container services|provide container management services|
|Designate|Route 53|DNS service|provided cloud domain name system|
|Barbican|-|Key management services|-|
|Congress|-|policy as a service|Policy statement, monitoring, implementation, audit framework based on heterogeneous cloud environment|
|Horizon|AWS console|Panel Services|Console, providing a Web UI interface for OpenStack to manage resources|
|Cloudkitty|Billing|Billing services|                                     
|Freezer|[Freezer](https://github.com/stevegury/freezer)(Unofficial)|backup service|file system, database data, virtual machine, disk automatic incremental backup to Swift|
|Manila|EFS|File sharing services|provide file system sharing services such as NFS|
|Murano|AWS Service Catalog|Application directory service|similar application store, through a unified Framework and API to achieve rapid application deployment and application lifecycle management features, such as the deployment of Apache HTTP service|
|Searchlight|-|Search services|OpenStack resources are indexed in Elasticsearch to provide a quick search of resources on the OpenStack platform|
|Solum|-|-|On the OpenStack IaaS platform, building a continuous integration/continuous Delivery (CI/CD) application for the PaaS layer can be easily understood as an integrated development platform for application Apps|
|Tacker||NFV Orchestrator service||
|Tricircle||networking automation|Neutron network management for multi-zone OpenStack platform|
|Vitrage|-|RCA (Root Cause Analysis) service, platform problem location analysis service|used to organize, analyze and extend OpenStack alarms and events to find the root cause before the real problem occurs|
|Watcher|-|resource optimization service|generate resource optimization strategy based on certain strategies, objectives and data collection|
|[Karbor](https://wiki.openstack.org/wiki/Karbor)||Application Data Protection as a Service||


## Official resources

* [Home](http://www.openstack.org/)
* [git source address](http://git.openstack.org/cgit)
* [Github source image](https://github.com/openstack/openstack)
* [Component items](http://governance.openstack.org/reference/projects/index.html) (Big Tent Government)
* [Official document](http://docs.openstack.org/)
* [Mailing list](http://lists.openstack.org/cgi-bin/mailman/listinfo)
* [IRC(freenode)](https://wiki.openstack.org/wiki/IRC)
* [Code review](https://review.openstack.org)
* [Roadmap](https://www.openstack.org/software/roadmap/)
* [Wiki](https://wiki.openstack.org/wiki/Main_Page)
* [Blueprints](https://blueprints.launchpad.net/openstack)
* [Bugs](https://bugs.launchpad.net/openstack)
* [Support company](https://www.openstack.org/foundation/companies/) (Companies Supporting The OpenStack Foundation)
* [Contribution statistics (stacklytics)](http://stackalytics.com (Provide transparent and meaningful statistics regarding contributions to both OpenStack itself and projects related to OpenStack.)
* [Community development documentation](http://docs.openstack.org/infra/manual/developers.html) (step by step, teach you how to join the community)
* [Code submission test](http://docs.openstack.org/infra/manual/sandbox.html#sandbox) (novice code to submit the test, novice can use this familiar code to submit the process)
* [git commit message specification](https://wiki.openstack.org/wiki/GitCommitMessages#Summary_of_GIT_commit_message_structure) (the specification of the message that must be followed when submitting the code)
* [Openstack code specification](http://docs.openstack.org/developer/hacking/#creating-unit-tests) (**Openstack code specification, developer must read**)
* [OpenStack various components maturity and heat statistics](http://www.openstack.org/software/project-navigator)
* [Openstack version list](https://releases.openstack.org/) (you can see the digital version of the OpenStack version of the code, such as Nova version 13. X. x corresponds to the mitaka version)


## Members

### Platinum members

Provide a significant portion of the funding to achieve the Foundation's mission of protecting, empowering and promoting the OpenStack community and software. Each Platinum Member's company strategy aligns with the OpenStack mission and is responsible for committing full-time resources toward the project. There are **eight Platinum Members** at any given time, each of which holds a seat on the Board of Directors.

* [AT&T](http://www.att.com/)
* [Canonical](https://www.openstack.org/foundation/companies/profile/canonical)
* [Hewlett Packard Enterprise](https://www.openstack.org/foundation/companies/profile/hewlett-packard-enterprise)
* [IBM](https://www.openstack.org/foundation/companies/profile/ibm)
* [Intel](http://www.intel.cn/content/www/cn/zh/homepage.html)
* [Rackspace](https://www.openstack.org/foundation/companies/profile/rackspace)
* [Red Hat, Inc.](https://www.openstack.org/foundation/companies/profile/page-0)
* [SUSE](https://www.openstack.org/foundation/companies/profile/suse)

### Gold member

Provide funding and pledge strategic alignment to the OpenStack mission. There can be up to twenty-four Gold Members at any given time, subject to board approval. 

* [Aptira](https://aptira.com/)
* [CCAT](https://www.openstack.org/foundation/companies/profile/ccat)
* [Cisco](https://www.openstack.org/foundation/companies/profile/cisco)
* [Dell](https://www.openstack.org/foundation/companies/profile/dell)
* [DreamHost](https://www.openstack.org/foundation/companies/profile/dreamhost)
* [EasyStack](https://www.openstack.org/foundation/companies/profile/easystack)
* [EMC](http://www.emc.com/en-us/index.htm)
* [Ericsson](https://www.openstack.org/foundation/companies/profile/ericsson)
* [Fujitsu](https://www.openstack.org/foundation/companies/profile/fujitsu)
* [Hitachi](https://www.openstack.org/foundation/companies/profile/Hitachi-Data-Systems)
* [Huawei](https://www.openstack.org/foundation/companies/profile/huawei)
* [inwinSTACK](https://www.openstack.org/foundation/companies/profile/inwinstack)
* [Juniper Networks](https://www.openstack.org/foundation/companies/profile/juniper-networks)
* [Mirantis](https://www.openstack.org/foundation/companies/profile/mirantis)
* [NEC](https://www.openstack.org/foundation/companies/profile/nec)
* [NetApp](https://www.openstack.org/foundation/companies/profile/netapp)
* [Symantec](https://www.openstack.org/foundation/companies/profile/symantec-8)
* [UnitedStack Inc.](https://www.openstack.org/foundation/companies/profile/unitedstack)
* [Virtuozzo](https://www.openstack.org/foundation/companies/profile/virtuozzo)
* [Yahoo Inc.](https://www.openstack.org/foundation/companies/profile/yahoo)

## Automated deployment

* [Devstack](http://docs.openstack.org/developer/devstack/)(Oneiric powered development environment for openstack.)
* [Fuel](https://www.mirantis.com/products/mirantis-openstack-software/)(The leading purpose-built open source deployment and management tool for OpenStack.)
* [RDO](https://www.rdoproject.org/)(A communiaty of people using and deploying OpenStack on CentOS, Fedora, and Red Hat Enterprise Linux.)
* [openstack-puppet](https://wiki.openstack.org/wiki/Puppet)(Bring scalable and reliable IT automation to OpenStack cloud deployments using puppet.)
* [openstack-ansible](https://github.com/openstack/openstack-ansible)(Ansible playbooks for deploying OpenStack.)
* [kolla](https://github.com/openstack/kolla)(Deploying OpenStack using Docker.)
* [TripleO](https://wiki.openstack.org/wiki/TripleO)(A program aimed at installing, upgrading and operating OpenStack clouds using OpenStacks own cloud facilities as the foundations.)
* [SaltStack](https://github.com/cloudbase/salt-openstack)(Deploying Openstack using saltstack.)
* [packstack](https://github.com/openstack/packstack) (Install utility to deploy openstack on multiple hosts.)

## Monitoring

* [cloudpulse](https://github.com/openstack/cloudpulse): Openstack service status monitoring
* [Vitrage](https://github.com/openstack/Vitrage): Openstack failure analysis, failure Spanning Tree
* [fuel-plugin-external-zabbix](https://github.com/openstack/fuel-plugin-external-zabbix): Fuel Openstack zabbix monitoring project, contains all monitoring items
* [fuel-ostf](https://github.com/openstack/fuel-ostf): Fuel's integrated test, functional test framework


## Competitors

* [AWS](https://aws.amazon.com)(Offers reliable, scalable, and inexpensive cloud computing services.)
* [CloudStack](https://cloudstack.apache.org/)(Open source software designed to deploy and manage large networks of virtual machines, as highly scalable Infrastructure as a Service (IaaS) cloud computing platform.)
* [Vmware](http://www.vmware.com/)(The industry-leading virtualization software company.)
* [Docker](https://www.docker.com)(Docker containers and tooling make building and shipping applications dramatically easier and faster.)

## Service directory

|Service Name|Service Type|service features|listening port|default endpoints|
|------|------|------|------|------|
|ironic|baremetal|Bare Metal services|6385|http://${HOST}:6385
|ironic-inspector|Bare Metal Autodiscover service|5000|baremetal-introspection|http://${HOST}:5050
|cinder|volume|Block storage services|9776|http://${HOST}:8776/v2/%(tenant_id)s
|glance|image|Mirror services|9292|http://${HOST}:9292
|heat|orchestration|Orchestration services|8004|http://${HOST}:8004/v1/%(tenant_id)s
|heat-cfn|cloudformation|--|8000|http://${HOST}:8000/v1
|keystone|identity|Certification services|5000、35357|http://${HOST}:5000/v3
|magnum|container-infra|Container orchestration services|9511|http://${HOST}:9511/v1
|mistral|workflow|Workflow services|9898|http://${HOST}:9898/v2
|neutron|network|Network services|9696|http://${HOST}:9696
|nova|compute|Computing services|8774、8773、8775|http://${HOST}:8774/v2.1/%(tenant_id)s
|sahara|data-processing|Big Data Services|8386|http://${HOST}:8386/v1.1/%(project_id)s
|swift|object-store|Object Store service|8080|http://${HOST}:8080/v1/AUTH_%(tenant_id)s
|trove|database|Database services|8779|http://${HOST}:8779/v1.0/%(tenant_id)s|
|designate|dns|DNS service|9001|http://${HOST}:9001/|
|barbican|key-manager|Key services|9311|http://${HOST}:9311/|
|zaqar|messaging|Messaging services|8888|http://${HOST}:8888/|
|manila|share|File sharing service|8786|http://${HOST}:8786/v1/%\(tenant_id\)s|
|aodh|alarming|Warning service|8042|http://${HOST}:8042|
|cloudkitty|rating|Billing services|8889|http://${HOST}:8889|
|ceilometer|metering|Measurement services|8777|http://${HOST}:8777|

## Service initialization template-take cinder as an example

Initializing the database:

```sql
CREATE DATABASE cinder;
GRANT ALL PRIVILEGES ON cinder.* TO 'cinder'@'localhost' IDENTIFIED BY 'CINDER_DBPASS';
GRANT ALL PRIVILEGES ON cinder.* TO 'cinder'@'%' IDENTIFIED BY 'CINDER_DBPASS';
```

Create an account:

```sh
openstack user create --domain default --password CINDER_PASS cinder
openstack role add --project service --user cinder admin
```

Create endpoints:

```sh
openstack service create --name cinder \
  --description "OpenStack Block Storage" volume

openstack endpoint create --region RegionOne \
  volume public 'http://controller:8776/v2/%(tenant_id)s'

openstack endpoint create --region RegionOne \
  volume admin 'http://controller:8776/v2/%(tenant_id)s'

openstack endpoint create --region RegionOne \
  volume internal 'http://controller:8776/v2/%(tenant_id)s'
```

## keystore

## glance

## nova

### Create a Ceph secret:

```sh
#!/bin/sh

USERNAME=${1:-admin}
UUID=${2:-$(uuidgen)}

# Generate secret.xml files
cat > secret.xml <<EOF
<secret ephemeral='no' private='no'>
  <uuid>${UUID}</uuid>
  <usage type='ceph'>
    <name>client.${USERNAME} secret</name>
  </usage>
</secret>
EOF

# Create a secret from an xml file
UUID=$(sudo virsh secret-define --file secret.xml | grep -Po '\w{8}-(\w{4}-){3}\w{12}')
if [ $? -ne 0 ]; then
    rm -f client."${USERNAME}".key secret.xml
    exit 1
fi

# Get the ceph client's key
KEY=$(ceph auth get-key client."${USERNAME}")
if [ $? -ne 0 ]; then
    sudo virsh secret-undefine "${UUID}"
    exit 1
fi

# Associate the key to the newly created secret
sudo virsh secret-set-value --secret "${UUID}" --base64 "${KEY}" >/dev/null \
    && rm -f client."${USERNAME}".key secret.xml

echo "Secret $UUID create sucessfully!"
```

**👉[scripts/create_libvirt_ceph_secret.sh](scripts/create_libvirt_ceph_secret.sh).**

### Tips

List all error cloud hosts:

```
nova list --status error --all-tenants
```

Lists hosts and mapped hosts:

```
nova list --fields name,host
```

Get the id of all hosts:

```
nova list --minimal | tail -n +4 | head -n -1 | cut -d ' ' -f 2
```

Gets the host id for all error States:

```
nova list --minimal --status error --all-tenants | tail -n +4 | head -n -1 | cut -d ' ' -f 2
```

Gets all hosts whose names begin with test:

```
nova list --name "^test"
```

Gets the volume id of all host mounts:

```
nova show --minimal 65e761b3-63b4-498f-9735-08e246c1e976 | grep 'os-extended-volumes:volumes_attached' | cut -d '|' -f 3 | jq '.[].id' | sed 's/"//g'
```

Gets the volume id and device name of all host mounts:

```
nova show --minimal | grep 'os-extended-volumes:volumes_attached' | cut -d '|' -f 3 | jq '.[]|.id + " " + .device_name' | sed 's/"//g'
```


## cinder

[CinderSupportMatrix](https://wiki.openstack.org/wiki/CinderSupportMatrix):

|Driver|Volume|Snapshot|Clone|Replication|Consistency Group|Qos|Extend(扩容)|
|----|----|----|----|----|----|----|----|
|Blockbridge|Liberty|Liberty|Liberty|||Liberty|Liberty|
|CloudByte|Kilo|Kilo|Kilo||||Kilo|
|Coho Data|Mitaka|Mitaka|Mitaka|||Newton|Mitaka|
|Coraid|Grizzly|Grizzly|Havana||||Havana|
|Datera|Juno|Juno|Juno|||Mitaka|Juno|
|Dell EqualLogic|Havana|Havana|Havana||||Icehouse|
|Dell Storage Center|Kilo|Kilo|Kilo|Mitaka|Liberty||Kilo|
|DRBD via DRBDmanage|Liberty|Liberty|Liberty||||Liberty|
|Dell EMC VMAX AF 250F, 450F, 850F|Mitaka|Mitaka|Mitaka|Ocata|Mitaka|Newton|Mitaka|
|Dell EMC VMAX3 100K, 200K, 400K|Liberty|Liberty|Liberty|Ocata|Mitaka|Newton|Mitaka|
|Dell EMC VMAX V2 10K, 20K, 40K|Grizzly|Grizzly|Grizzly||Kilo||Juno|
|Dell EMC Unity|Ocata|Ocata|Ocata|||Ocata|Ocata|
|Dell EMC VNX Direct|Icehouse|Icehouse|Icehouse|Mitaka|Juno||Icehouse|
|Dell EMC XtremIO|Juno|Juno|Juno||Liberty||Juno|
|Dell EMC ScaleIO|Liberty|Liberty|Liberty||Mitaka|Mitaka|Liberty|
|Fujitsu ETERNUS|Juno|Juno|Juno||||Juno|
|GlusterFS|Grizzly|Havana|Havana||||Havana|
|Hitachi (HUS)|Havana|Havana|Havana||||Havana|
|Hitachi (HUS-VM)|Juno|Juno|Juno||||Juno|
|Hitachi (VSP, VSP G1000)|Juno|Juno|Juno||||Juno|
|Hitachi (VSP G200-G800)|Kilo|Kilo|Kilo||||Kilo|
|Hitachi (HNAS)|Juno|Juno|Juno||||Juno|
|HPE 3PAR (StoreServ)|Grizzly|Grizzly|Grizzly|Mitaka|Liberty|Icehouse|Havana|
|HPE Lefthand (StoreVirtual)|Diablo|Havana|Icehouse|Mitaka|Liberty||Havana|
|HP MSA|Icehouse|Icehouse|Icehouse||||Icehouse|
|HPE XP|Liberty|Liberty|Liberty||||Liberty|
|Huawei T Series V1|Havana|Havana|Havana||||Havana|
|Huawei T Series V2|Kilo|Kilo|Kilo|||Kilo|Kilo|
|Huawei V3 Series|Kilo|Kilo|Kilo|Mitaka|Newton|Kilo|Kilo|
|Huawei 18000 Series|Kilo|Kilo|Kilo|||Kilo|Kilo|
|Huawei Dorado V3 Series|Ocata|Ocata||Ocata|Ocata||Ocata|
|IBM DS8000|Havana|Havana|Havana|Juno|Kilo||Havana|
|IBM FlashSystem|Kilo|Kilo|Kilo||||Kilo|
|IBM FlashSystem A9000/A9000R|Mitaka|Mitaka|Mitaka|Mitaka|Mitaka|Mitaka|Mitaka|
|IBM GPFS|Havana|Havana|Havana||||Havana|
|IBM Storwize family/SVC|Folsom|Folsom|Grizzly|Juno|Kilo|Juno|Havana|
|IBM NAS|Icehouse|Icehouse|Icehouse||||Icehouse|
|IBM XIV / Spectrum Accelerate|Folsom|Folsom|Havana|Mitaka|Liberty||Havana|
|ITRI DISCO|Mitaka|Mitaka|Mitaka||||Mitaka|
|Lenovo|Liberty|Liberty|Liberty||||Liberty|
|LVM (Reference)|Folsom|Folsom|Grizzly||||Havana|
|NetApp Data ONTAP|Essex|Folsom|Grizzly|Havana|Mitaka|Juno|Havana|
|NetApp E/EF-series|Icehouse|Icehouse|Icehouse||Mitaka||Icehouse|
|Nexenta|Essex|Essex|Havana||||Havana|
|NFS (Reference)|Folsom||||||Havana|
|Nimble Storage|Juno|Juno|Juno||||Juno|
|Pure Storage|Juno|Juno|Juno|Mitaka|Kilo||Juno|
|Quobyte|Kilo|Kilo|Kilo||||Kilo|
|RBD (Ceph)|Cactus|Diablo|Havana||||Havana|
|Scality|Grizzly|Grizzly|Havana||||Havana|
|SMB|Juno|Juno|||||Juno|
|NetApp SolidFire|Folsom|Folsom|Grizzly|Mitaka|Mitaka|Icehouse|Havana|
|StorPool|Kilo|Kilo|Kilo||||Kilo|
|Synology|Newton|Newton|Newton||||Newton|
|Symantec|Kilo|Kilo|Kilo||||Kilo|
|Tintri|Liberty|Liberty|Liberty||||Liberty|
|Violin Memory|Kilo|Kilo|Kilo|n/a|n/a|n/a|Kilo|
|VMware|Havana|Havana|Havana||||Icehouse|
|Windows Server 2012|Grizzly|Grizzly||||||
|X-IO technologies|Kilo|Kilo|Kilo|||Kilo|Kilo|
|Zadara Storage|Folsom|Havana|Havana||||Havana|
|Solaris (ZFS)|Diablo|||||||
|ProphetStor (Flexvisor)|Juno|Juno|Juno||Kilo||Juno|
|Infortrend (EonStor DS/GS/GSe Family)|Liberty|Liberty|Liberty||||Liberty|
|CoprHD|Newton|Newton|Newton||Newton||Newton|
|Kaminario|Newton|Newton|Newton|Newton|||Newton|
|ZTE|Newton|Newton|Newton||||Newton|
|NEC Storage M series|Ocata|Ocata|Ocata|||Ocata|Ocata|
|INFINIDAT|Ocata|Ocata|Ocata||||Ocata|
|QNAP|Ocata|Ocata|Ocata||||Ocata|
|Reduxio|Ocata|Ocata|Ocata||||Ocata|

### Mount volume to local

Installing the cinderclient extension:

```sh
pip install python-brick-cinderclient-ext
```

attach volume到本地:

```sh
$ cinder local-attach 9770a53e-91ce-4cd0-afde-5793bfa6b0ef

+----------+-----------------------------------+
| Property | Value                             |
+----------+-----------------------------------+
| path     | /dev/sdb                          |
| scsi_wwn | 360000000000000000e00000000010001 |
| type     | block                             |
+----------+-----------------------------------+
```

Mount volume:

```
$ mkfs.ext4 /dev/sdb
mke2fs 1.42.13 (17-May-2015)
Creating filesystem with 262144 4k blocks and 65536 inodes
Filesystem UUID: d53932de-2844-4f63-8b37-67db52d1a243
Superblock backups stored on blocks:
        32768, 98304, 163840, 229376

Allocating group tables: done
Writing inode tables: done
Creating journal (8192 blocks): done
Writing superblocks and filesystem accounting information: done

$ mount /dev/sdb /mnt
```

umount & detach:

```
umount /mnt
cinder local-detach 9770a53e-91ce-4cd0-afde-5793bfa6b0ef
```

## neutron

## swift

## trove

## sahara

### Mirror list

* [sahara-image-elements](https://github.com/openstack/sahara-image-elements) (Disk image elements for Sahara.)
* If you don't want to mirror yourself, there is a ready-made image download available here: [prepared images](http://sahara-files.mirantis.com/images/upstream/).
* [Building Images for Vanilla Plugin](http://docs.openstack.org/developer/sahara/userdoc/vanilla_imagebuilder.html).
* [Building Images for Cloudera Plugin](http://docs.openstack.org/developer/sahara/userdoc/cdh_imagebuilder.html).

### Create a cluster--take spark 1.6.0 as an example

Initialize variables:

```sh
# 集群名字
NAME=test
# 镜像uuid，必须是通过sahara注册过的镜像
IMAGE_ID=6ba27a59-ecd7-47d4-8df4-925acb23bb87
# 浮动IP网络uuid
FLOATING_IP=7517cbd2-2d07-44ad-8eaa-b9ec7098071a
# flavor id
FLAVOR_ID=2
# 密钥名称
KEYPAIR_NAME=server-230
# 租户网络uuid
NETWORK_ID=e478bc87-a067-402f-98e2-9bdc9b180d5e
```

Create master group:

```sh
# Create master node group template
cat > spark-master-node-group-template.json <<EOF
{
    "auto_security_group": true,
    "availability_zone": "",
    "description": "spark 1.6.0 master node group",
    "flavor_id": "${FLAVOR_ID}",
    "floating_ip_pool": "${FLOATING_IP}",
    "hadoop_version": "1.6.0",
    "image_id": "${IMAGE_ID}",
    "is_protected": false,
    "is_proxy_gateway": false,
    "is_public": true,
    "name": "${NAME}-master",
    "node_configs": {
        "HDFS": {}
    },
    "node_processes": [
        "namenode",
        "master"
    ],
    "plugin_name": "spark",
    "security_groups": [],
    "shares": [],
    "use_autoconfig": true,
    "volumes_per_node": 1,
    "volumes_size": 20
}
EOF
cat spark-master-node-group-template.json
sahara node-group-template-create --json spark-master-node-group-template.json 2>/dev/null
```

Create a slave group:

```sh
# Create worker node group template
cat > spark-worker-node-group-template.json <<EOF
{
    "auto_security_group": true,
    "availability_zone": "",
    "description": "spark 1.6.0 master node group",
    "flavor_id": "2",
    "floating_ip_pool": "${FLOATING_IP}",
    "hadoop_version": "1.6.0",
    "image_id": "${IMAGE_ID}",
    "is_protected": false,
    "is_proxy_gateway": false,
    "is_public": true,
    "name": "${NAME}-worker",
    "node_configs": {
        "HDFS": {}
    },
    "node_processes": [
        "datanode",
        "slave"
    ],
    "plugin_name": "spark",
    "security_groups": [],
    "shares": [],
    "use_autoconfig": true,
    "volumes_per_node": 1,
    "volumes_size": 20
}
EOF
cat spark-worker-node-group-template.json
sahara node-group-template-create --json spark-worker-node-group-template.json
```

Create a cluster template:

```sh
SPARK_MASTER_GROUP_ID=$(sahara node-group-template-list  2>/dev/null | grep -P -- "\s$NAME-master\s" | awk '{print $4}')
SPARK_WORKER_GROUP_ID=$(sahara node-group-template-list  2>/dev/null | grep -P -- "\s$NAME-worker\s" | awk '{print $4}')

# Create cluster template
cat >spark-cluster-template.json <<EOF
{
    "anti_affinity": [],
    "cluster_configs": {
        "HDFS": {
            "dfs.replication": 1
        },
        "Spark": {},
        "general": {
            "Enable XFS": true
        }
    },
    "description": "spark 1.6.0",
    "hadoop_version": "1.6.0",
    "is_protected": false,
    "is_public": true,
    "name": "${NAME}-cluster-template",
    "node_groups": [
        {
            "count": 1,
            "name": "${NAME}-master",
            "node_group_template_id": "${SPARK_MASTER_GROUP_ID}"
        },
        {
            "count": 1,
            "name": "${NAME}-worker",
            "node_group_template_id": "${SPARK_WORKER_GROUP_ID}"
        }
    ],
    "plugin_name": "spark",
    "shares": [],
    "use_autoconfig": true
}
EOF

echo $NAME-cluster-template:
cat spark-cluster-template.json
sahara cluster-template-create --json spark-cluster-template.json
```

Create a cluster:

```sh
# Create cluster
CLUSTER_TEMPLATE_ID=$(sahara cluster-template-list 2>/dev/null | grep -P "\s${NAME}-cluster-template\s" | awk '{print $4}')
cat >spark_cluster.json <<EOF
{
    "cluster_template_id": "${CLUSTER_TEMPLATE_ID}",
    "default_image_id": "${IMAGE_ID}",
    "description": "",
    "hadoop_version": "1.6.0",
    "is_protected": false,
    "is_public": true,
    "name": "${NAME}",
    "neutron_management_network": "${NETWORK_ID}",
    "plugin_name": "spark",
    "user_keypair_id": "${KEYPAIR_NAME}"
}
EOF

echo $NAME:
cat spark_cluster.json
sahara cluster-create --json spark_cluster.json
```

View the cluster list:

```sh
sahara cluster-list
```

Full script address: [create-spark-cluster.sh](sahara/create-spark-cluster.sh)

### Submit the spark task

Initialize variables:

```sh
# Task name
JOB_NAME=int32bit-spark-wordcount.jar
# jar package path
BINARY_FILE=spark-wordcount.jar
# input hdfs path
INPUT=hdfs://int32bit-spark-spark-master-0:8020/user/ubuntu/hello.txt
# output hdfs path
OUTPUT=hdfs://int32bit-spark-spark-master-0:8020/user/ubuntu/output2
# uuid of the cluster
CLUSTER_UUID=27d3fc76-d913-4d64-8491-5fc0968efe90
# main function in the class
MAIN_CLASS=sahara.edp.spark.SparkWordCount
```

Attention!:

* `INPUT ' test files need to be uploaded to hdfs first.
* The hdfs path specified by OUTPUT cannot exist

Download and upload the jar package to sahara:

```sh
# Upload job binary data
wget 'https://github.com/int32bit/openstack-cheat-sheet/raw/master/sahara/spark-wordcount.jar' -O ${BINARY_FILE}
sahara job-binary-data-create --name "${JOB_NAME}" --file "${BINARY_FILE}"

# Create job binary
DATA_ID=$(sahara job-binary-data-list 2>/dev/null | grep -P -- "\s${JOB_NAME}\s" | awk '{print $2}')
sahara job-binary-create --name "${JOB_NAME}" --url "internal-db://${DATA_ID}"
```

Create a job template:

```sh
# Create job template
BINARY_ID=$(sahara job-binary-list | grep -P -- "\s${JOB_NAME}\s" | awk '{print $2}')
cat >spark-job-template.json <<EOF
{
    "description": "",
    "interface": [],
    "is_protected": false,
    "is_public": true,
    "libs": [],
    "mains": [
        "${BINARY_ID}"
    ],
    "name": "${JOB_NAME}-template",
    "type": "Spark"
}
EOF
sahara job-template-create --json spark-job-template.json
```

Submit job:

```sh
# Submit job
JOB_TEMPLATE_UUID=$(sahara job-template-list 2>/dev/null | grep -P -- "\s${JOB_NAME}-template\s" | awk '{print $2}')
cat >job.json <<EOF
{
    "cluster_id": "${CLUSTER_UUID}",
    "is_protected": false,
    "is_public": true,
    "interface": {},
    "job_configs": {
        "args": [
            "${INPUT}",
            "${OUTPUT}"
        ],
        "configs": {
            "edp.hbase_common_lib": true,
            "edp.java.java_opts": "",
            "edp.java.main_class": "${MAIN_CLASS}",
            "edp.spark.adapt_for_swift": true,
            "edp.substitute_data_source_for_name": true,
            "edp.substitute_data_source_for_uuid": true
        }
    }
}
EOF
sahara job-create --job-template "${JOB_TEMPLATE_UUID}" --json job.json
```

View job Status:

```sh
sahara job-list
```

Full script: [submit-spark-job.sh](sahara/submit-spark-job.sh)

### Other links

1. sahara test.: [https://github.com/openstack/sahara-tests](https://github.com/openstack/sahara-tests)

## manila

## magnum
