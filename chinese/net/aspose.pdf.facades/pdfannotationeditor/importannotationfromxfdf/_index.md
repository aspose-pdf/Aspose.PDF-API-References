---
title: PdfAnnotationEditor.ImportAnnotationFromXfdf
second_title: Aspose.PDF for .NET API Reference
description: PdfAnnotationEditor 方法。 从 XFDF 文件导入指定的注释
type: docs
weight: 80
url: /zh/net/aspose.pdf.facades/pdfannotationeditor/importannotationfromxfdf/
---
## ImportAnnotationFromXfdf(string, AnnotationType[]) {#importannotationfromxfdf_3}

从 XFDF 文件导入指定的注释。

```csharp
public void ImportAnnotationFromXfdf(string xfdfFile, AnnotationType[] annotType)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| xfdfFile | 字符串 | 输入的 XFDF 文件。 |
| annotType | AnnotationType[] | 要导入的注释数组。 |

## 示例

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
AnnotationType[] annotTypes = {AnnotationType.Highlight, AnnotationType.Text};
editor.ImportAnnotationFromXfdf("annots.xfdf", annotTypes);
editor.Save("example_out.pdf");
```

### 另请参阅

* 枚举 [AnnotationType](../../../aspose.pdf.annotations/annotationtype/)
* 类 [PdfAnnotationEditor](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)

---

## ImportAnnotationFromXfdf(Stream, AnnotationType[]) {#importannotationfromxfdf_1}

从 XFDF 数据流导入指定的注释。

```csharp
public void ImportAnnotationFromXfdf(Stream xfdfStream, AnnotationType[] annotType)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| xfdfStream | 流 | 输入的 XFDF 数据流。 |
| annotType | AnnotationType[] | 要导入的注释类型数组。 |

## 示例

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
AnnotationType[] annotTypes ={ AnnotationType.Highlight, AnnotationType.Line };
editor.ImportAnnotationFromXfdf(File.OpenRead("annots.xfdf"), annotTypes);
editor.Save("example_out.pdf");
```

### 另请参阅

* 枚举 [AnnotationType](../../../aspose.pdf.annotations/annotationtype/)
* 类 [PdfAnnotationEditor](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)