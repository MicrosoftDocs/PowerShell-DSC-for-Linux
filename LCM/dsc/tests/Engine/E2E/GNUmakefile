
TESTTOP = ../..

DSCTOP = ../../..

TOP = ../../../..


include $(TOP)/config.mak

CXXUNITTEST = NITSDSCtestEngineE2E


SOURCES= test_EngineE2E.cpp

INCLUDES= \
	$(OMI) \
	$(OMI)/common \
	$(OMI)/common/inc \
	$(TOP)/codec/common \
	$(OMI)/nits/base \
	$(DSCTOP)/common/inc \
	$(DSCTOP)/engine/EngineHelper \
	$(DSCTOP)/engine/ModuleLoader/ModuleLibrary \
	$(DSCTOP)/engine/ca/CAInfrastructure \
	$(DSCTOP)/engine/lcm \
	$(TESTTOP)/common \

DEFINES= TEST_BUILD

LIBRARIES = mi  $(UNITTESTLIBS) pal EngineHelper

include $(OMI)/mak/rules.mak

