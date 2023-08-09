IOC_TOP = /reg/g/pcds/epics/ioc/common/ads-ioc/R0.6.1
IOC_INSTANCE_PATH := $(shell pwd)

# Set PRODUCTION_IOC to 1 to move from a testing to a production IOC:
PRODUCTION_IOC := 0

PROJECT_NAME = lcls-twincat-motion-example
PROJECT_PATH := ../../lcls-plc-example-motion/lcls-plc-example-motion.tsproj
PLC = tc_mot_example

PYTMC_OPTS :=
PREFIX = PLC:TST:MOT

include $(IOC_TOP)/iocBoot/templates/Makefile.base
