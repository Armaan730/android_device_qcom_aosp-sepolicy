# device-qcom-aosp-sepolicy

Repository that hosts SELinux common policies for QCOM Hardware
It was forked from https://github.com/sonyxperiadev/device-qcom-sepolicy
and should be track it.

This repo was created for Sony Open Devices
http://developer.sonymobile.com/knowledge-base/open-source/open-devices/list-of-devices-and-resources/

If you want to use these policies, add a

include device/qcom/aosp-sepolicy/sepolicy.mk

to your device's BoardConfig. It is highly recommended that in case
you have your own BOARD_SEPOLICY_DIRS and BOARD_SEPOLICY_UNION declarations,
the inclusion happens _before_ those lines
