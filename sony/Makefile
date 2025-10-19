PINEAPPLE_BASE_DTB += ../qcom/pineapple.dtb ../qcom/pineapple-v2.dtb ../qcom/cliffs.dtb ../qcom/cliffs7.dtb
PINEAPPLE_APQ_BASE_DTB += ../qcom/pineapplep.dtb ../qcom/pineapplep-v2.dtb

SOMC_PINEAPPLE_BOARDS += pineapple-asahi-pdx245_generic-overlay.dtbo pineapple-asahi-pdx245_ets-overlay.dtbo

dtb-y += $(SOMC_PINEAPPLE_BOARDS) $(PINEAPPLE_BASE_DTB) $(PINEAPPLE_APQ_BASE_DTB)

always-y	:= $(dtb-y)
subdir-y	:= $(dts-dirs)
clean-files	:= *.dtb *.dtbo
