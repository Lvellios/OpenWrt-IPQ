# OpenWrt for IPQ60xx
***
## Upgrade RAM
### The rank density is the product of rank depth and rank width.
| Memory Organisation | Rank Depth | Rank Width | Number Of Banks | Rank Density |
| ------| ------ | ------ | ------ | ------ |
| 1G × 16 | 128 Mbit | 16 Bits | 8 Banks | 2048 Mb |
| 512M × 16 | 64 Mbit | 16 Bits | 8 Banks | 1024 Mb |
| 256M × 16 | 32 Mbit | 16 Bits | 8 Banks | 512 Mb |
| 128M × 16 | 16 Mbit | 16 Bits | 8 Banks | 256 Mb |

## Original RAM
* M15T2G16128A-DEB, DDR3L, FBGA 96, 7.5mm×13.5mm (128M×16, 16M×16×8), Single Die

## 2GB
* MT41K1G16DGA-125:A (D9STR), DDR3L, FBGA 96, (1G×16, 128M×16×8), Single Die

## 1GB
* MT41K512M16HA-125:A (D9STQ), DDR3L, FBGA 96, 9mm×14mm (512M×16, 64M×16×8), Single Die
* MT41K512M16VRP-107 IT:P (D9ZWN), DDR3L, FBGA 96, 8mm×14 mm (512M×16, 64M×16×8), Single Die

## 512M
* MT41K256M16TW-107 AIT:P (D9SHJ), DDR3, FBGA 96, (256M×16, 32M×16×8), Single Die
* MT41K256M16TW-107:P (D9SHG), DDR3, FBGA 96, (256M×16, 32M×16×8), Single Die

***
### Redmi AX5 & RA67
* Processor: IPQ6018（Quad Cores A53@1.0-1.2 Ghz, 1 NPU@1.5 GHz)
* RAM: 256MB, (ESMT) **M15T2G16128A**, DDR3, FBGA96 [You must upgrade RAM ≥512 MB](#heading)
* Flash: 128MB, (GigaDevice) **GD9FS1G8F2AMGI**, SLC, TSOP48
* Switch: QCA8075 {5 Ports, 10/100/1000 GbE}
* 5G WiSoC: QCN5052 {2x2:2 (1.2 Gbps), Wi-Fi 6, 1024QAM}, FEM: QPF4550 ×2
* 2.4 WiSoC: QCN5022, {2x2:2 (574 Mbps), Wi-Fi 6, 1024QAM}, FEM: QPF4200 ×2
* Power Management: MP5496

### Xiaomi AX1800
* Processor: IPQ6000 (Quad Cores A53@1.0-1.2 Ghz, 1 NPU@1.5 GHz)
* RAM: 256MB, (ESMT) **M15T2G16128A**, DDR3, FBGA96 [You must upgrade RAM ≥512 MB](#heading)
* Flash: 128MB, (ESMT) **F59D1G81MB**, TSOP48
* Others are the same as AX5

### GL.iNet GL-AX1800
* V1 Processor: IPQ6000 (Quad Cores A53@1.0-1.2 Ghz, 1 NPU@1.5 GHz)
* V2 Processor: IPQ6018 (Quad Cores A53@1.8 Ghz, 2 NPU@1.5 GHz)
* RAM: 512MB, DDR3L
* Flash: 128MB
* Others are the same as AX5