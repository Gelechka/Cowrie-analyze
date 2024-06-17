1. Run this command to setup mysql db (remember to config password in **environment** section)
```
docker compose up -d
```
2. User ansible playbook and it's roles to install 4 instances of cowrie honeypot on your vps/vds server. 
You need to configure **default/main.yml** in roles and create your inventory before start.
3. Use jupyter to load **cowrie-analyze.ipynb**