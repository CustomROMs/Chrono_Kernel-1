obj-$(CONFIG_PHONET) += phonet.o pn_pep.o

phonet-y := \
	pn_dev.o \
	pn_netlink.o \
	socket.o \
	datagram.o \
	sysctl.o \
	af_phonet.o

pn_pep-y := pep.o pep-gprs.o

include $(srctree)/scripts/Makefile_build.thumb2
