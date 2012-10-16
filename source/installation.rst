############
Installation
############

* Make sure you've read and understand the :doc:`prerequisites for installation </prerequisites>`.
* Check out the `OpenStack Chef Repository from GitHub <http://github.com/opscode/openstack-chef-repo>`_.
* Follow the Librarian Chef instructions to download all of the appropriate cookbooks.
* Edit your environment that you will be using.
* Upload all the roles, environments, cookbooks and data bags as necessary (Spiceweasel).
* On the appropriate nodes, apply the proper roles to deploy.
* Converge the nodes, controller first, then compute.
* Log in to the Horizon Dashboard and either install or download your private key.
* Create a test node.

Please refer to the :doc:`Example Deployment </example>` for a detailed reference implementation.

.. toctree::

   installation/openstack-chef-repo
   installation/cookbooks
   installation/cookbooks/nova
   installation/cookbooks/glance
   installation/cookbooks/swift
   installation/cookbooks/keystone
   installation/cookbooks/horizon
   installation/cookbooks/osops-utils
   installation/environment
   installation/roles
