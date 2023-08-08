
# 单据轨迹信息实体

| 字段名称   | 字段类型 | 不能为空 | 默认值 | 描述                                  |
| ---------- | -------- | -------- | ------ | ------------------------------------- |
| time       | long     | Y        | 无     | 轨迹记录时间                          |
| geo        | string   | N        | 无     | 轨迹记录经纬度                        |
| address    | string   | N        | 无     | 轨迹记录地点                          |
| state_code | string   | y        | 无     | [运单状态编码](enums?id=order_status) |
| state_name | string   | N        | 无     | 运单状态说明                          |
| remarks    | string   | N        | 无     | 运单备注说明                          |
