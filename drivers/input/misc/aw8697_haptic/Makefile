ifeq ($(TARGET_PRODUCT),lmi)
CDEFINES += -DUSE_CONT_F0_CALI
KBUILD_CPPFLAGS += $(CDEFINES)
else ifeq ($(CONFIG_BOARD_UMI),y)
CDEFINES += -DSUPPORT_RELOAD_FW
KBUILD_CPPFLAGS += $(CDEFINES)
endif

obj-$(CONFIG_INPUT_AW8697_HAPTIC)	+= aw8697.o ringbuffer.o
