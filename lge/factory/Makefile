EXTRA_CFLAGS += -Ilge/include
obj-$(CONFIG_LGE_SUPPORT_RAPI) += LG_rapi_client.o

obj-$(CONFIG_LGE_DIAGTEST) += lg_diag_testmode.o
obj-$(CONFIG_LGE_DIAGTEST) += lg_fw_diag_class.o
obj-$(CONFIG_LGE_DIAGTEST) += lg_fw_diag_communication.o
# add lg_diag_event_log.c for key logging in diag testmode test 2010-07-10
obj-$(CONFIG_LGE_DIAGTEST) += lg_diag_event_log.o
# add lg_diag_keypress.c for UTS test by younchan.kim 2010-06-11
obj-$(CONFIG_LGE_DIAGTEST) += lg_diag_keypress.o 
# add lg_diag_screen_shot.c for UTS test by minjong.gong 2010-06-13
obj-$(CONFIG_LGE_DIAGTEST) += lg_diag_screen_shot.o
obj-$(CONFIG_LGE_DIAGTEST) += lg_diag_unifiedmsgtool.o
#obj-$(CONFIG_LGE_DIAGTEST) += lg_fw_diag_mtc.o
#obj-$(CONFIG_LGE_DIAGTEST) += lg_diag_wifi.o

obj-$(CONFIG_LGE_DIAG_KEYPRESS) += lg_diag_keypress.o
obj-$(CONFIG_LGE_DIAG_SCREENSHOT) += lg_diag_screen_shot.o
obj-$(CONFIG_LGE_DIAG_UDM) += lg_diag_udm.o
obj-$(CONFIG_LGE_FACTORY) += userDataBackUpDiag.o
obj-$(CONFIG_LGE_FACTORY) += lge_diag_eri.o
obj-$(CONFIG_LGE_FACTORY) += lg_diag_dload.o

obj-$(CONFIG_LGE_ERROR_HANDLER) += lge_test.o
