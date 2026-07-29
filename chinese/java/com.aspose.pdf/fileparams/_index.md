---
title: "FileParams"
linktitle: "FileParams"
second_title: "Aspose.PDF for Java API 参考"
description: "定义一个嵌入文件参数字典，其中应包含额外的特定文件信息。"
type: docs
weight: 1490
url: /zh/java/com.aspose.pdf/fileparams/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.FileParams

```
public final class FileParams extends Object
```

定义一个嵌入文件参数字典，其中应包含额外的特定文件信息。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [FileParams](#FileParams-com.aspose.pdf.FileSpecification-) | FileParams 类的构造函数。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [getCheckSum](#getCheckSum--) | 一个 16 字节的字符串，表示未压缩嵌入文件字节的校验和。该校验和通过对嵌入文件流的字节应用标准 MD5 消息摘要算法计算得到。 |
| [getCreationDate](#getCreationDate--) | 获取嵌入文件创建的日期和时间。 |
| [getModDate](#getModDate--) | 获取嵌入文件最后修改的日期和时间。 |
| [getSize](#getSize--) | 未压缩嵌入文件的大小（字节）。 |
| [setCreationDate](#setCreationDate-java.util.Date-) | 设置嵌入文件创建的日期和时间。 |
| [setModDate](#setModDate-java.util.Date-) | 设置嵌入文件最后修改的日期和时间。 |

### FileParams {#FileParams-com.aspose.pdf.FileSpecification-}
FileParams 类的构造函数。

### getCheckSum {#getCheckSum--}
```
public String getCheckSum()
```

一个 16 字节的字符串，表示未压缩嵌入文件字节的校验和。该校验和通过对嵌入文件流的字节应用标准 MD5 消息摘要算法计算得到。

**Returns:**
字符串值

### getCreationDate {#getCreationDate--}
```
public Date getCreationDate()
```

获取嵌入文件创建的日期和时间。

**Returns:**
Date 对象

### getModDate {#getModDate--}
```
public Date getModDate()
```

获取嵌入文件最后修改的日期和时间。

**Returns:**
Date 对象

### getSize {#getSize--}
```
public int getSize()
```

未压缩嵌入文件的大小（字节）。

**Returns:**
int 值

### setCreationDate {#setCreationDate-java.util.Date-}
设置嵌入文件创建的日期和时间。

### setModDate {#setModDate-java.util.Date-}
设置嵌入文件最后修改的日期和时间。
