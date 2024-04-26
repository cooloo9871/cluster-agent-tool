# cluster-agent-tool.sh
## This script will help you retrieve redeployment commands for rancher agents as well as docker run commands to start new agent containers.
```
curl -LO https://github.com/cooloo9871/cluster-agent-tool/raw/main/cluster-agent-tool.sh
```
## retrieve rancher agents yaml
```
bash cluster-agent-tool.sh -u'<RANCHERACCOUNT>' -p'<PASSWD>' -c'<CLUSTER-ID>' -s'<https://RANCHER_URL>'
```

## 完正範例可以參考以下
https://hackmd.io/@7vxmAdNPTmmlYGSRMuvbmw/HyIoXwwnh
