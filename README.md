# OpenWRT-CI
官方版：
https://github.com/immortalwrt/immortalwrt.git

自用版：
https://github.com/VIKINGYFY/immortalwrt.git

# 固件简要说明
固件信息里的时间为编译开始的时间，方便核对上游源码提交时间。

MEDIATEK系列、QUALCOMMAX系列、ROCKCHIP系列、X86系列。

# 目录简要说明
workflows——自定义CI配置

Scripts——自定义脚本

Config——自定义配置

# 修改 (自用)
## ebpf
[开启内核eBPF](https://github.com/GHNERCH/OpenWRT-CI)
最后同步:
Update Packages.sh GHNERCH* 2026/7/22 10:12

## daed
使用 olicesx/dae 的daed 有流量统计功能
https://github.com/darkrain88/daed-immWRT-CI-david
最后同步:
Update viking package dependencies darkrain88* 2026/7/22 13:30
