# SPDX-License-Identifier: GPL-2.0-only
################################################################################
#
# aQuantia Ethernet Controller AQtion Linux Driver
# Copyright(c) 2014-2017 aQuantia Corporation.
#
# Contact Information: <rdc-drv@aquantia.com>
# aQuantia Corporation, 105 E. Tasman Dr. San Jose, CA 95134, USA
#
################################################################################

#
# Makefile for the AQtion(tm) Ethernet driver
#

obj-$(CONFIG_AQTION) += atlantic.o

atlantic-objs := aq_main.o \
	aq_nic.o \
	aq_pci_func.o \
	aq_vec.o \
	aq_ring.o \
	aq_hw_utils.o \
	aq_ethtool.o \
	aq_drvinfo.o \
	aq_filters.o \
	hw_atl/hw_atl_a0.o \
	hw_atl/hw_atl_b0.o \
	hw_atl/hw_atl_utils.o \
	hw_atl/hw_atl_utils_fw2x.o \
	hw_atl/hw_atl_llh.o
