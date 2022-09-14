start:
	bundle exec jekyll serve --baseurl '/hpc/assets' --port 4003 &> ../jekyll.log &

stop:
	- pkill --echo --count --full jekyll

restart: stop start

serve: start
