### money-tree
---
https://github.com/mhanne/money-tree

https://github.com/GemHQ/money-tree

https://github.com/wink/money-tree

```rb
@master = MoneyTree::Master.new
@master.seed
@master = MoneyTree::Master.new seed_hex: "xxx"
@master.seed
@master.index
@master.depth
@master.to_identifier
@master.to_fingerprint
@master.to_address
@master.private_key.to_hex
@master.private_key.to_wif
@master.public_key.to_hex
@master.chain_code_hex
@master.to_serialized_hex(:private)
@master.to_serialized_address(:private)
@master.to_serialized_hex
@master.t0_serialized_address

@node = @master.node_for_path "m/0/3"
@node.index
@node.depth
@node.to_serialized_address(:private)
@node.to_serialized_address

@node.to_serialized_address(:private)
@node.to_serialized_address

@node = MoneyTree::Node.from_serialized_address "xxx"

@node = @master.node_for_path("M/0/3")
@node.to_serialized_address
@node.to_serialized_address(:private)

@node = MoneyTree::Node.from_serialized_address("xxx")
@node.to_serialized_address
@node.to_serialized_address(:private)
```

```sh
bundle
gem install money-tree
```

```
```


