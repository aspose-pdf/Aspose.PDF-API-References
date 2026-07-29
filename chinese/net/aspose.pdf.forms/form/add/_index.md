---
title: "Form.Add"
second_title: "Aspose.PDF for .NET API 参考"
description: "Form 方法。向表单添加字段"
type: docs
weight: 210
url: /zh/net/aspose.pdf.forms/form/add/
---
## Add(Field, int) {#add_2}

在表单上添加字段。

```csharp
public void Add(Field field, int pageNumber)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 字段 | 字段 | 必须添加的字段。 |
| pageNumber | Int32 | 已添加字段将放置的页面索引。 |

### 另请参见

* class [Field](../../field/)
* class [Form](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## Add(Field) {#add_1}

在表单上添加字段。

```csharp
public void Add(Field field)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 字段 | 字段 | 必须添加的字段。 |

### 另请参见

* class [Field](../../field/)
* class [Form](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## Add(Field, string, int) {#add}

向表单添加新字段；如果该字段已放置在其他表单或此表单上，则会创建该字段的副本。

```csharp
public Field Add(Field field, string partialName, int pageNumber)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 字段 | 字段 | 字段名称。 |
| partialName | String | 表单上字段的名称。 |
| pageNumber | Int32 | 字段将被添加的页面编号。 |

### 返回值

返回已添加的字段。如果创建了字段的副本，则返回该副本。

### 另请参见

* class [Field](../../field/)
* class [Form](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)


