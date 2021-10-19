all:	compile
	g++ *.o -o main -lthrift -pthread

compile:
	g++ -c main.cpp match_server/*.cpp save_client/*.cpp

clean:
	rm -f *.o main
