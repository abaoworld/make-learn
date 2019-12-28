# 这个规则表示所有的 .o文件都是依赖与相应的.c文件的
main:main.o mytool1.o mytool2.o 

	gcc -o $@ $^ 

.c.o: 

	gcc -c $< 