# SSSIHL_roadshow

#include<stdio.h>
int main(){
    int sum = 0, i, n;
    printf("Enter the value of n = ");
    scanf("%d",&n);
    for(i = 1;i <= n;i++){
       sum = sum + i;
    }
    printf("The Sum of numbers from 1 to %d is %d\n",n,sum);
    return 0;
}

./a.out

riscv64-unknown-elf-gcc -O1 -mabi=lp64 -march=rv64i -o hello.o hello.c

riscv64-unknown-elf-objdump -d hello.o

# Change directory to openlane flow directory
cd Desktop/work/tools/openlane_working_dir/openlane
