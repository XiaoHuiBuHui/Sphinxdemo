# 接入参数示例
| 参数名称 | 参数值 | 是否必须 | 示例 | 备注 |
| --- | --- | --- | --- | --- |
| Content-Type | application/json | 是 |   |   |
| X-Api-Key |   | 是 | 00001 | 项目 API Key，用于 API 访问鉴权 |
| X-Timestamp |   | 是 | 1642065511000 | 时间戳，1970年1月1日0点0分0秒到现在的毫秒数 |
| X-Signature |   | 是 | 93908f3533bf816e7e59131e391723b585368605b553091b5f8cb64a0d668a7a | API 签名，算法为SHA256(Params+Timestamp+ApiSecret) |