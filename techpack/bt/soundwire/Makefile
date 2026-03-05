ccflags-y += -I$(srctree)/techpack/bt/include
ccflags-y += \
	-I$(srctree)/techpack/audio/include\
	-I$(srctree)/techpack/bt/btfmcodec/include
bt_fm_swr-objs := btfm_swr.o btfm_swr_hw_interface.o btfm_swr_slave.o
obj-$(CONFIG_BTFM_SWR) += bt_fm_swr.o
