
PROGS  = listdemo treedemo listtest treetest dirlist treesort completion \
	 listdnd filterdemo listtext

SOURCES = ListDemo.hs TreeDemo.hs ListTest.hs TreeTest.hs DirList.hs \
	TreeSort.hs Completion.hs ListDND.hs FilterDemo.hs ListText.hs

all : $(PROGS)

listdemo : ListDemo.hs
	$(HC_RULE)

treedemo : TreeDemo.hs
	$(HC_RULE)

listtest : ListTest.hs
	$(HC_RULE)

treetest : TreeTest.hs
	$(HC_RULE)

dirlist : DirList.hs
	$(HC_RULE)

treesort : TreeSort.hs
	$(HC_RULE)

completion : Completion.hs
	$(HC_RULE)

listdnd : ListDND.hs
	$(HC_RULE)

filterdemo : FilterDemo.hs
	$(HC_RULE)

listtext : ListText.hs
	$(HC_RULE)

HC_RULE = $(HC) --make $< -o $@ $(HCFLAGS)

clean:
	rm -f $(SOURCES:.hs=.hi) $(SOURCES:.hs=.o) $(PROGS)

HC=ghc
