# supersync
基于IBM Hyperledger区块链技术的通用数据同步框架，可用于多点数据库的同步，以及其他任何需要从零开始完整复制数据的分布式系统
以数据库为例，需要同步的节点从区块链上获取同步的数据，并执行同步过程，由于区块链保持了完整的同步数据前后关系，并且最终一致，
因此此方法可以用于局域网，广域网中的任意多台机器之间的数据同步，并且任意机器可以从头开始恢复完整的数据。
