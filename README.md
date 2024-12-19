# TX7-CT5DS-EFI
神舟 TX7-CT5DS-EFI

## 系统 15.2 (24C101)
## OC 1.0.3
## 硬件
- 固态：Samsung SSD 970 EVO Plus 1TB
- CPU: i5-9400
- 显卡：Intel UHD Graphics 630 2048 MB
- 内存：三星 32G 2667 MHz DDR4
- wifi: Intel AC 9462

## 其他

### Wifi 驱动补全
> macos15 以上需要进行 Wifi驱动补全
[OpenCore-Patcher-1.6.0](https://github.com/guoshiqiufeng/TX7-CT5DS-EFI/releases/download/v15.0/OpenCore-Patcher-1.6.0.pkg)

### 系统更新检测

开启：NVRAM 下 找到 boot-args 添加 `revpatch=auto,sbvmm,asset`

关闭：去除即可
