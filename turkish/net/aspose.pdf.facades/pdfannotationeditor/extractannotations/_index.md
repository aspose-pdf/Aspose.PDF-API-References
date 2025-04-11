---
title: PdfAnnotationEditor.ExtractAnnotations
second_title: Aspose.PDF for .NET API Reference
description: PdfAnnotationEditor metodu. Belirtilen türlerin anotasyonlarının listesini alır
type: docs
weight: 60
url: /tr/net/aspose.pdf.facades/pdfannotationeditor/extractannotations/
---
## AçıkAnnotasyonlar(int, int, string[]) {#extractannotations_1}

Belirtilen türlerin anotasyonlarının listesini alır.

```csharp
public IList<Annotation> ExtractAnnotations(int start, int end, string[] annotTypes)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| başlangıç | Int32 | Anotasyonların seçileceği başlangıç sayfası. |
| bitiş | Int32 | Anotasyonların seçileceği bitiş sayfası. |
| annotTürleri | String[] | Gerekli anotasyon türlerinin dizisi. |

### Dönüş Değeri

Anotasyonlar listesi.

## Örnekler

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
string[] annotTypes = new string[] {"Text", "Highlight"};
IList annotList = editor.ExtractAnnotations(1, 2 , annotTypes);
```

### Ayrıca Bakınız

* sınıf [Annotation](../../../aspose.pdf.annotations/annotation/)
* sınıf [PdfAnnotationEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)

---

## AçıkAnnotasyonlar(int, int, AnnotationType[]) {#extractannotations}

Belirtilen türlerin anotasyonlarının listesini alır.

```csharp
public IList<Annotation> ExtractAnnotations(int start, int end, AnnotationType[] annotTypes)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| başlangıç | Int32 | Anotasyonların seçileceği başlangıç sayfası. |
| bitiş | Int32 | Anotasyonların seçileceği bitiş sayfası. |
| annotTürleri | AnnotationType[] | Gerekli anotasyon türlerinin dizisi. |

### Dönüş Değeri

Anotasyonlar listesi.

## Örnekler

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
AnnotationType[] annotTypes = new AnnotationType[] {AnnotationType.Text, AnnotationType.Highlight};
IList annotList = editor.ExtractAnnotations(1, 2 , annotTypes);
```

### Ayrıca Bakınız

* sınıf [Annotation](../../../aspose.pdf.annotations/annotation/)
* enum [AnnotationType](../../../aspose.pdf.annotations/annotationtype/)
* sınıf [PdfAnnotationEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)