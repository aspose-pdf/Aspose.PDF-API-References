---
title: "PdfContentEditor.DeleteImage"
second_title: "Aspose.PDF for .NET API 参考"
description: "PdfContentEditor 方法。删除指定页面上的指定图像。"
type: docs
weight: 320
url: /zh/net/aspose.pdf.facades/pdfcontenteditor/deleteimage/
---
## DeleteImage(int, int[]) {#deleteimage_1}

删除指定页面上的指定图像。

```csharp
public void DeleteImage(int pageNumber, int[] index)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pageNumber | Int32 | 需要删除图像的页面编号。 |
| index | Int32[] | 一个数组表示图像的索引。 |

## 示例

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.DeleteImage(1, new int[] {1, 2});
editor.Save("example_out.pdf");
```

### 另请参见

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## DeleteImage() {#deleteimage}

删除 PDF 文档中的所有图像。

```csharp
public void DeleteImage()
```

## 示例

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.DeleteImage();
editor.Save("example_out.pdf");
```

### 另请参见

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


