# NUC9-hacktosh-config

`update to oc 1.0.0;
update to MacOS 13.6.7`

![MacOS 13.6.7](https://github.com/littlesum/nuc9hacktosh-config/blob/main/pic/iShot_2023-08-24_08.32.04.png)

# NUC9 的黑苹果配置

## 我的具体配置

### Notice: intel wifi bluetooth not configured

### Now update to MacOS 13.6.7

| Matherboard | nuc9i9      |
| ----------- | ----------- |
| dGpu        | wx4100      |
| RAM         | 64Gx3200    |
| SSD         | sn570       |
| NIC         | Aqc107 10G  |
| Airport_nic | bcm94360cs2 |
| oc version  | 0.9.6       |

## usb already mod include usb2 in motherboard (down)

##  根据opencore更新说明，我在更新opencore 0.9.6之后，要使用aqc107万兆卡，就需要更改dmar，所以acpi里面新增了dmar修改，如果您没有使用aqc107需要把这个acpi文件删除了！
