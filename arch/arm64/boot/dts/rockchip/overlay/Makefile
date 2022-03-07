# SPDX-License-Identifier: GPL-2.0
dtbo-$(CONFIG_ARCH_ROCKCHIP) += \
	rockchip-enable-edp.dtbo \
	rockchip-i2c7.dtbo \
	rockchip-i2c8.dtbo \
	rockchip-pcie-gen2.dtbo \
	rockchip-rk3399-oc-20.dtbo \
	rockchip-rk3399-oc-22.dtbo \
	rockchip-rpi-7inch-lcd.dtbo \
	rockchip-rpi-cam-imx219.dtbo \
	rockchip-rpi-cam-ov5647.dtbo \
	rockchip-spi-jedec-nor.dtbo \
	rockchip-spi-spidev.dtbo \
	rockchip-uart4.dtbo \
	rockchip-w1-gpio.dtbo 

scr-$(CONFIG_ARCH_ROCKCHIP) += \
       rockchip-fixup.scr

dtbotxt-$(CONFIG_ARCH_ROCKCHIP) += \
       README.rockchip-overlays

targets += $(dtbo-y) $(scr-y) $(dtbotxt-y)

always         := $(dtbo-y) $(scr-y) $(dtbotxt-y)
clean-files    := *.dtbo *.scr


