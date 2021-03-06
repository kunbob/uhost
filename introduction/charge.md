# 计费说明

UCloud云主机产品目前支持按年、按月、按时（预付费）和按时（后付费）四种计费方式。

## 按年计费

按年计费以年为计费周期支付订单，此类计费方式适用于长期稳定的业务。

目前主机推出的年付优惠策略如下：

|  | 主机 | 磁盘 | 外网弹性IP|
| --- | --- | --- | --- |
| 1年 | 83折 | 83折 |83折|
| 2年 | 7折 | 7折 |83折|
| 3年 | 5折 | 5折 |83折|

说明：
* 83折的概念为每年订单均可减免2个月费用，即1年减免2个月，2年减免4个月
* 年付优惠适用于所有云主机机型和磁盘类型
* 主机产品包含CPU、内存、网络增强等，磁盘产品包含本地磁盘、云盘和数据方舟等
* 允许用户在计费周期内删除退费，已使用部分按照月单价*使用时长进行扣除，详见：[退费细则](https://docs.ucloud.cn/charge/refund)
* 可叠加代金券使用

举例：用户于2020年5月15日新购一台1年付主机，列表价100 * 12=1200元，享受83折需支付1000元，2020年6月15日续费2年，续费的部分享受7折，需付1680元，2020年7月15日升级或降级，差价的部分享受5折（按照整个订单周期的时长判断，1+2=3年），差价=（新配置月单价-原配置月单价）* 剩余时长 * 适用年付折扣。

## 按月计费

按月计费以月为计费周期支付订单，此类计费方式适用于初创期或增长期业务。

用户可选择1-9个月支付主机订单，若需一次性购买10个月以上，建议选择按年计费以享受年付优惠。

说明：
* 选择按月计费，购买12个月主机并不能享受年付优惠
* 为满足用户对齐账单的需求，订单可选择付到月底

举例：用户于2020年5月15日20:00新购一台月付云主机，并选择1个月的计费周期，需先支付单月费用方可使用。2020年6月15日20:00到期后若继续使用，需在过期时间内及时续费。

## 按时计费（预付费）

按时计费（预付费）以小时为计费周期支付订单，此类计费方式适用于临时批量开通服务，以应对推广或暴增业务。

用户需预支付1小时费用方可使用主机产品，即先支付后使用，使用后每半小时预扣下1小时费用。

说明：
* 按时计费用户可自主变更为按月计费或按年计费

举例：用户于12：00支付1小时费用购买成功云主机，计费周期为12：00-13：00，系统将于12：30预扣13：00-14：00时间段内的费用，并以此类推。选择按时计费（预付费）的用户，请保障您的账号下有充足余额以支付后续费用。


## 按时计费（后付费）

> 按时计费（后付费）目前仅支持系统盘和数据盘为云盘的主机（本地盘主机尚未支持），且正在逐步灰度中，可能无法申请。

按时计费（后付费）以小时为计费周期生成后付费订单，此类计费方式适用于一天中有大量关机时间的场景。

购买主机时无需预支付费用，1小时后，系统根据前1小时的用量生成待支付订单，并自动扣除费用。此处的用量特指CPU与内存的用量，关机情况下，系统不会统计CPU与内存的用量，开机时则正常统计。此外，云盘费用与主机开关机状态无关，按照完整的小时计费。按时计费（预付费）与按时计费（后付费）定价一致。

举例：用户于12：00购买成功后付费云主机，系统将于13：00生成12：00-13：00时间段内的后付费订单，并以此类推。选择按时计费（后付费）的用户，请保障您的账号下有充足余额以支付后续费用。
