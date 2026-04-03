```bash
USR_ID=acbbe7e4-5f7d-4a6a-b4da-074c6862d75a
TNL_AUTH=eyJhIjoiOTc......
TNL_DOM=argo.xxx.com
SYS_HOST=komari.xxx.com
SYS_TOKEN=your_komari_token_value
TGT_IP=cdns.doon.eu.org
TGT_PORT=443
LCL_PORT=8001
N_ID=Modal
TKN_PATH=sub

MODAL_TOKEN_ID=ak-LDWXVTB6......
MODAL_TOKEN_SECRET=as-LDFTB9......
```
### Explanation:

* **`MODAL_TOKEN_ID`** and **`MODAL_TOKEN_SECRET`** should be added as **secret variables** in your **GitHub repository** under "Secrets" (GitHub > Settings > Secrets).

* For the remaining variables (`USR_ID`, `TNL_AUTH`, `TNL_DOM`, `SYS_HOST`, `SYS_TOKEN`, etc.), these should be filled in on the **Modal platform**. You can group these under an environment variable named **`pysecret`** for better organization.

