all: add

add : add.cpp
	g++ -o add add.cpp

dump: add
	objdump -d add.exe > add_numbers.asm

clean:
	del add.exe > add_numbers.asm

run: add.exe
	./add