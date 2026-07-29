---
title: "Form.HasField"
second_title: "Aspose.PDF for .NET API 参考"
description: "Form 方法。检查表单是否已经具有指定字段。"
type: docs
weight: 300
url: /zh/net/aspose.pdf.forms/form/hasfield/
---
## HasField(Field) {#hasfield}

检查表单是否已经具有指定字段。

```csharp
public bool HasField(Field field)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 字段 | 字段 | 要检查的字段。 |

### 返回值

`true` 表示指定的字段名称已添加到 Form；否则为 `false`。

### 另请参见

* class [Field](../../field/)
* class [Form](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## HasField(string) {#hasfield_1}

确定是否已将具有指定名称的字段添加到表单中。

```csharp
public bool HasField(string fieldName)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fieldName | String | 字段的 [`PartialName`](../../field/partialname/) 或 [`FullName`](../../../aspose.pdf.annotations/annotation/fullname/)。 |

### 返回值

`true` 表示指定的字段名称已添加到 Form；否则为 `false`。

### 另请参见

* class [Form](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## HasField(string, bool) {#hasfield_2}

确定是否已将具有指定名称的字段添加到表单中，并能够查看字段的子层次结构。

```csharp
public bool HasField(string fieldName, bool searchChildren)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fieldName | String | 字段的 [`PartialName`](../../field/partialname/) 或 [`FullName`](../../../aspose.pdf.annotations/annotation/fullname/)。 |
| searchChildren | Boolean | 设置为 `true` 时，将在整个表单字段层次结构中搜索请求的 *fieldName*（请注意，在这种情况下，应将所需字段的 [`FullName`](../../../aspose.pdf.annotations/annotation/fullname/) 作为 *fieldName* 传入）。 |

### 返回值

`true` 表示指定的字段名称已添加到 Form；否则为 `false`。

### 另请参见

* class [Form](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)


