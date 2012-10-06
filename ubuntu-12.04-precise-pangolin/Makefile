install: update bootstrap

update:
	sudo apt-get update

all: update bootstrap dev server util audio graphics media

bootstrap: bootstrap.txt
	sudo apt-get -y install `m4 bootstrap.txt`

dependencies: dependencies.txt
	sudo apt-get -y install `grep -v "^#" dependencies.txt | m4`

app: app.txt
	sudo apt-get -y install `m4 app.txt`	

audio: audio.txt
	sudo apt-get -y install `m4 audio.txt`

dev: dev.txt
	sudo apt-get -y install `m4 dev.txt`

graphics: graphics.txt
	sudo apt-get -y install `m4 graphics.txt`

media: media.txt
	sudo apt-get -y install `m4 media.txt`

net: net.txt
	sudo apt-get -y install `m4 net.txt`

server: server.txt
	sudo apt-get -y install `m4 server.txt`

util: util.txt
	sudo apt-get -y install `m4 util.txt`
