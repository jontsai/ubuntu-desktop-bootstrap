lightweight: bootstrap dev util

install: update bootstrap

update:
	sudo apt-get update

bootstrap: bootstrap.txt
	sudo apt-get -y install `m4 bootstrap.txt`

dev: dev.txt
	sudo apt-get -y install `m4 dev.txt`

media: media.txt
	sudo apt-get -y install `m4 media.txt`

util: util.txt
	sudo apt-get -y install `m4 util.txt`

util-extras: util-extras.txt
	sudo apt-get -y install `m4 util-extras.txt`
