# 获取分组数据

1、请求地址：/api/getGroupById

2、请求方式：POST

3、请求参数

| 参数  | 类型   | 必须 | 说明 |
| -| - | - | - |
|id | int | 是 | 数据id

4、返回参数

略


5、请求示例

```
POST {{baseUrl}}/api/getGroupById
Content-Type: application/json

{
  "id": 1
}
```

6、返回示例

```json
{
  "code": 0,
  "data": {
    "create_time": "2022-09-24 16:21:59",
    "id": 1,
    "name": "项目1",
    "update_time": "2022-09-24 16:21:59"
  },
  "msg": "success"
}
```
