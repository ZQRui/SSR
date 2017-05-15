#update at 5/15/2017 


Suggest use docker compose to custmize parameters

Sample of docker-compose file:
shadowsocksr:
image: burndown/shadowsockrs
ports:

- "80:58388"

environment:

- PASSWORD=Killgfw!
- OBFS_PARAM=www.xxxx.com

restart: always
