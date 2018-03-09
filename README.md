## 使用
直接运行 python create.py
将生成20组区块组成的区块链

## Block类
区块生成类
index：区块序号, timestamp：生成区块的时间戳, data：该区块携带参数, previous_hash：上一个区块的哈希值

## 涉及到的方法
next_block：根据上一个区块的哈希值，取下一个区块字典
create_genesis_block：创建一个创世区块