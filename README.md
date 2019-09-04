# docker-flexget
Docker image Flexget. Flexget is a tool that works from the terminal that allows downloading torrents through RSS.

<p align="center"><img src="/images/logo.png"></p>

<h3>Use it in Docker</h3>

<p>docker run -d --name=flexget -p 5050:5050 -e TORRENT_PLUGIN=transmission -e FG_WEBUI_PASSWD=mypasswd -v config:/config javi98/flexget</p>
