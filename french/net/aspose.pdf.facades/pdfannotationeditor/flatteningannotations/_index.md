---
title: PdfAnnotationEditor.FlatteningAnnotations
second_title: Aspose.PDF for .NET API Reference
description: Méthode PdfAnnotationEditor. Aplatit toutes les annotations dans le document
type: docs
weight: 70
url: /fr/net/aspose.pdf.facades/pdfannotationeditor/flatteningannotations/
---
## FlatteningAnnotations() {#flatteningannotations}

Aplatit toutes les annotations dans le document.

```csharp
public void FlatteningAnnotations()
```

## Exemples

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
editor.FlatteningAnnotations();
editor.Save(example_out.pdf");
```

### Voir aussi

* classe [PdfAnnotationEditor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## FlatteningAnnotations(FlattenSettings) {#flatteningannotations_1}

Aplatit toutes les annotations dans le document.

```csharp
public void FlatteningAnnotations(FlattenSettings flattenSettings)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| flattenSettings | FlattenSettings | Spécifie les modes d'aplatissement. |

### Voir aussi

* classe [FlattenSettings](../../../aspose.pdf.forms/form.flattensettings/)
* classe [PdfAnnotationEditor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## FlatteningAnnotations(int, int, AnnotationType[]) {#flatteningannotations_2}

Aplatit les annotations des types spécifiés.

```csharp
public void FlatteningAnnotations(int start, int end, AnnotationType[] annotType)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| start | Int32 | La page de début. |
| end | Int32 | La page de fin. |
| annotType | AnnotationType[] | Les types d'annotations doivent être aplatis. |

## Exemples

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
AnnotationType[] annotTypes ={AnnotationType.Line, AnnotationType.FreeText};
editor.FlatteningAnnotations(1, 2, annotTypes);
editor.Save("example_out.pdf");
```

### Voir aussi

* enum [AnnotationType](../../../aspose.pdf.annotations/annotationtype/)
* classe [PdfAnnotationEditor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)