.. index::
  Hardware

========================
Hardware Requirements
========================

There are recommendations for hardware configuration in the `OpenStack Install and Deploy documentation <>`_ and in the `Rackspace Private Cloud Getting Started Guide <>`_, **Chef for OpenStack** does not have any additional requirements. For best results, physical hardware is recommended.

Nova
------
* Controller node (MySQL, RabbitMQ, Glance, Keystone, Nova API/scheduler/volume, Horizon)
   * Processor: 64-bit x86 with multiple cores
   * Memory: 16 GB RAM
   * Disk space: 144 GB (SATA or SAS or SSD)
   * Volume storage: two disks with 2 TB (SATA) for volumes attached to the compute nodes
   * Network: one 1 GB Network Interface Card (NIC) Two NICS are recommended but not required.
* Compute nodes (runs Nova compute/network)
   * Processor: 64-bit x86 with multiple cores
   * Memory: 32 GB RAM
   * Disk space: 30 GB (SATA)
   * Network: two 1 GB NICs
   * Specifically for virtualization on certain hypervisors on the node or nodes running nova-compute, you need a x86 machine with an AMD processor with SVM extensions (also called AMD-V) or an Intel processor with VT (virtualization technology) extensions. For LXC, the VT extensions are not required.
   * The default CPU overcommit is set at 16:1 VCPUs to cores and memory is set to 1.5:1. You may need to adjust your settings accordingly.

Swift
------

.. note::
**Chef for OpenStack** has not added Swift yet, but it will be added soon from the Rackspace `rcbops-cookbooks/swift repository <https://github.com/rcbops-cookbooks/swift>`_ and appropriate hardware recommendations will be made.

