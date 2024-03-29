---
title: FlatteningAnnotations
second_title: Référence de l'API Aspose.PDF pour .NET
description: Aplatit toutes les annotations du document.
type: docs
weight: 70
url: /fr/net/aspose.pdf.facades/pdfannotationeditor/flatteningannotations/
---
## FlatteningAnnotations() {#flatteningannotations}

Aplatit toutes les annotations du document.

```csharp
public void FlatteningAnnotations()
```

### Exemples

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
editor.FlatteningAnnotations();
editor.Save(example_out.pdf");
```

### Voir également

* class [PdfAnnotationEditor](../../pdfannotationeditor)
* espace de noms [Aspose.Pdf.Facades](../../pdfannotationeditor)
* Assemblée [Aspose.PDF](../../../)

---

## FlatteningAnnotations(FlattenSettings) {#flatteningannotations_1}

Aplatit toutes les annotations du document.

```csharp
public void FlatteningAnnotations(FlattenSettings flattenSettings)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| flattenSettings | FlattenSettings | Spécifie les modes d'aplatissement. |

### Voir également

* class [FlattenSettings](../../../aspose.pdf.forms/form.flattensettings)
* class [PdfAnnotationEditor](../../pdfannotationeditor)
* espace de noms [Aspose.Pdf.Facades](../../pdfannotationeditor)
* Assemblée [Aspose.PDF](../../../)

---

## FlatteningAnnotations(int, int, AnnotationType[]) {#flatteningannotations_2}

Aplatit les annotations des types spécifiés.

```csharp
public void FlatteningAnnotations(int start, int end, AnnotationType[] annotType)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| start | Int32 | La page de démarrage. |
| end | Int32 | Puis page de fin. |
| annotType | AnnotationType[] | Les types d'annotation doivent être aplatis. |

### Exemples

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
AnnotationType[] annotTypes ={AnnotationType.Line, AnnotationType.FreeText};
editor.FlatteningAnnotations(1, 2, annotTypes);
editor.Save("example_out.pdf");
```

### Voir également

* enum [AnnotationType](../../../aspose.pdf.annotations/annotationtype)
* class [PdfAnnotationEditor](../../pdfannotationeditor)
* espace de noms [Aspose.Pdf.Facades](../../pdfannotationeditor)
* Assemblée [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
