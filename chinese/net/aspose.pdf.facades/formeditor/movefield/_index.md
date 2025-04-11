---
title: FormEditor.MoveField
second_title: Aspose.PDF for .NET API Reference
description: FormEditor 方法。设置字段的新位置
type: docs
weight: 200
url: /zh/net/aspose.pdf.facades/formeditor/movefield/
---
## FormEditor.MoveField 方法

设置字段的新位置。

```csharp
public bool MoveField(string fieldName, float llx, float lly, float urx, float ury)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fieldName | 字符串 | 必须移动的字段名称。 |
| llx | 单精度 | 字段左下角的横坐标。 |
| lly | 单精度 | 字段左下角的纵坐标。 |
| urx | 单精度 | 字段右上角的横坐标。 |
| ury | 单精度 | 字段右上角的纵坐标。 |

### 返回值

如果字段位置成功更改，则返回 true。

## 示例

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_MoveField.pdf");
formEditor.MoveField("textField", 20.5f, 20.3f, 120.6f, 40.8f);
```

### 另请参阅

* 类 [FormEditor](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)