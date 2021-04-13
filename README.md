# livestream_km
OBS Setting 
rtmp:// ( your server ):1935 /live/ 

sudo openssl req -x509 -nodes -days 365 -newkey rsa:2048 -keyout output.key -out output.crt


# client

rtmp:// ( your server ):1935 /live/ (yourkey by obs )

vlc player  url test https://(your server)/hls/(yourkey).m3u8

copy and edit index.html to www
