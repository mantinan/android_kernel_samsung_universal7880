# SPDX-License-Identifier: GPL-2.0
dtb-y += \
	exynos7880-a5y17lte_eur_open_00.dtb \
	exynos7880-a5y17lte_eur_open_01.dtb \
	exynos7880-a5y17lte_eur_open_02.dtb \
	exynos7880-a5y17lte_eur_open_03.dtb \
	exynos7880-a5y17lte_eur_open_05.dtb \
	exynos7880-a5y17lte_eur_open_07.dtb \
	exynos7880-a5y17lte_eur_open_08.dtb

dtb-y += \
	exynos7880-a7y17lte_eur_open_00.dtb \
	exynos7880-a7y17lte_eur_open_01.dtb \
	exynos7880-a7y17lte_eur_open_02.dtb \
	exynos7880-a7y17lte_eur_open_03.dtb \
	exynos7880-a7y17lte_eur_open_04.dtb \
	exynos7880-a7y17lte_eur_open_06.dtb

targets += dtbs
DTB_LIST  := $(dtb-y) $(dtbo-y)
always    := $(DTB_LIST)

dtbs: $(addprefix $(obj)/, $(DTB_LIST))

clean-files := dts/*.dtb *.dtb
