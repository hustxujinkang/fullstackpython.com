run:
	cp static-html/* ..
	cp redirects/* ..
	pelican -t theme -s settings.py -o .. content
	cp ../pages/* ../
	cp -R ../theme/img ..
	rm -rf ../pages/

init:
	pip install -r requirements.txt
