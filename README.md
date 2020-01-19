**This library is not ready for production** 

# raft-wal

This repository provides the raftwal package. 
It uses the [tidwall/wal](https://github.com/tidwall/wal) 
write ahead log library and implements the raft.LogStore from the [hashicorp/raft](https://github.com/hashicorp/raft) project.

It has faster writes, uses less disk space, and consumes up less memory than many of the other raft log implementations.

## Contact

Josh Baker [@tidwall](http://twitter.com/tidwall)

## License

raft-wal source code is available under the MIT [License](/LICENSE).
