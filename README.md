# m73-efi
lenovo tiny m73 opencore efi

CPU：i5-4590T \
内存：16g \
网卡：BCM94360HMB

**注意：**
1. 使用此efi，请使用occ重新生成自己的序列号
2. 使用 opencore 0.9.7 升级 Monterey、Ventura 失败（Sonoma没有尝试，网卡问题已经不适合黑苹果了！！！）
   - boot-args 新增 amfi_get_out_of_my_way=1 ipc_control_port_options=0
   - 设置 Misc - SecureBootModel = Disabled
   - 安装 OpenCore-Patcher-2.4.0.pkg

3. 当前使用 branch: oc0.6.6 of Big Sur 11.5.2 养老。
