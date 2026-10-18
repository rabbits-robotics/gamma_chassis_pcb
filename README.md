# gamma_chassis_pcb

## 役割

車体側の受動分配ハブ。マイコンは載せず、24V 入力を 8 系統に分配し、CAN2 を車輪・脚モータへ分配する。

## 主要部品

| 部品 | 型番 | 用途 |
|---|---|---|
| 24V 入力コネクタ | AMASS XT30PW-M × 1 | 幹線からの 24V 入力 |
| 24V 分配コネクタ | AMASS XT30U-F × 8 | 車輪・脚モータへの電源分配 |
| CAN コネクタ | JST PH B2B-PH-K × 9 | CAN_CHASSIS 1〜4、CAN_LEG 1〜4、CAN_TURRET |
| 6P コネクタ | JST PH B6B-PH-K × 1 | 砲塔側（スリップリング）への出力 |

回路図は [gamma_chassis.pdf](./gamma_chassis.pdf)、部品表は [bom.csv](./bom.csv)、3D は [gamma_chassis.step](./gamma_chassis.step)。

## ライセンス

© Rabbits Robotics、[CERN-OHL-P-2.0](./LICENSE)。
