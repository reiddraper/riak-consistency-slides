!SLIDE bullets

# Riak #

* Basho
* distributed database
* open source
* highly available

!SLIDE bullets

.notes put comic here

* erlang
* dynamo implementation
* HTTP REST / PB API

!SLIDE bullets

# distributed for #

* availability
* durability
* throughput
* capacity

!SLIDE bullets

# Data Model #

* key/value
* secondary indexes
* mapreduce
* large files
* links

!SLIDE bullets

* N replicas!

!SLIDE center

![riak ring](riak-ring.png)

!SLIDE bullets

* no master
* any node serves any request

!SLIDE commandline

    $bin/riak-admin join dev1@127.0.0.1
    Sent join request to dev1@127.0.0.1

!SLIDE commandline
    $bin/riak-admin member_status
    ================================= Membership ==================================
    Status     Ring    Pending    Node
    -------------------------------------------------------------------------------
    valid      50.0%      --      'dev1@127.0.0.1'
    valid      50.0%      --      'dev2@127.0.0.1'
    -------------------------------------------------------------------------------
    Valid:2 / Leaving:0 / Exiting:0 / Joining:0 / Down:0
