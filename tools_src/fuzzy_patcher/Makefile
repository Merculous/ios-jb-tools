OPT_PATH=/sw/bin
BOOST=/usr/lib/x86_64-linux-gnu
#GCC_45=$(OPT_PATH)/g++-fsf-4.5
all:
	g++ -m64 -o fuzzy_patcher  main.cpp -I$(BOOST) $(BOOST)/libboost_program_options.a $(BOOST)/libboost_iostreams.a
