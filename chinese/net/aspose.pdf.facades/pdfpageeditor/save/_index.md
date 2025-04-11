---
title: PdfPageEditor.Save
second_title: Aspose.PDF for .NET API Reference
description: PdfPageEditor 方法。将更改后的文档保存到文件
type: docs
weight: 180
url: /zh/net/aspose.pdf.facades/pdfpageeditor/save/
---
## Save(string) {#save_1}

将更改后的文档保存到文件。

```csharp
public override void Save(string outputFile)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| outputFile | 字符串 | 文档将保存到的文件路径。 |

## 示例

以下示例演示如何保存更改后的 PDF 文档

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("sample.pdf");
editor.Zoom = 0.5f;
editor.Save("newdocument.pdf");
```

### 另请参阅

* 类 [PdfPageEditor](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)

---

## Save(Stream) {#save}

将更改后的文档保存到流中。

```csharp
public override void Save(Stream outputStream)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| outputStream | 流 | 更改后的 PDF 文档将保存到的流。 |

## 示例

以下示例演示如何将更改后的 PDF 文档保存到流中。

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("sample.pdf");
editor.Zoom = 0.5f;
editor.Save("newdocument.pdf");
```

### 另请参阅

* 类 [PdfPageEditor](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)