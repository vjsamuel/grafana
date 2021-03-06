---
page_title: Grafana Installation
page_description: Install guide for Grafana
page_keywords: grafana, installation, documentation
---

# Installation

Grafana is easily installed via a Debian/Ubuntu package (.deb), via
Redhat/Centos package (.rpm) or manually via a tarball that contains all
required files and binaries. If you can't find a package or binary for
your platform, you might be able to build one yourself. Read the [build
from source](../project/building_from_source) instructions for more
information.

## Platforms
- [Installing on Debian / Ubuntu](installation/debian.md)
- [Installing on RPM-based Linux (CentOS, Fedora, OpenSuse, RedHat)](installation/rpm.md)
- [Installing on Mac OS X](installation/mac.md)
- [Installing on Windows](installation/windows.md)
- [Installing on Docker](installation/docker.md)
- [Installing using Provisioning (Chef, Puppet, Salt, Ansible, etc)](installation/provisioning.md)
- [Nightly Builds](http://grafana.org/download/builds.html)

## Configuration

The back-end web server has a number of configuration options. Go the
[Configuration](/installation/configuration) page for details on all
those options.

## Data sources guides

- [Graphite](datasources/graphite.md)
- [Elasticsearch](datasources/elasticsearch.md)
- [InfluxDB](datasources/influxdb.md)
- [OpenTSDB](datasources/opentsdb.md)

