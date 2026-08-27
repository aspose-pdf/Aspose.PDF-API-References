---
title: "类 PdfAnnotationEditor"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.Facades.PdfAnnotationEditor 类。表示用于处理 PDF 文档注释评论的类"
type: docs
weight: 4530
url: /zh/net/aspose.pdf.facades/pdfannotationeditor/
---
## PdfAnnotationEditor class

表示用于处理 PDF 文档批注（注释）的类。

```csharp
public sealed class PdfAnnotationEditor : SaveableFacade
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [PdfAnnotationEditor](pdfannotationeditor/#constructor)() | 初始化新的 `PdfAnnotationEditor` 对象。 |
| [PdfAnnotationEditor](pdfannotationeditor/#constructor_1)(Document) | 基于 *document* 初始化新的 `PdfAnnotationEditor` 对象。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | 获取正在操作的 document facade。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | 初始化 facade。 |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | 初始化 facade。 |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | 初始化 facade。 |
| virtual [Close](../../aspose.pdf.facades/facade/close/)() | 释放与外观绑定的 Aspose.Pdf.Document。 |
| [DeleteAnnotation](../../aspose.pdf.facades/pdfannotationeditor/deleteannotation/)(string) | 删除具有指定注释名称的注释。 |
| [DeleteAnnotations](../../aspose.pdf.facades/pdfannotationeditor/deleteannotations/#deleteannotations)() | 删除文档中的所有注释。 |
| [DeleteAnnotations](../../aspose.pdf.facades/pdfannotationeditor/deleteannotations/#deleteannotations_1)(string) | 删除文档中指定类型的所有注释。 |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | 释放 facade。 |
| [ExportAnnotationsToXfdf](../../aspose.pdf.facades/pdfannotationeditor/exportannotationstoxfdf/)(Stream) | 将注释导出到流。 |
| [ExportAnnotationsXfdf](../../aspose.pdf.facades/pdfannotationeditor/exportannotationsxfdf/#exportannotationsxfdf)(Stream, int, int, AnnotationType[]) | 将指定注释类型的内容导出为 XFDF。 |
| [ExportAnnotationsXfdf](../../aspose.pdf.facades/pdfannotationeditor/exportannotationsxfdf/#exportannotationsxfdf_1)(Stream, int, int, string[]) | 将指定注释类型的内容导出为 XFDF。 |
| [ExtractAnnotations](../../aspose.pdf.facades/pdfannotationeditor/extractannotations/#extractannotations)(int, int, AnnotationType[]) | 获取指定类型注释的列表。 |
| [ExtractAnnotations](../../aspose.pdf.facades/pdfannotationeditor/extractannotations/#extractannotations_1)(int, int, string[]) | 获取指定类型注释的列表。 |
| [FlatteningAnnotations](../../aspose.pdf.facades/pdfannotationeditor/flatteningannotations/#flatteningannotations)() | 将文档中的所有注释扁平化。 |
| [FlatteningAnnotations](../../aspose.pdf.facades/pdfannotationeditor/flatteningannotations/#flatteningannotations_1)(FlattenSettings) | 将文档中的所有注释扁平化。 |
| [FlatteningAnnotations](../../aspose.pdf.facades/pdfannotationeditor/flatteningannotations/#flatteningannotations_2)(int, int, AnnotationType[]) | 将指定类型的注释扁平化。 |
| [ImportAnnotationFromXfdf](../../aspose.pdf.facades/pdfannotationeditor/importannotationfromxfdf/#importannotationfromxfdf_1)(Stream, AnnotationType[]) | 从 XFDF 数据流导入指定的注释。 |
| [ImportAnnotationFromXfdf](../../aspose.pdf.facades/pdfannotationeditor/importannotationfromxfdf/#importannotationfromxfdf_3)(string, AnnotationType[]) | 从 XFDF 文件导入指定的注释。 |
| [ImportAnnotations](../../aspose.pdf.facades/pdfannotationeditor/importannotations/#importannotations)(Stream[]) | 从另一个 PDF 文档流数组将注释导入到文档中。 |
| [ImportAnnotations](../../aspose.pdf.facades/pdfannotationeditor/importannotations/#importannotations_2)(string[]) | 从另一个 PDF 文档数组将注释导入到文档中。 |
| [ImportAnnotations](../../aspose.pdf.facades/pdfannotationeditor/importannotations/#importannotations_1)(Stream[], AnnotationType[]) | 从另一个 PDF 文档流数组将指定的注释导入到文档中。 |
| [ImportAnnotations](../../aspose.pdf.facades/pdfannotationeditor/importannotations/#importannotations_3)(string[], AnnotationType[]) | 从另一个 PDF 文档数组将指定的注释导入到文档中。 |
| [ImportAnnotationsFromFdf](../../aspose.pdf.facades/pdfannotationeditor/importannotationsfromfdf/)(string) | 从 FDF 文件导入所有注释。 |
| [ImportAnnotationsFromXfdf](../../aspose.pdf.facades/pdfannotationeditor/importannotationsfromxfdf/#importannotationsfromxfdf)(Stream) | 从 XFDF 数据流导入所有注释。 |
| [ImportAnnotationsFromXfdf](../../aspose.pdf.facades/pdfannotationeditor/importannotationsfromxfdf/#importannotationsfromxfdf_1)(string) | 从 XFDF 文件导入所有批注。 |
| [ModifyAnnotations](../../aspose.pdf.facades/pdfannotationeditor/modifyannotations/#modifyannotations)(int, int, Annotation) | 修改指定页面范围内指定类型的批注。支持修改以下批注属性：Modified、Title、Contents、Color、Subject 和 Open。 |
| [ModifyAnnotationsAuthor](../../aspose.pdf.facades/pdfannotationeditor/modifyannotationsauthor/)(int, int, string, string) | 修改指定页面范围内批注的作者。 |
| [RedactArea](../../aspose.pdf.facades/pdfannotationeditor/redactarea/)(int, Rectangle, Color) | 在指定页面上进行编辑遮盖。所有内容均被删除。 |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(Stream) | 将 PDF 文档保存到指定的流中。 |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(string) | 将 PDF 文档保存到指定的文件中。 |

### 另请参见

* class [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


