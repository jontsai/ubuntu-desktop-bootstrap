lightweight: bootstrap dev util

install: update bootstrap

update:
	sudo apt-get update

bootstrap: bootstrap.txt
	sudo apt-get -y install `grep -v ^# bootstrap.txt | m4`

dev: dev.txt
	sudo apt-get -y install `grep -v ^# dev.txt | m4`

media: media.txt
	sudo apt-get -y install `grep -v ^# media.txt | m4`

webcam: webcam.txt
	sudo apt-get -y install `grep -v ^# webcam.txt | m4`

util: util.txt
	sudo apt-get -y install `grep -v ^# util.txt | m4`

util-extras: util-extras.txt
	sudo apt-get -y install `grep -v ^# util-extras.txt | m4`
