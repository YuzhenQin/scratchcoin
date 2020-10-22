# sccoinnet
空间sccoinnet储存了网络的基本信息，格式如下  
{  
"bootnodes":["一个bootnode","另一个bootnode"],  
"peercount":在线的节点数,  
"height":区块高度,  
"forks":["一条链","另一条链"],  
"size":打包交易的最高容量,  
}  
# sccoinboardcast  
空间sccoinboardcast存储已广播的交易和区块，当交易被打包或区块被同步后被移出，格式如下  
{  
"transaction":[{一个trx},{另一个trx}],  
"block":[{一个block},{另一个block}],  
"synced":[{已被确认的区块},{已被确认的区块}]  
}  
