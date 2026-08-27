---
title: "PdfAnnotationEditor.DeleteAnnotations"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Méthode PdfAnnotationEditor. Supprime toutes les annotations du document"
type: docs
weight: 30
url: /fr/net/aspose.pdf.facades/pdfannotationeditor/deleteannotations/
---
## DeleteAnnotations() {#deleteannotations}

Supprime toutes les annotations du document.

```csharp
public void DeleteAnnotations()
```

## Exemples

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
editor.DeleteAnnotations();
editor.Save("example_out.pdf");
```

### Voir aussi

* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## DeleteAnnotations(string) {#deleteannotations_1}

Supprime toutes les annotations du type spécifié dans le document.

```csharp
public void DeleteAnnotations(string annotType)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| annotType | String | Le type d'annotation sera supprimé. |

## Exemples

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
editor.DeleteAnnotations("Text");
editor.Save("example_out.pdf");
```

### Voir aussi

* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


