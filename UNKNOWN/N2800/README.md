# N2800

## Summery

Prodcut link: <https://item.taobao.com/item.htm?id=584277093892>

| Port        | Unit |
| ----------- | ---- |
| 1 GbE       | 1    |
| USB 2.0     | 4    |
| HDMI Output | 1    |
| mSATA       | 1    |

- [lshw.txt](lshw.txt)
- [dmidecode.txt](dmidecode.txt)
- <https://browser.geekbench.com/v5/cpu/600865>

## Power

| Mode    | Power |
| ------- | ----: |
| Standby |  9.0w |
| Max     | 11.5w |
| Boot    | 12.5w |

## Caverts

- BIOS 自带密码
  <br>拔除电池后进入 Administrator 模式进行可以重新设置密码来清除
  <br>如果不清除密码，再次进入 BIOS 将是 User 模式
- 确认不支持 UEFI 启动
- 优先 LVDS 输出但是没有 LVDS Connector

## BIOS Settings

- BIOS Snapshot
  <br>[BIOS](BIOS)

- Use HDMI Output (`Archlinux` availabe)
  <br>`Chipset` - `Host Bridge` - `Intel IGD Configuration` - `IGFX Boot Type` - `EFP`

- Automate Power On
  <br>`Advanced` - `Power Management Configuration` - `Restore AC Power Loss` - `Power On`

## References

- <https://www.mrtbc.com/special/n2800>
- <http://www.east-atom.com/html/7418255445.html>
- <https://ark.intel.com/content/www/us/en/ark/products/58917/intel-atom-processor-n2800-1m-cache-1-86-ghz.html>
