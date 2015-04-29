all:

upload:
	rsync -a -v --rsh=ssh --exclude='**/.svn' src/* hostgator:domains/humanity/public_html/
