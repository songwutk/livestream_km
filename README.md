# livestream_km
OBS Setting 
rtmp:// ( your server ):1935 /live/ 

# client
rtmp:// ( your server ):1935 /live/ (yourkey by obs )


Let's encrypt cert

https://certbot.eff.org/docs/using.html#manual


certbot certonly --cert-name example.com -d example.com


select 2 
type www


cat  /etc/letsencrypt/live/ (example.com) /fullchain.pem >custom.crt

cat  /etc/letsencrypt/live/ (example.com) /privkey.pem >custom.key


vlc player  url test https://(your server)/hls/(yourkey).m3u8
