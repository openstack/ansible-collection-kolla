============================
So You Want to Contribute...
============================

For general information on contributing to OpenStack, please check out the
`contributor guide <https://docs.openstack.org/contributors/>`_ to get started.
It covers all the basics that are common to all OpenStack projects: the
accounts you need, the basics of interacting with our Gerrit review system,
how we communicate as a community, etc.

Below will cover the more project specific information you need to get started
with ansible-collection-kolla.

Much of the :kolla-ansible-doc:`Kolla Ansible contributor guide <contributor>`
applies also to this project.

Basics
~~~~~~

The source repository for this project can be found at:

   https://opendev.org/openstack/ansible-collection-kolla

Communication
~~~~~~~~~~~~~

ansible-collection-kolla shares communication channels with Kolla.

IRC Channel
    ``#openstack-kolla`` (`channel logs`_) on `OFTC <http://oftc.net>`_

Weekly Meetings
    On Wednesdays at 15:00 UTC in the IRC channel (`meetings logs`_)

Mailing list (prefix subjects with ``[kolla]``)
    http://lists.openstack.org/pipermail/openstack-discuss/

Meeting Agenda
    https://wiki.openstack.org/wiki/Meetings/Kolla

Whiteboard (etherpad)
    Keeping track of CI gate status, release status, stable backports,
    planning and feature development status.
    https://etherpad.openstack.org/p/KollaWhiteBoard

.. _channel logs: http://eavesdrop.openstack.org/irclogs/%23openstack-kolla/
.. _meetings logs:  http://eavesdrop.openstack.org/meetings/kolla/

Contacting the Core Team
~~~~~~~~~~~~~~~~~~~~~~~~

The Kolla Ansible core team is also the core team for ansible-collection-kolla.

New Feature Planning
~~~~~~~~~~~~~~~~~~~~

New features are discussed via IRC or mailing list (with [kolla] prefix).
ansible-collection-kolla keeps blueprints in `Launchpad <https://blueprints.launchpad.net/ansible-collection-kolla>`__.
Specs are welcome but not strictly required.

Task Tracking
~~~~~~~~~~~~~

Kolla project tracks tasks in `Launchpad <https://bugs.launchpad.net/ansible-collection-kolla>`__.
Note this is the same place as for bugs.

If you're looking for some smaller, easier work item to pick up and get started
on, search for the 'low-hanging-fruit' tag.

A more lightweight task tracking is done via etherpad - `Whiteboard <https://etherpad.openstack.org/p/KollaWhiteBoard>`__.

Reporting a Bug
~~~~~~~~~~~~~~~

You found an issue and want to make sure we are aware of it? You can do so
on `Launchpad <https://bugs.launchpad.net/ansible-collection-kolla>`__.
Note this is the same place as for tasks.

Getting Your Patch Merged
~~~~~~~~~~~~~~~~~~~~~~~~~

Most changes proposed to ansible-collection-kolla require two +2 votes from
core reviewers before +W. A release note is required on most changes as well.
Release notes policy is described in :kolla-ansible-doc:`Kolla Ansible
contributor guide <contributor/release-notes>`.

Significant changes should have documentation and testing provided with them.

Project Team Lead Duties
~~~~~~~~~~~~~~~~~~~~~~~~

All common PTL duties are enumerated in the `PTL guide
<https://docs.openstack.org/project-team-guide/ptl.html>`_.
Kolla Ansible-specific PTL duties are listed in :kolla-ansible-doc:`Kolla
Ansible PTL guide <contributor/ptl-guide>`.
