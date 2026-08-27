---
title: "PageLabelCollection"
linktitle: "PageLabelCollection"
second_title: "Aspose.PDF for Java API 参考"
description: "表示页面标签集合的类。"
type: docs
weight: 3400
url: /zh/java/com.aspose.pdf/pagelabelcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PageLabelCollection

```
public class PageLabelCollection extends Object
```

表示页面标签集合的类。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getLabel](#getLabel-int-) | 获取页面标签，依据页面索引（页面索引从 0 开始）。 |
| [getPages](#getPages--) | 获取集合中的页面索引。 |
| [removeLabel](#removeLabel-int-) | 通过页面索引移除标签（页面索引从 0 开始）。 |
| [updateLabel](#updateLabel-int-com.aspose.pdf.PageLabel-) | 更新给定页面索引的标签（页面索引从 0 开始）。 |

### getLabel {#getLabel-int-}
```
public PageLabel getLabel(int pageIndex)
```

获取页面标签，依据页面索引（页面索引从 0 开始）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pageIndex |  | 页面的索引。 |

**Returns:**
指定页面索引的页面标签，如果页面标签不存在则为 null。

### getPages {#getPages--}
```
public int[] getPages()
```

获取集合中的页面索引。

**Returns:**
包含页面索引的整数数组。

### removeLabel {#removeLabel-int-}
```
public boolean removeLabel(int pageIndex)
```

通过页面索引移除标签（页面索引从 0 开始）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pageIndex |  | 需要删除标签的页面索引。 |

**Returns:**
如果操作成功执行，则为 true。

### updateLabel {#updateLabel-int-com.aspose.pdf.PageLabel-}
更新给定页面索引的标签（页面索引从 0 开始）。
