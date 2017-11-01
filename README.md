# oracle-xe-11g

In [DockerHub](https://hub.docker.com) there are available two containers with an Oracle XE 11g database for
Teamcenter:

* [oracle-xe-4-tc](https://hub.docker.com/r/jagasanchez/oracle-xe-4-tc/)
* [oracle-xe-tc](https://hub.docker.com/r/jagasanchez/oracle-xe-tc/)

Both are based on [oracle-xe-11g](https://hub.docker.com/r/wnameless/oracle-xe-11g/)

The difference between them is that `oracle-xe-4-tc` is an empty database with created tablespaces required
by Teamcenter. It is suitable for a Teamcenter installation.
In the other hand, `oracle-xe-tc` is a populated database after having installed Teamcenter. It is suitable
to make it work with a containerized Teamcenter Corporate Server.

Use the container `oracle-xe-4-tc` if you need a database prepared in order to make a Teamcenter installation.
Use `oracle-xe-tc` with an already installed Teamcenter Corporate Server.
