obj-$(CONFIG_MACH_LGE) += devices_lge.o

obj-$(CONFIG_MACH_MSM8926_E2_SPR_US) += board-8926-e2-spr.o board-8926-e2-spr-gpiomux.o
obj-$(CONFIG_MACH_MSM8926_E2_MPCS_US) += board-8926-e2-mpcs.o board-8926-e2-mpcs-gpiomux.o
obj-$(CONFIG_MACH_MSM8926_E2_BELL_CA) += board-8926-e2-bell.o board-8926-e2-bell-gpiomux.o
obj-$(CONFIG_MACH_MSM8926_E2_RGS_CA) += board-8926-e2-rgs.o board-8926-e2-rgs-gpiomux.o
obj-$(CONFIG_MACH_MSM8926_E2_VTR_CA) += board-8926-e2-vtr.o board-8926-e2-vtr-gpiomux.o
obj-$(CONFIG_MACH_MSM8926_E2_VZW) += board-8926-e2-vzw.o board-8926-e2-vzw-gpiomux.o

obj-$(CONFIG_LGE_BOOTLOADER_LOG) += lge_bootloader_log.o
obj-$(CONFIG_LGE_BOOTLOADER_TIME_CHECKER) += lge_bootloader_time_checker.o
obj-$(CONFIG_LGE_PM_CHARGING_TEMP_SCENARIO) += lge_charging_scenario.o

obj-$(CONFIG_MACH_LGE) += lge_kcal_ctrl.o

obj-$(CONFIG_LGE_QFPROM_INTERFACE) += lge_qfprom_access.o

ifdef CONFIG_LGE_PM_BATTERY_PROFILE_DATA
obj-$(CONFIG_LGE_PM_BATTERY_CAPACITY_2100mAh) += bms-batterydata-LGE_LGC_2040mAh_Final.o bms-batterydata-LGE_Tocad_2040mAh_Final.o bms-batterydata-LGE_Hitaci_2040mAh_Final.o bms-batterydata-LGE_BL41A1H_2100mAh_LG_Chem_Final.o bms-batterydata-LGE_BL41A1H_2100mAh_TOCAD_Final.o
endif

CFLAGS_devices_lge.o += -Idrivers/staging/android

