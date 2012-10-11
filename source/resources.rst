############
Resources
############

There are a number of related projects and links of interest.

Projects
--------
 - `Rackspace Private Cloud <http://www.rackspace.com/cloud/private/>`_: the original source of the cookbooks and a great way to kick the tires on OpenStack. Their 'Alamo' distribution is quite useful and overlaps significantly with the Chef for OpenStack project. A great place to get started with trying OpenStack.
  - `Rackspace Private Cloud Software Documentation <http://www.rackspace.com/knowledge_center/getting-started/rackspace-private-cloud>`_ has lots of great debugging and troubleshooting information, and most of it is quite relevant to **Chef for OpenStack**.
  - `github.com/rcbops <http://github.com/rcbops/>`_ are the repos used by Rackspace for the building and deployment of their private clouds, testing and Alamo tooling.
  - `github.com/rcbops/rcbops-cookbooks <http://github.com/rcbops/chef-cookbooks>`_ is similar to the ``chef-openstack-repo`` used to deploy OpenStack and the source of many roles.
  - `github.com/rcbops-cookbooks/ <https://github.com/rcbops-cookbooks/>`_ are the cookbook repositories for Rackspace Private Cloud. Chef for OpenStack is a parallel fork of these, with patches going both ways.
  .. note::
    **Chef for OpenStack** specifically removes Rackspace's operational additions like monitoring and logging because these may conflict with your deployment choices. If you want to use ``collectd`` and ``rsyslog`` for your deployment, please feel free to track the work being done in the Rackspace repositories.
 - `Librarian <http://github.com/applicationsonline/librarian>`_: For managing Chef-based cookbook repositories.
 - `Spiceweasel <http://github.com/mattray/spiceweasel>`_: Command-line tool for loading Chef infrastructure.


Links
-----
 - OpenStack's `docs.openstack.org <http://docs.openstack.org>`_
 - Austin Page's `Chef/OpenStack presentation <http://prezi.com/cjoebupahw3o/chef/>`_
 - Ken Pepple's excellent architectural overviews of `Essex <http://ken.pepple.info/openstack/2012/02/21/revisit-openstack-architecture-diablo/>`_ and `Folsom <http://ken.pepple.info/openstack/2012/09/25/openstack-folsom-architecture/>`_
