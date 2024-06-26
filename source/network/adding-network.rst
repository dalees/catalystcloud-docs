.. _adding-networks:

################
Adding a network
################

By default all new Catalyst Cloud projects in the Porirua region (nz-por-1)
are created with a router and network. If you have removed this, or simply
wish to create additional networks, then the following guide will show you
the steps required to achieve this.

.. _creating_networks:

.. include:: _scripts/create-network-dashboard.rst

Following the configuration details this tutorial has advised, you should
now have a network called **private_network** that connects to your
**border-router** and then on to the wider internet. This network can
then be used to host instances which will then be able to connect to the
outside internet through this connection.

|

*************
Using the CLI
*************

You are also able to create a network using the CLI. If you look through
:ref:`this <using-the-command-line-interface>` section of the documentation.
While it talks about setting up your first instance there are steps at the
beginning showing you how to create routers and networks using the CLI.
