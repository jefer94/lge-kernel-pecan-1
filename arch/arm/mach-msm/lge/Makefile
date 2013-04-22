subdir-ccflags-$(CONFIG_ARCH_MSM) += -Iarch/arm/mach-msm

-include $(src)/Makefile.board

obj-$(CONFIG_MACH_LGE) += devices_lge.o

obj-$(CONFIG_LGE_HEADSET_2GPIO) += lge_gpio_h2w.o
obj-$(CONFIG_LGE_SWITCH_GPIO) += lge_gpio_switch.o
obj-$(CONFIG_LGE_HANDLE_PANIC) += lge_handle_panic.o
obj-$(CONFIG_LGE_BLUE_ERROR_HANDLER) += lge_errorhandler.o
obj-$(CONFIG_LGE_PROC_COMM) += lge_proc_comm.o
obj-$(CONFIG_LGE_SUPPORT_ERS) += lge_ers.o
obj-$(CONFIG_LGE_MTD_DIRECT_ACCESS) += lge_mtd_direct_access.o  #need this rather than emmc direct access, maybe this was problem on previous builds?

obj-$(CONFIG_LGE_SUPPORT_AT_CMD) += lge_ats.o
obj-$(CONFIG_LGE_SUPPORT_AT_CMD) += lge_ats_cmd.o
obj-$(CONFIG_LGE_SUPPORT_AT_CMD) += lge_ats_eta.o
obj-$(CONFIG_LGE_SUPPORT_AT_CMD) += lge_ats_mmc.o
obj-$(CONFIG_LGE_SUPPORT_AT_CMD) += lge_ats_event_log.o
obj-$(CONFIG_LGE_ATS_UEVENT_DEVICE) += lge_ats_uevent.o
obj-$(CONFIG_LGE_ATS_INPUT_DEVICE) += lge_ats_input.o
obj-$(CONFIG_LGE_SUPPORT_AT_CMD) += lge_ats_flex.o # LGE_CHANGE [irene.park@lge.com] 2010-06-04 - to get flex value from ARM9
obj-$(CONFIG_LGE_PWRSINK) += lge_pwrsink.o

obj-$(CONFIG_LGE_BOOT_MODE) += lge_boot_mode.o
