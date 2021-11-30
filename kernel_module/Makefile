PWD = $(shell pwd)
KERNEL_SRC = /usr/src/linux-headers-4.4.0-142-generic/

obj-m := test.o
module-objs := test.o

all:
	$(MAKE) -C $(KERNEL_SRC) M=$(PWD) modules

clean:
	rm *.ko *.o
