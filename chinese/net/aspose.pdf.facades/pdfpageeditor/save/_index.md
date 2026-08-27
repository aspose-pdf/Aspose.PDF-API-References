---
title: "PdfPageEditor.Save"
second_title: "Aspose.PDF for .NET API 参考"
description: "PdfPageEditor 方法。将更改的文档保存到文件中。"
type: docs
weight: 180
url: /zh/net/aspose.pdf.facades/pdfpageeditor/save/
---
## Save(string) {#save_1}

将更改后的文档保存到文件中。

```csharp
public override void Save(string outputFile)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| outputFile | String | 文档将保存到的文件路径。 |

## 示例

以下示例演示如何保存更改后的 PDF 文档

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("sample.pdf");
editor.Zoom = 0.5f;
editor.Save("newdocument.pdf");
```

### 另请参见

* class [PdfPageEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Save(Stream) {#save}

将更改后的文档保存到流中。

```csharp
public override void Save(Stream outputStream)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| outputStream | Stream | 更改后的 PDF 文档将保存的流。 |

## 示例

以下示例演示如何将更改后的 PDF 文档保存到流中。

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("sample.pdf");
editor.Zoom = 0.5f;
editor.Save("newdocument.pdf");
```

### 另请参见

* class [PdfPageEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


