This is a fork from https://github.com/yulewang/cloudflare-api-v4-ddns

I realize the Yulewang's code could not run anymore due to change of authorization method i.e from Auth User and Auth Key to only using API key. And he didnt update it. 

I personally use in Task Scheduler in Synology NAS to update every 15 minutes using this command 

bash /volume2/homes/user/cf-v4-ddns.sh -k APIKEY -h www.mysite.com -z mysite.com  -t A -p false
