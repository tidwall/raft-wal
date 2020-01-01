# raft-wal

This repository provides the raftwal package. 
The package uses the [tidwall/wal](https://github.com/tidwall/wal) 
write ahead log package and implements the raft.LogStore from the [hashicorp/raft](https://github.com/hashicorp/raft) project.

It has faster writes, uses less disk space, and consumes up less memory than many of the other raft log implementations.

## Contact

Josh Baker [@tidwall](http://twitter.com/tidwall)

## License

raft-wal source code is available under the MIT [License](/LICENSE).
