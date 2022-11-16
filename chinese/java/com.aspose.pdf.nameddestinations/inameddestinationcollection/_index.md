---
标题：INamedDestinationCollection
second_title: Aspose.PDF for Java API 参考
描述：命名目的地的集合。
类型：文档
体重：11
网址：/java/com.aspose.pdf.nameddestinations/inameddestinationcollection/
---```
公共接口 INamedDestinationCollection
```

Collection of Named Destinations.
## Methods

| Method | Description |
| --- | --- |
| [add(String name, IAppointment appointment)](#add-java.lang.String-com.aspose.pdf.IAppointment-) | Adds new named destination. |
| [getNames()](#getNames--) | Gets array of names of the destinations. |
| [get_Item(String name)](#get-Item-java.lang.String-) | Gets destination by its name. |
| [remove(String name)](#remove-java.lang.String-) | Removes destination by its name. |
| [set_Item(String name, IAppointment value)](#set-Item-java.lang.String-com.aspose.pdf.IAppointment-) | Sets destination by its name. |
| [size()](#size--) | Returns count of the destinations. |
### add(String name, IAppointment appointment) {#add-java.lang.String-com.aspose.pdf.IAppointment-}
```
public abstract void add(String name, IAppointment appointment)
```


Adds new named destination.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | String value |
| appointment | [IAppointment](../../com.aspose.pdf/iappointment) | IAppointment instance |

### getNames() {#getNames--}
```
公共抽象字符串[] 获取名称()
```


Gets array of names of the destinations.

**Returns:**
java.lang.String[] - Array of String values
### get_Item(String name) {#get-Item-java.lang.String-}
```
公共抽象 IAppointment get_Item（字符串名称）
```


Gets destination by its name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | String value |

**Returns:**
[IAppointment](../../com.aspose.pdf/iappointment) - IAppointment instance Destination object.
### remove(String name) {#remove-java.lang.String-}
```
公共抽象无效删除（字符串名称）
```


Removes destination by its name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | String value |

### set_Item(String name, IAppointment value) {#set-Item-java.lang.String-com.aspose.pdf.IAppointment-}
```
public abstract void set_Item（字符串名称，IAppointment 值）
```


Sets destination by its name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | String value |
| value | [IAppointment](../../com.aspose.pdf/iappointment) | IAppointment instance Destination object. |

### size() {#size--}
```
公共抽象整数大小（）
```


Returns count of the destinations.

**Returns:**
int - int value