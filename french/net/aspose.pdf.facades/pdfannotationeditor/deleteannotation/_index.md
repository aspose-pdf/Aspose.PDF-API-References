---
title: "PdfAnnotationEditor.DeleteAnnotation"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Méthode PdfAnnotationEditor. Supprime l'annotation avec le nom d'annotation spécifié"
type: docs
weight: 20
url: /fr/net/aspose.pdf.facades/pdfannotationeditor/deleteannotation/
---
## PdfAnnotationEditor.DeleteAnnotation method

Supprime l'annotation avec le nom d'annotation spécifié.

```csharp
public void DeleteAnnotation(string annotName)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| annotName | String | Le nom de l'annotation |

## Exemples

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
editor.DeleteAnnotation("4cfa69cd-9bff-49e0-9005-e22a77cebf38");
editor.Save("example_out.pdf");
```

### Voir aussi

* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


