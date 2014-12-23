default:

disk-balancer:
	dot -Tpdf disk-balancer.dot > disk-balancer.pdf

cldb:
	dot -Tpdf cldb.dot > cldb.pdf

cldb-classes:
	dot -Tpdf cldb-classes.dot > cldb-classes.pdf

all: disk-balancer cldb cldb-classes

distclean:
	rm -rf *.pdf

squeakyclean: distclean
	rm -rf *~
