#update at 6/19/2017 

update with new shadowsocksR 4.5.0

#update at 6/5/2017 

update with new shadowsocksR 4.4.0


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
