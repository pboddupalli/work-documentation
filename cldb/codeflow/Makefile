default:

disk-balancer cldb cldb-classes topology container-delete RoleBalancer:
	dot -Tpdf $@.dot > $@.pdf
FileServerWorkAllocator:
	dot -Tpdf $@.dot > $@.pdf

all: disk-balancer cldb cldb-classes topology container-delete RoleBalancer FileServerWorkAllocator

distclean:
	rm -rf *.pdf

squeakyclean: distclean
	rm -rf *~
