# 机器人对象 (MiraiBot)

## 属性

| 属性名 | 类型    | 描述           |
| ------ | ------- | -------------- |
| id     | Integer | 机器人的qq号码 |

## 方法

### getFriend (获取好友)

#### 参数列表：

| 参数 | 类型    | 描述     |
| ---- | ------- | -------- |
| id   | Integer | 好友qq号 |

#### 返回值：

| 类型                                  | 描述             |
| ------------------------------------- | ---------------- |
| [`MiraiFriend`](/docs/miraifriend.md) | 获取到的好友对象 |


### getGroup (获取群)

#### 参数列表：

| 参数 | 类型    | 描述 |
| ---- | ------- | ---- |
| id   | Integer | 群号 |

#### 返回值：

| 类型                                | 描述           |
| ----------------------------------- | -------------- |
| [`MiraiGroup`](/docs/miraigroup.md) | 获取到的群对象 |

### getSelfQQ (将MiraiBot对象转为MiraiFriend对象)

#### 返回值：

| 类型                                  | 描述         |
| ------------------------------------- | ------------ |
| [`MiraiFriend`](/docs/miraifriend.md) | 转换后的对象 |

### getId (获取机器人的qq号码)

#### 返回值：

| 类型    | 描述 |
| ------- | ---- |
| Integer | qq号 |

### addFriend (将MiraiBot对象转为MiraiFriend对象)

#### 参数列表：

| 参数 | 类型    | 描述     |
| ---- | ------- | -------- |
| id   | Integer | 好友qq号 |

#### 返回值：

| 类型                                  | 描述             |
| ------------------------------------- | ---------------- |
| [`MiraiFriend`](/docs/miraifriend.md) | 获取到的好友对象 |

### containsFriend (判断好友是否存在)

#### 参数列表：

| 参数 | 类型    | 描述     |
| ---- | ------- | -------- |
| id   | Integer | 好友qq号 |

#### 返回值：

| 类型    | 描述     |
| ------- | -------- |
| Boolean | 是否存在 |

### containsGroup (判断群是否存在)

#### 参数列表：

| 参数 | 类型    | 描述 |
| ---- | ------- | ---- |
| id   | Integer | 群号 |

#### 返回值：

| 类型    | 描述     |
| ------- | -------- |
| Boolean | 是否存在 |

### isActive (是否在线)

#### 参数列表：

| 参数 | 类型    | 描述     |
| ---- | ------- | -------- |
| id   | Integer | 好友qq号 |

#### 返回值：

| 类型    | 描述     |
| ------- | -------- |
| Boolean | 是否在线 |

### subscribeXXXXX (订阅事件)

详细用法见[`事件列表`](/docs/events.md)

#### 参数列表：

| 参数     | 类型     | 描述     |
| -------- | -------- | -------- |
| callback | Function | 回调函数 |

### launch(立即启动一个线程)

#### 参数列表：

| 参数  | 类型     | 描述       |
| ----- | -------- | ---------- |
| block | Function | 线程主函数 |


# 