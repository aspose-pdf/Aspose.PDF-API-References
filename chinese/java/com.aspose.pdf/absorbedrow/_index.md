---
title: "AbsorbedRow"
linktitle: "AbsorbedRow"
second_title: "Aspose.PDF for Java API 参考"
description: "表示页面上存在的表格行"
type: docs
weight: 20
url: /zh/java/com.aspose.pdf/absorbedrow/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.AbsorbedRow

**All Implemented Interfaces:**
ITableElement, Comparable < AbsorbedRow >

```
public class AbsorbedRow extends Object implements ITableElement , Comparable < AbsorbedRow >
```

表示页面上存在的表格行

## 方法

| 方法 | 描述 |
| --- | --- |
| [compareTo](#compareTo-com.aspose.pdf.AbsorbedRow-) | 比较当前的 AbsorbedRow 对象与另一个 AbsorbedRow 对象，并返回一个整数，指示当前对象在排序顺序中是位于前面、后面，还是与另一个对象处于相同位置。 |
| [getCellList](#getCellList--) | 获取只读 IList，包含该行的单元格。 |
| [getRectangle](#getRectangle--) | 获取描述该行在页面上位置的矩形。 |

### compareTo {#compareTo-com.aspose.pdf.AbsorbedRow-}
比较当前的 AbsorbedRow 对象与另一个 AbsorbedRow 对象，并返回一个整数，指示当前对象在排序顺序中是位于前面、后面，还是与另一个对象处于相同位置。

### getCellList {#getCellList--}
```
public List < AbsorbedCell > getCellList()
```

获取只读 IList，包含该行的单元格。

**Returns:**
AbsorbedCell 对象的列表。

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

获取描述该行在页面上位置的矩形。

**Returns:**
Rectangle 实例
