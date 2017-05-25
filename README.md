algovpn.bootstrap
=========

Bootstrap a newly provisioned host.

Role Variables
--------------

Used to bootstrap Ubuntu and FreeBSD hosts for deployment via ansible.

Registered Variables
--------------------
Variables available for use after this role has been included.

| Name           | Type | Description                        |
| -------------- | ------------- | -----------------------------------|
| `remote_host` | str | The IP Address of the deployed instance. (useful when using deploy_to)|

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: algovpn.bootstrap }

License
-------

MIT

Author Information
------------------

AlgoVPN