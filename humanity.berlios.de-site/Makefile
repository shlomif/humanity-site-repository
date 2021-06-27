all:

upload:
	rsync -a -v --rsh=ssh --exclude='**/.svn' src/* hostgator:domains/humanity/public_html/

test:
	screenplay-text-to-xhtml5 -o /tmp/usrbinperlf.xhtml src/usr-bin-perl/total-screenplay.screenplay-text.txt

