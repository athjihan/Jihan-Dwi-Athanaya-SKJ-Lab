all:	mul_numbers
mul_numbers:	mul_numbers.cpp
	g++	-o	mul_numbers	mul_numbers.cpp
dump:	mul_numbers
	objdump	-d	mul_numbers.exe	>	mul_numbers.asm
clean:
	rm	-f	mul_numbers	mul_numbers.asm
run:	mul_numbers
	./mul_numbers
