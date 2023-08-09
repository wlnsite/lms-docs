# 运单详情查询

- **接口说明：** 根据运单号、客户方单号查询运单详情
- **接口地址：** /api/order_detail
- **请求方式：** GET/POST
- **请求参数：**
  | 参数名称 | 参数类型 | 出现要求 | 描述                                   |
  | -------- | -------- | -------- | -------------------------------------- |
  | no       | string   | C        | 要查询的运单号                         |
  | out_no   | string   | C        | 要查询的客户方单号（no、out_no二选一） |
- **输出参数：**
  | 参数名称       | 参数类型 | 出现要求 | 描述                           |
  | -------------- | -------- | -------- | ---------------------------- |
  | code           | string   | R        | 执行状态：1-成功，其它表示异常 |
  | message        | string   | R        | 消息：错误消息或成功提示       |
  | data           | object   | R        | 输出数据：查询结果             |
  | - no           | string   | R        | 平台运单号                     |
  | - out_no       | string   | R        | 客户运单号                     |
  | - state_code   | string   | R        | 状态代码                       |
  | - state_name   | string   | O        | 状态描述                       |
  | - from_area    | string   | O        | 始发地区划                     |
  | - dest_area    | string   | O        | 目的地区划                     |
  | - signer            | string   | O        | 签收人                         |


