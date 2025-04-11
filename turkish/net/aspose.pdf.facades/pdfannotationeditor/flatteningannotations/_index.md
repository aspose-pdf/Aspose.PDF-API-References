---
title: PdfAnnotationEditor.FlatteningAnnotations
second_title: Aspose.PDF for .NET API Reference
description: PdfAnnotationEditor metodu. Belgedeki tüm anotasyonları düzleştirir
type: docs
weight: 70
url: /tr/net/aspose.pdf.facades/pdfannotationeditor/flatteningannotations/
---
## AnnotasyonlarıDüzleştirme() {#flatteningannotations}

Belgedeki tüm anotasyonları düzleştirir.

```csharp
public void FlatteningAnnotations()
```

## Örnekler

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
editor.FlatteningAnnotations();
editor.Save(example_out.pdf");
```

### Ayrıca Bakınız

* sınıf [PdfAnnotationEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)

---

## AnnotasyonlarıDüzleştirme(DüzleştirmeAyarları) {#flatteningannotations_1}

Belgedeki tüm anotasyonları düzleştirir.

```csharp
public void FlatteningAnnotations(FlattenSettings flattenSettings)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| düzleştirmeAyarları | DüzleştirmeAyarları | Düzleştirme modlarını belirtir. |

### Ayrıca Bakınız

* sınıf [DüzleştirmeAyarları](../../../aspose.pdf.forms/form.flattensettings/)
* sınıf [PdfAnnotationEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)

---

## AnnotasyonlarıDüzleştirme(int, int, AnotasyonTürü[]) {#flatteningannotations_2}

Belirtilen türdeki anotasyonları düzleştirir.

```csharp
public void FlatteningAnnotations(int start, int end, AnnotationType[] annotType)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| başlangıç | Int32 | Başlangıç sayfası. |
| bitiş | Int32 | Bitiş sayfası. |
| annotTürü | AnotasyonTürü[] | Düzleştirilmesi gereken anotasyon türleri. |

## Örnekler

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
AnnotationType[] annotTypes ={AnnotationType.Line, AnnotationType.FreeText};
editor.FlatteningAnnotations(1, 2, annotTypes);
editor.Save("example_out.pdf");
```

### Ayrıca Bakınız

* enum [AnotasyonTürü](../../../aspose.pdf.annotations/annotationtype/)
* sınıf [PdfAnnotationEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)