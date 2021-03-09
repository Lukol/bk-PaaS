### 功能描述

删除对象模型属性，可以删除业务自定义字段

### 请求参数

{{ common_args_desc }}

#### 接口参数

| 字段  |  类型       | 必选   |  描述                         |
|-------|-------------|--------|-------------------------------|
| id    | int         | 否     | 被删除的数据记录的唯一标识ID  |


### 请求参数示例

```python

{
    "id" : 0
}
```


### 返回结果示例

```python

{
    "result": true,
    "code": 0,
    "message": "",
    "data": "success"
}
```