# Overlays for the CONFIG_SOC_THEAD platform

dtbo-$(CONFIG_SOC_THEAD) += meles-wifibt-external-antenna.dtbo

targets += dtbs dtbs_install
targets += $(dtbo-y)

always-y	:= $(dtbo-y)
clean-files	:= *.dtbo
