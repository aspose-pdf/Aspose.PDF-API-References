---
title: PdfAnnotationEditor.ImportAnnotationsFromXfdf
second_title: Aspose.PDF for .NET API Reference
description: PdfAnnotationEditor 方法。 从 XFDF 文件导入所有注释
type: docs
weight: 110
url: /zh/net/aspose.pdf.facades/pdfannotationeditor/importannotationsfromxfdf/
---
## ImportAnnotationsFromXfdf(string) {#importannotationsfromxfdf_1}

从 XFDF 文件导入所有注释。

```csharp
public void ImportAnnotationsFromXfdf(string xfdfFile)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| xfdfFile | 字符串 | 输入的 XFDF 文件。 |

## 示例

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
editor.ImportAnnotationsFromXfdf("annots.xfdf");
editor.Save("example_out.pdf");
```

### 另请参阅

* 类 [PdfAnnotationEditor](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)

---

## ImportAnnotationsFromXfdf(Stream) {#importannotationsfromxfdf}

从 XFDF 数据流导入所有注释。

```csharp
public void ImportAnnotationsFromXfdf(Stream xfdfStream)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| xfdfStream | 流 | 输入的 XFDF 数据流。 |

## 示例

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
editor.ImportAnnotationsFromXfdf(File.OpenRead("annots.xfdf"));
editor.Save("example_out.pdf");
```

### 另请参阅

* 类 [PdfAnnotationEditor](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)