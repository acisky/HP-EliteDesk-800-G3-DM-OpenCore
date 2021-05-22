# HP-EliteDesk-800-G3-DM-OpenCore

## 配置

- CPU: Intel(R) Core(TM) i5-6600T CPU @ 2.70GHz
- GPU: Intel HD Graphics 530
- Memory: 2 x 16GB Samsung DDR4-2133
- Storage: 512G nvme ssd
- LAN: Intel® I219LM Gigabit Network Connection LOM
- WLAN: Wireless 7265
- Audio: Conexant CX20632 Audio Codec

## 更新日志

- 定制USB，蓝牙usb为内联
- 升级VirtualSMC，增加YogaSMC，正常显示风扇转速
- 清理config.plist无效配置

## 无效

- HD  530 休眠无效
- Wireless 7265 无法驱动，后期更换BCM943224PCIEBT2 （7265可用itlwm配合HeliPort上网）

## 备注
- 支持4K （DP转HDMI需要使用PS176芯片才能支持4K 60Hz）
- 支持HP HDMI Port Flex IO，需要将型号改为MacBookPro13,1

## 其他

~~Big Sur 安装会卡12分钟安装bug，后期再处理~~ （更新nvram配置已经解决）

