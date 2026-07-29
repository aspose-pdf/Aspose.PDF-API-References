---
title: "PdfPageEditor.MovePosition"
second_title: "Aspose.PDF for .NET API 参考"
description: "PdfPageEditor 方法。将原点从 0 0 移动到指定点。原点位于左下角，单位为 point1 英寸 72 点"
type: docs
weight: 170
url: /zh/net/aspose.pdf.facades/pdfpageeditor/moveposition/
---
## PdfPageEditor.MovePosition method

将原点从 (0, 0) 移动到指定的点。原点位于左下角，单位为点（1 英寸 = 72 点）。

```csharp
public void MovePosition(float moveX, float moveY)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| moveX | Single | X 坐标。 |
| moveY | Single | Y 坐标。 |

## 示例

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("input.pdf");
editor.MovePosition(-100, 60);
editor.Save("moved.pdf");
```

### 另请参见

* class [PdfPageEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


