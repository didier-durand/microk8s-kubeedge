# KubeEdge on MicroK8s

This repo is WIP (Work In Progress) as of now

Its aim is to provide a fully automated install of the KubeEdge components on 2 separate Google Cloud Engine (GCE) instances: 1 for CloudCore 
and for EdgeCore.

Currently working on a solution for [issue #2362](https://github.com/kubeedge/kubeedge/issues/2362)

If you wanna dig into the details:

1. Structured log of failing execution is [here](https://github.com/didier-durand/microk8s-kubeedge/runs/1442253504)
2. Raw log of failing execution is [here](https://pipelines.actions.githubusercontent.com/XyrBlDsDH2tsKV68Y7WzMHHgNi2B991enTUDwAA1mTH8Oqh49s/_apis/pipelines/1/runs/30/signedlogcontent/3?urlExpires=2020-11-23T13%3A37%3A07.0843269Z&urlSigningMethod=HMACV1&urlSignature=qBTOqjJg6TbfsJwK89jdIn%2FAE%2FFbPjehfcrzL2h%2B1ck%3D)
3. Shell script generating those logs is [microk8s-kubeedge.sh](https://github.com/didier-durand/microk8s-kubeedge/blob/main/sh/microk8s-kubeedge.sh)

For further details, please, check the official Git [repository of KubeEdge](https://github.com/kubeedge/kubeedge)

Feel free to fork and reuse this repo already. But, rather come back until we get it to work to obtain complete version.
