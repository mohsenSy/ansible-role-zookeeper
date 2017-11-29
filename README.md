ZooKeeper
=========

This role is used to install ZooKeeper.

Requirements
------------

No special requirements.

Role Variables
--------------

* ZOOKEEPER_VERSION: The version of zookeeper to install (default is 3.4.10)
* ZOOKEEPER_USER: The user to run zookeeper daemon as it. (default zookeeper)
* ZOOKEEPER_DATA_DIR: The directory used to save zookeeper data to it (default /tmp/zookeeper)
* ZOOKEEPER_TICK_TIME: The number of milliseconds of each tick (default is 2000)
* ZOOKEEPER_SYNC_LIMIT: The number of ticks that can pass between sending a request and getting an acknowledgement. (default is 5)
* ZOOKEEPER_PORT: The port that zookeeper will listen to it (default 2181)
* ZOOKEEPER_BIND_IP: The IP address that zookeeper will bind to it (default is 127.0.0.1)


Dependencies
------------

* mohsenSy.java

Example Playbook
----------------

    - hosts: servers
      roles:
         - mohsenSy.zookeeper

License
-------

BSD

Author Information
------------------

If you have any question please contact me on

[twitter](https://twitter.com/mouhsen_ibrahim)

[linkedin](https://linkedin.com/in/mohsen-ibrahim-670b13112/)

email mohsen47@hotmail.co.uk
