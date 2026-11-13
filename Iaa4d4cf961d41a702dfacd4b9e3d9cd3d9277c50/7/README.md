# InfoScale CI Results

| Iteration | Setup | Result |
|-----------|-------|--------|
| [local-cfs](local-cfs) | The devstack host is a node of the InfoScale cluster and uses the volumes on the cluster file system. | PASSED |
| [remote-cfs](remote-cfs) | The devstack host is not a node of the InfoScale cluster and mounts the NFS exports of the volumes. | PASSED |
