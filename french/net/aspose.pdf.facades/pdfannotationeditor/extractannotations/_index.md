---
title: PdfAnnotationEditor.ExtractAnnotations
second_title: Aspose.PDF for .NET API Reference
description: Méthode PdfAnnotationEditor. Obtient la liste des annotations des types spécifiés
type: docs
weight: 60
url: /fr/net/aspose.pdf.facades/pdfannotationeditor/extractannotations/
---
## ExtractAnnotations(int, int, string[]) {#extractannotations_1}

Obtient la liste des annotations des types spécifiés.

```csharp
public IList<Annotation> ExtractAnnotations(int start, int end, string[] annotTypes)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| start | Int32 | Page de départ à partir de laquelle les annotations seront sélectionnées. |
| end | Int32 | Page de fin à laquelle les annotations seront sélectionnées. |
| annotTypes | String[] | Le tableau des types d'annotations nécessaires. |

### Valeur de retour

Liste des annotations.

## Exemples

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
string[] annotTypes = new string[] {"Text", "Highlight"};
IList annotList = editor.ExtractAnnotations(1, 2 , annotTypes);
```

### Voir aussi

* classe [Annotation](../../../aspose.pdf.annotations/annotation/)
* classe [PdfAnnotationEditor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ExtractAnnotations(int, int, AnnotationType[]) {#extractannotations}

Obtient la liste des annotations des types spécifiés.

```csharp
public IList<Annotation> ExtractAnnotations(int start, int end, AnnotationType[] annotTypes)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| start | Int32 | Page de départ à partir de laquelle les annotations seront sélectionnées. |
| end | Int32 | Page de fin à laquelle les annotations seront sélectionnées. |
| annotTypes | AnnotationType[] | Le tableau des types d'annotations nécessaires. |

### Valeur de retour

Liste des annotations.

## Exemples

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
AnnotationType[] annotTypes = new AnnotationType[] {AnnotationType.Text, AnnotationType.Highlight};
IList annotList = editor.ExtractAnnotations(1, 2 , annotTypes);
```

### Voir aussi

* classe [Annotation](../../../aspose.pdf.annotations/annotation/)
* énum [AnnotationType](../../../aspose.pdf.annotations/annotationtype/)
* classe [PdfAnnotationEditor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)