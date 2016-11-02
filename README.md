# SUPER - SPOON
Super spoon is a collection of scripts which can set up couchbase, mongodb,
cassandra on many maschines and distrub them.

# Nice to know
- machines have to be in same network
- tested with openstack and 4x Ubuntu 14.04 VMs
- scripts was run on arch linux, but should also work on ubuntu or other
linux distros

# How to use
1. set up maschine/vm
2. set up script
3. start script
```bash
git clone https://github.com/Ehrax/super-spoon.git
cd super-spoon
```
How to use each script is documented in their directories.

# TODO
- [x] Couchbase script
- [x] Cassandra script
- [ ] Mongodb script
- [ ] diffrent network setup
- [ ] cassandra, more seed nodes
- [ ] replication factor, chouchbase and cassandra
- [ ] memory size and heap for cassandra
- [ ] flush script for couchbase, mongodb, cassandra
- [ ] Mongodb Parameter, specify storage engine
