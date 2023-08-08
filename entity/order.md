
# 订单基础信息

| 字段名称   | 字段类型 | 不能为空 | 默认值 | 描述                                        |
| ---------- | -------- | -------- | ------ | ------------------------------------------- |
| no         | string   | Y        | 无     | 单据号                                      |
| geo        | string   | N        | 无     | 最后记录坐标                                |
| state_code | string   | Y        | 无     | [运单状态编码](../enums.md?id=order_status) |
| state_name | string   | N        | 无     | 运单状态说明                                |
| out_no     | string   | N        | 无     | 客户单号                                    |
| remarks    | string   | N        | 无     | 运单记录说明                                |
