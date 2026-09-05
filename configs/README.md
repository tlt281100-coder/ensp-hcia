# 设备配置

本目录存放从 eNSP 工程中导出的设备配置文件：

| 文件 | 对应设备 |
| --- | --- |
| `出口路由器-OR.cfg` | 企业出口路由器 OR |
| `电信运营商路由器.cfg` | 电信运营商模拟路由器 |
| `联通运营商路由器.cfg` | 联通运营商模拟路由器 |
| `AC1.cfg` | 无线控制器 AC1 |

交换机（Core1、AGG1-3、ACC1-6、DC_SW）的运行配置保存在 eNSP 工程的设备 flash 镜像（`园区/` 下各设备目录中的 `flash.efz`）中。完整配置命令与说明见 [docs/项目实现文档.md](../docs/项目实现文档.md)，也可以在 eNSP 中启动设备后用 `display current-configuration` 查看并导出。
