---
title: Form.Add
second_title: Aspose.PDF for .NET API Reference
description: 表单方法。向表单添加字段
type: docs
weight: 190
url: /zh/net/aspose.pdf.forms/form/add/
---
## Add(Field, int) {#add_2}

向表单添加字段。

```csharp
public void Add(Field field, int pageNumber)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| field | Field | 必须添加的字段。 |
| pageNumber | Int32 | 添加字段将放置的页面索引。 |

### 另见

* class [Field](../../field/)
* class [Form](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## Add(Field) {#add_1}

向表单添加字段。

```csharp
public void Add(Field field)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| field | Field | 必须添加的字段。 |

### 另见

* class [Field](../../field/)
* class [Form](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## Add(Field, string, int) {#add}

向表单添加新字段；如果该字段已经放置在其他表单或此表单上，将创建字段的副本。

```csharp
public Field Add(Field field, string partialName, int pageNumber)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| field | Field | 字段名称。 |
| partialName | String | 表单上字段的名称。 |
| pageNumber | Int32 | 字段将被添加的页面编号。 |

### 返回值

返回添加的字段。如果创建了字段的副本，将返回该副本。

### 另见

* class [Field](../../field/)
* class [Form](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)