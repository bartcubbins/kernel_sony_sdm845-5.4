# SPDX-License-Identifier: GPL-2.0

ifeq ($(CONFIG_BUILD_ARM64_DT_OVERLAY),y)

# SoMC Tama
dtbo-$(CONFIG_ARCH_SONY_TAMA) += \
	sdm845-tama-akari_generic-overlay.dtbo \
	sdm845-tama-akatsuki_generic-overlay.dtbo \
	sdm845-tama-apollo_generic-overlay.dtbo \
	sdm845-v2-tama-akari_generic-overlay.dtbo \
	sdm845-v2-tama-akatsuki_generic-overlay.dtbo \
	sdm845-v2-tama-apollo_generic-overlay.dtbo \
	sdm845-v2.1-tama-akari_generic-overlay.dtbo \
	sdm845-v2.1-tama-akatsuki_generic-overlay.dtbo \
	sdm845-v2.1-tama-apollo_generic-overlay.dtbo

sdm845-tama-akari_generic-overlay.dtbo-base := ../qcom/sdm845.dtb
sdm845-tama-akatsuki_generic-overlay.dtbo-base := ../qcom/sdm845.dtb
sdm845-tama-apollo_generic-overlay.dtbo-base := ../qcom/sdm845.dtb

sdm845-v2-tama-akari_generic-overlay.dtbo-base := ../qcom/sdm845-v2.dtb
sdm845-v2-tama-akatsuki_generic-overlay.dtbo-base := ../qcom/sdm845-v2.dtb
sdm845-v2-tama-apollo_generic-overlay.dtbo-base := ../qcom/sdm845-v2.dtb

sdm845-v2.1-tama-akari_generic-overlay.dtbo-base := ../qcom/sdm845-v2.1.dtb
sdm845-v2.1-tama-akatsuki_generic-overlay.dtbo-base := ../qcom/sdm845-v2.1.dtb
sdm845-v2.1-tama-apollo_generic-overlay.dtbo-base := ../qcom/sdm845-v2.1.dtb

endif

always		:= $(dtb-y)
subdir-y	:= $(dts-dirs)
clean-files	:= *.dtb *.dtbo
