---
title: Class PdfAnnotationEditor
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.PdfAnnotationEditor sınıfı. PDF belge notları ile çalışma için bir sınıfı temsil eder.
type: docs
weight: 4410
url: /tr/net/aspose.pdf.facades/pdfannotationeditor/
---
## PdfAnnotationEditor Sınıfı

PDF belge notları (yorumlar) ile çalışma için bir sınıfı temsil eder.

```csharp
public sealed class PdfAnnotationEditor : SaveableFacade
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [PdfAnnotationEditor](pdfannotationeditor/#constructor)() | Yeni bir `PdfAnnotationEditor` nesnesi başlatır. |
| [PdfAnnotationEditor](pdfannotationeditor/#constructor_1)(Document) | *belge* temelinde yeni bir `PdfAnnotationEditor` nesnesi başlatır. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Üzerinde çalışılan belge yüzeyini alır. |

## Metotlar

| Ad | Açıklama |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Yüzeyi başlatır. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | Yüzeyi başlatır. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | Yüzeyi başlatır. |
| virtual [Close](../../aspose.pdf.facades/facade/close/)() | Bir yüzeye bağlı Aspose.Pdf.Document nesnesini yok eder. |
| [DeleteAnnotation](../../aspose.pdf.facades/pdfannotationeditor/deleteannotation/)(string) | Belirtilen not adı ile notu siler. |
| [DeleteAnnotations](../../aspose.pdf.facades/pdfannotationeditor/deleteannotations/#deleteannotations)() | Belgedeki tüm notları siler. |
| [DeleteAnnotations](../../aspose.pdf.facades/pdfannotationeditor/deleteannotations/#deleteannotations_1)(string) | Belgedeki belirtilen türdeki tüm notları siler. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Yüzeyi yok eder. |
| [ExportAnnotationsToXfdf](../../aspose.pdf.facades/pdfannotationeditor/exportannotationstoxfdf/)(Stream) | Notları akışa aktarır. |
| [ExportAnnotationsXfdf](../../aspose.pdf.facades/pdfannotationeditor/exportannotationsxfdf/#exportannotationsxfdf)(Stream, int, int, AnnotationType[]) | Belirtilen not türlerinin içeriğini XFDF'ye aktarır. |
| [ExportAnnotationsXfdf](../../aspose.pdf.facades/pdfannotationeditor/exportannotationsxfdf/#exportannotationsxfdf_1)(Stream, int, int, string[]) | Belirtilen not türlerinin içeriğini XFDF'ye aktarır. |
| [ExtractAnnotations](../../aspose.pdf.facades/pdfannotationeditor/extractannotations/#extractannotations)(int, int, AnnotationType[]) | Belirtilen türdeki notların listesini alır. |
| [ExtractAnnotations](../../aspose.pdf.facades/pdfannotationeditor/extractannotations/#extractannotations_1)(int, int, string[]) | Belirtilen türdeki notların listesini alır. |
| [FlatteningAnnotations](../../aspose.pdf.facades/pdfannotationeditor/flatteningannotations/#flatteningannotations)() | Belgedeki tüm notları düzleştirir. |
| [FlatteningAnnotations](../../aspose.pdf.facades/pdfannotationeditor/flatteningannotations/#flatteningannotations_1)(FlattenSettings) | Belgedeki tüm notları düzleştirir. |
| [FlatteningAnnotations](../../aspose.pdf.facades/pdfannotationeditor/flatteningannotations/#flatteningannotations_2)(int, int, AnnotationType[]) | Belirtilen türdeki notları düzleştirir. |
| [ImportAnnotationFromXfdf](../../aspose.pdf.facades/pdfannotationeditor/importannotationfromxfdf/#importannotationfromxfdf_1)(Stream, AnnotationType[]) | Belirtilen notları XFDF veri akışından içe aktarır. |
| [ImportAnnotationFromXfdf](../../aspose.pdf.facades/pdfannotationeditor/importannotationfromxfdf/#importannotationfromxfdf_3)(string, AnnotationType[]) | Belirtilen notları XFDF dosyasından içe aktarır. |
| [ImportAnnotations](../../aspose.pdf.facades/pdfannotationeditor/importannotations/#importannotations)(Stream[]) | Başka bir PDF belgesinin akış dizisinden belgeye notları içe aktarır. |
| [ImportAnnotations](../../aspose.pdf.facades/pdfannotationeditor/importannotations/#importannotations_2)(string[]) | Başka PDF belgelerinin dizisinden belgeye notları içe aktarır. |
| [ImportAnnotations](../../aspose.pdf.facades/pdfannotationeditor/importannotations/#importannotations_1)(Stream[], AnnotationType[]) | Belirtilen notları başka bir PDF belgesinin akış dizisinden belgeye içe aktarır. |
| [ImportAnnotations](../../aspose.pdf.facades/pdfannotationeditor/importannotations/#importannotations_3)(string[], AnnotationType[]) | Belirtilen notları başka PDF belgelerinin dizisinden belgeye içe aktarır. |
| [ImportAnnotationsFromFdf](../../aspose.pdf.facades/pdfannotationeditor/importannotationsfromfdf/)(string) | FDF dosyasından tüm notları içe aktarır. |
| [ImportAnnotationsFromXfdf](../../aspose.pdf.facades/pdfannotationeditor/importannotationsfromxfdf/#importannotationsfromxfdf)(Stream) | XFDF veri akışından tüm notları içe aktarır. |
| [ImportAnnotationsFromXfdf](../../aspose.pdf.facades/pdfannotationeditor/importannotationsfromxfdf/#importannotationsfromxfdf_1)(string) | XFDF dosyasından tüm notları içe aktarır. |
| [ModifyAnnotations](../../aspose.pdf.facades/pdfannotationeditor/modifyannotations/#modifyannotations)(int, int, Annotation) | Belirtilen sayfa aralığında belirtilen türdeki notları değiştirir. Aşağıdaki not özelliklerini değiştirmeyi destekler: Modified, Title, Contents, Color, Subject ve Open. |
| [ModifyAnnotationsAuthor](../../aspose.pdf.facades/pdfannotationeditor/modifyannotationsauthor/)(int, int, string, string) | Belirtilen sayfa aralığında notların yazarını değiştirir. |
| [RedactArea](../../aspose.pdf.facades/pdfannotationeditor/redactarea/)(int, Rectangle, Color) | Belirtilen sayfada alanı sansürler. Tüm içerik kaldırılır. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(Stream) | PDF belgesini belirtilen akışa kaydeder. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(string) | PDF belgesini belirtilen dosyaya kaydeder. |

### Ayrıca Bakınız

* sınıf [SaveableFacade](../saveablefacade/)
* ad alanı [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../)