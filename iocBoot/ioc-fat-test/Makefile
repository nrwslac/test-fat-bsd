IOC_TOP = /reg/g/pcds/epics/ioc/common/ads-ioc/R0.6.0

IOC_INSTANCE_PATH := $(shell pwd)

# Set PRODUCTION_IOC to 1 to move from a testing to a production IOC:
PRODUCTION_IOC := 1

PROJECT_NAME := test-fat-bsd 
PROJECT_PATH := ../../test-fat-bsd/test-fat-bsd.tsproj
PLC := fat_test 

PYTMC_OPTS := 
PREFIX := PLC:FAT:OPTICS

include $(IOC_TOP)/iocBoot/templates/Makefile.base
