黑苹果

CPU：锐龙5600g

主板：华擎A520m-itx/ac

macos：13.6.6 (22G630)

目前一切正常，能够识别apu，唯一的问题是无法主动休眠，但超时自动休眠正常

BIOS调整

1、BIOS>引导>CSM(兼容性设备支持模块)> 改为“关闭”；

2、BISO>高级>PCI配置>Above 4G Decoding > 改为“enable启用”；

3、BISO>高级>PCI配置>Re-Size BAR Support > 改为“disable禁用”；

4、BIOS> 高级 > AMD PBS > Graphics Features > Primary Video Adaptor > 选择为“Int Graphics (IGD)”

5、BIOS> 高级 > AMD CBS > NBIO Common Options > GFX Configuration > iGPU Configuration > 改为UMA SPECIFIED

6、BIOS> 高级 > AMD CBS > NBIO Common Options > GFX Configuration > iGPU Configuration > UMA Frame buffer Size > 选择4G；

7、BIOS> 高级 > AMD CBS > Chipset Common Options > SATA Configuration Options > SATA Mode > 改为 AHCI

8、BIOS> 安全：关闭安全引导
