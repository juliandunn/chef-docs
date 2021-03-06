.. The contents of this file are included in multiple topics.
.. This file should not be changed in a way that hinders its ability to appear in multiple documentation sets. 


On the |chef server| machine create the |organization pem| from the command line using |chef server ctl|. Run the following command:

.. code-block:: bash

   $ chef-server-ctl org-create ORG_NAME ORG_FULL_NAME -f FILE_NAME

where

* |name_rules org| For example: ``chef``
* |name_rules org_full| For example: ``"Chef Software, Inc."``
* ``-f FILE_NAME``: |key organization_create| For example: ``/tmp/chef.key``.

For example, an organization named ``chef``, with a full name of ``Chef Software, Inc.``, and with the |organization pem| file saved to ``/tmp/chef.key``:

.. code-block:: bash

   $ chef-server-ctl org-create chef "Chef Software, Inc." -f /tmp/chef.key
