---
title: "NumberTree"
linktitle: "NumberTree"
second_title: "Aspose.PDF for Java API 参考"
description: "表示 PDF 文件的 Number 树结构的类。7.9.7Number Trees"
type: docs
weight: 3150
url: /zh/java/com.aspose.pdf/numbertree/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.NumberTree

```
public class NumberTree extends Object
```

表示 PDF 文件的 Number 树结构的类。7.9.7Number Trees

## 方法

| 方法 | 描述 |
| --- | --- |
| [get](#get-int-) | 根据键获取项。 |
| [getKeys](#getKeys--) | 获取树中的所有键。 |
| [remove](#remove-int-) | 从数字树中移除键。 |

### get {#get-int-}
```
public com.aspose.pdf.engine.data.IPdfPrimitive get(int key)
```

根据键获取项。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 键 |  | int 值 |

**Returns:**
IPdfPrimitive 对象

### getKeys {#getKeys--}
```
public com.aspose.ms.System.Collections.Generic.List< Integer > getKeys()
```

获取树中的所有键。

**Returns:**
{@code List<Integer> object}

### remove {#remove-int-}
```
public boolean remove(int key)
```

从数字树中移除键。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 键 |  | int 值 |

**Returns:**
布尔值
