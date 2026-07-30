---
title: "PdfAnnotationEditor.FlatteningAnnotations"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "PdfAnnotationEditor méthode. Aplatisse toutes les annotations du document"
type: docs
weight: 70
url: /fr/net/aspose.pdf.facades/pdfannotationeditor/flatteningannotations/
---
## FlatteningAnnotations() {#flatteningannotations}

Aplatisse toutes les annotations du document.

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

* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## FlatteningAnnotations(FlattenSettings) {#flatteningannotations_1}

Aplatisse toutes les annotations du document.

```csharp
public void FlatteningAnnotations(FlattenSettings flattenSettings)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| flattenSettings | FlattenSettings | Spécifie les modes d'aplatissement. |

### Voir aussi

* class [FlattenSettings](../../../aspose.pdf.forms/form.flattensettings/)
* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## FlatteningAnnotations(int, int, AnnotationType[]) {#flatteningannotations_2}

Aplatisse les annotations des types spécifiés.

```csharp
public void FlatteningAnnotations(int start, int end, AnnotationType[] annotType)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| start | Int32 | La page de début. |
| end | Int32 | Puis la page de fin. |
| annotType | AnnotationType[] | Les types d'annotation doivent être aplatis. |

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
* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


