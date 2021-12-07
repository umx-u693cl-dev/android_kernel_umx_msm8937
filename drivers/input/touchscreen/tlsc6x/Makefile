#
# Makefile for the input core drivers.
#

# Each configuration option enables a list of files.
ccflags-y += -I$(srctree)/drivers/input/touchscreen/
ccflags-y += -I$(srctree)/drivers/input/touchscreen/tlsc6x/firmware_config/firmware_alps
tlsc6x_ts-objs := tlsc6x_main.o
tlsc6x_ts-objs += tlsc6x_comp.o
obj-$(CONFIG_TOUCHSCREEN_TLSC6X)  += tlsc6x_ts.o
