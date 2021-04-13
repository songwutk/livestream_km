# livestream_km
OBS Setting 
rtmp:// ( your server ):1935 /live/ 

# client
rtmp:// ( your server ):1935 /live/ (yourkey by obs )


sudo openssl req -x509 -nodes -days 365 -newkey rsa:2048 -keyout output.key -out output.crt

vlc player  url test https://(your server)/hls/(yourkey).m3u8
