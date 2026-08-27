---
title: "PdfAnnotationEditor.ExtractAnnotations"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Méthode PdfAnnotationEditor. Obtient la liste des annotations des types spécifiés."
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
| start | Int32 | Page de début à partir de laquelle les annotations seront sélectionnées. |
| end | Int32 | Page de fin jusqu'à laquelle les annotations seront sélectionnées. |
| annotTypes | String[] | Le tableau des types d'annotation requis. |

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

* class [Annotation](../../../aspose.pdf.annotations/annotation/)
* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ExtractAnnotations(int, int, AnnotationType[]) {#extractannotations}

Obtient la liste des annotations des types spécifiés.

```csharp
public IList<Annotation> ExtractAnnotations(int start, int end, AnnotationType[] annotTypes)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| start | Int32 | Page de début à partir de laquelle les annotations seront sélectionnées. |
| end | Int32 | Page de fin jusqu'à laquelle les annotations seront sélectionnées. |
| annotTypes | AnnotationType[] | Le tableau des types d'annotation requis. |

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

* class [Annotation](../../../aspose.pdf.annotations/annotation/)
* enum [AnnotationType](../../../aspose.pdf.annotations/annotationtype/)
* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


