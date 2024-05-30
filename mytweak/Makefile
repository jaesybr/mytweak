TARGET := iphone:clang:latest:7.0
INSTALL_TARGET_PROCESSES = 1


include $(THEOS)/makefiles/common.mk

TWEAK_NAME = mytweak

mytweak_FILES = Tweak.x
mytweak_CFLAGS = -fobjc-arc

include $(THEOS_MAKE_PATH)/tweak.mk
