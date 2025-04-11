---
title: Form.HasField
second_title: Aspose.PDF for .NET API Reference
description: 表单方法。检查表单是否已经具有指定字段
type: docs
weight: 280
url: /zh/net/aspose.pdf.forms/form/hasfield/
---
## HasField(Field) {#hasfield}

检查表单是否已经具有指定字段。

```csharp
public bool HasField(Field field)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| field | Field | 要检查的字段。 |

### 返回值

如果指定的字段名称已添加到表单，则为 `true`；否则为 `false`。

### 另见

* 类 [Field](../../field/)
* 类 [Form](../)
* 命名空间 [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* 程序集 [Aspose.PDF](../../../)

---

## HasField(string) {#hasfield_1}

确定具有指定名称的字段是否已经添加到表单中。

```csharp
public bool HasField(string fieldName)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fieldName | String | [`PartialName`](../../field/partialname/) 或 [`FullName`](../../../aspose.pdf.annotations/annotation/fullname/) 的字段。 |

### 返回值

如果指定的字段名称已添加到表单，则为 `true`；否则为 `false`。

### 另见

* 类 [Form](../)
* 命名空间 [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* 程序集 [Aspose.PDF](../../../)

---

## HasField(string, bool) {#hasfield_2}

确定具有指定名称的字段是否已经添加到表单中，并能够查看字段的子层次结构。

```csharp
public bool HasField(string fieldName, bool searchChildren)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fieldName | String | [`PartialName`](../../field/partialname/) 或 [`FullName`](../../../aspose.pdf.annotations/annotation/fullname/) 的字段。 |
| searchChildren | Boolean | 当设置为 `true` 时，将搜索整个表单字段层次结构以查找请求的 *fieldName*（请注意，在这种情况下，所需字段的 [`FullName`](../../../aspose.pdf.annotations/annotation/fullname/) 应作为 *fieldName* 传递）。 |

### 返回值

如果指定的字段名称已添加到表单，则为 `true`；否则为 `false`。

### 另见

* 类 [Form](../)
* 命名空间 [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* 程序集 [Aspose.PDF](../../../)