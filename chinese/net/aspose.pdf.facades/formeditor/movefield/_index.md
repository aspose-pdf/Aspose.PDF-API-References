---
title: "FormEditor.MoveField"
second_title: "Aspose.PDF for .NET API 参考"
description: "FormEditor 方法。设置字段的新位置"
type: docs
weight: 200
url: /zh/net/aspose.pdf.facades/formeditor/movefield/
---
## FormEditor.MoveField method

设置字段的新位置。

```csharp
public bool MoveField(string fieldName, float llx, float lly, float urx, float ury)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fieldName | String | 必须移动的字段名称。 |
| llx | Single | 字段左下角的横坐标。 |
| lly | Single | 字段左下角的纵坐标。 |
| urx | Single | 字段右上角的横坐标。 |
| ury | Single | 字段右上角的纵坐标。 |

### 返回值

如果成功更改字段位置，则返回 true。

## 示例

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_MoveField.pdf");
formEditor.MoveField("textField", 20.5f, 20.3f, 120.6f, 40.8f);
```

### 另请参见

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


