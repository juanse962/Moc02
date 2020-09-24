TARGET=main.cc

default: app-icc app-gcc

app-icc : ${TARGET}
	icc -o "$@" "$<"

app-gcc : ${TARGET}
	g++ -o "$@" "$<"

clean :
	rm app-icc app-gcc

