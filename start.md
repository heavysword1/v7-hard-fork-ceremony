# Start Nodes

# 10. Build Genesis TX
```
libra genesis --chain MAINNET build -o 0LNetworkCommunity -n v7-hard-fork-ceremony -l -j $HOME/.libra/state_epoch_79_ver_33217173.795d.json --drop-list $HOME/.libra/drop_list.json
```

# 11. Start node

```
libra node
```
