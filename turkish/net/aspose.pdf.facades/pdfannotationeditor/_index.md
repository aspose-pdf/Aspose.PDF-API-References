---
title: PdfAnnotationEditor
second_title: Aspose.PDF for .NET API Referansı
description: PDF belgesi ek açıklamaları yorumlar ile çalışmak için bir sınıfı temsil eder.
type: docs
weight: 2420
url: /tr/net/aspose.pdf.facades/pdfannotationeditor/
---
## PdfAnnotationEditor class

PDF belgesi ek açıklamaları (yorumlar) ile çalışmak için bir sınıfı temsil eder.

```csharp
public sealed class PdfAnnotationEditor : SaveableFacade
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [PdfAnnotationEditor](pdfannotationeditor#constructor)() | Yeniyi başlatır[`PdfAnnotationEditor`](../pdfannotationeditor) nesne. |
| [PdfAnnotationEditor](pdfannotationeditor#constructor_1)(Document) | Yeniyi başlatır[`PdfAnnotationEditor`](../pdfannotationeditor) temelinde nesne*document* . |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document) { get; } | Üzerinde çalıştığı belge cephesini alır. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(Document) | Cepheyi başlatır. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(Stream) | Cepheyi başlatır. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(string) | Cepheyi başlatır. |
| virtual [Close](../../aspose.pdf.facades/facade/close)() | Aspose.Pdf.Document'ı bir cepheye bağlı olarak imha eder. |
| [DeleteAnnotation](../../aspose.pdf.facades/pdfannotationeditor/deleteannotation)(string) | Belirtilen açıklama adı ile açıklamayı siler. |
| [DeleteAnnotations](../../aspose.pdf.facades/pdfannotationeditor/deleteannotations#deleteannotations)() | Belgedeki tüm açıklamaları siler. |
| [DeleteAnnotations](../../aspose.pdf.facades/pdfannotationeditor/deleteannotations#deleteannotations_1)(string) | Belgede belirtilen türdeki tüm açıklamaları siler. |
| [Dispose](../../aspose.pdf.facades/facade/dispose)() | Cepheyi ortadan kaldırır. |
| [ExportAnnotationsToXfdf](../../aspose.pdf.facades/pdfannotationeditor/exportannotationstoxfdf)(Stream) | Ek açıklamaları akışa aktarır. |
| [ExportAnnotationsXfdf](../../aspose.pdf.facades/pdfannotationeditor/exportannotationsxfdf#exportannotationsxfdf)(Stream, int, int, AnnotationType[]) | Belirtilen ek açıklama türlerinin içeriğini XFDF içine aktarır |
| [ExportAnnotationsXfdf](../../aspose.pdf.facades/pdfannotationeditor/exportannotationsxfdf#exportannotationsxfdf_1)(Stream, int, int, string[]) | Belirtilen ek açıklama türlerinin içeriğini XFDF içine aktarır |
| [ExtractAnnotations](../../aspose.pdf.facades/pdfannotationeditor/extractannotations#extractannotations)(int, int, AnnotationType[]) | Belirtilen türlerin ek açıklamalarının listesini alır. |
| [ExtractAnnotations](../../aspose.pdf.facades/pdfannotationeditor/extractannotations#extractannotations_1)(int, int, string[]) | Belirtilen türlerin ek açıklamalarının listesini alır. |
| [FlatteningAnnotations](../../aspose.pdf.facades/pdfannotationeditor/flatteningannotations#flatteningannotations)() | Belgedeki tüm açıklamaları düzleştirir. |
| [FlatteningAnnotations](../../aspose.pdf.facades/pdfannotationeditor/flatteningannotations#flatteningannotations_1)(FlattenSettings) | Belgedeki tüm açıklamaları düzleştirir. |
| [FlatteningAnnotations](../../aspose.pdf.facades/pdfannotationeditor/flatteningannotations#flatteningannotations_2)(int, int, AnnotationType[]) | Belirtilen türlerin ek açıklamalarını düzleştirir. |
| [ImportAnnotationFromXfdf](../../aspose.pdf.facades/pdfannotationeditor/importannotationfromxfdf#importannotationfromxfdf_1)(Stream, AnnotationType[]) | Belirtilen ek açıklamaları XFDF veri akışından içe aktarır. |
| [ImportAnnotationFromXfdf](../../aspose.pdf.facades/pdfannotationeditor/importannotationfromxfdf#importannotationfromxfdf_3)(string, AnnotationType[]) | Belirtilen ek açıklamaları XFDF dosyasından içe aktarır. |
| [ImportAnnotations](../../aspose.pdf.facades/pdfannotationeditor/importannotations#importannotations)(Stream[]) | Ek açıklamaları başka bir PDF belge akışı dizisinden belgeye aktarır. |
| [ImportAnnotations](../../aspose.pdf.facades/pdfannotationeditor/importannotations#importannotations_2)(string[]) | Ek açıklamaları başka bir PDF belgesi dizisinden belgeye aktarır. |
| [ImportAnnotations](../../aspose.pdf.facades/pdfannotationeditor/importannotations#importannotations_1)(Stream[], AnnotationType[]) | Belirtilen ek açıklamaları başka bir PDF belge akışı dizisinden belgeye aktarır. |
| [ImportAnnotations](../../aspose.pdf.facades/pdfannotationeditor/importannotations#importannotations_3)(string[], AnnotationType[]) | Belirtilen ek açıklamaları başka bir PDF belgesi dizisinden belgeye aktarır. |
| [ImportAnnotationsFromXfdf](../../aspose.pdf.facades/pdfannotationeditor/importannotationsfromxfdf#importannotationsfromxfdf)(Stream) | Tüm açıklamaları XFDF veri akışından içe aktarır. |
| [ImportAnnotationsFromXfdf](../../aspose.pdf.facades/pdfannotationeditor/importannotationsfromxfdf#importannotationsfromxfdf_1)(string) | Tüm açıklamaları XFDF dosyasından içe aktarır. |
| [ModifyAnnotations](../../aspose.pdf.facades/pdfannotationeditor/modifyannotations#modifyannotations)(int, int, Annotation) | Belirtilen sayfa aralığında belirtilen türün ek açıklamalarını değiştirir. Sonraki açıklama özelliklerini değiştirmeyi destekler: Değiştirilmiş, Başlık, İçerik, Renk, Konu ve Aç. |
| [ModifyAnnotationsAuthor](../../aspose.pdf.facades/pdfannotationeditor/modifyannotationsauthor)(int, int, string, string) | Belirtilen sayfa aralığındaki ek açıklamaların yazarını değiştirir. |
| [RedactArea](../../aspose.pdf.facades/pdfannotationeditor/redactarea)(int, Rectangle, Color) | Belirtilen sayfadaki alanı düzeltir. Tüm içerikler kaldırılır. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save)(Stream) | PDF belgesini belirtilen akışa kaydeder. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save)(string) | PDF belgesini belirtilen dosyaya kaydeder. |

### Ayrıca bakınız

* class [SaveableFacade](../saveablefacade)
* ad alanı [Aspose.Pdf.Facades](../../aspose.pdf.facades)
* toplantı [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
