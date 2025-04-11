---
title: PdfPageEditor.GetPageRotation
second_title: Aspose.PDF for .NET API Reference
description: Méthode PdfPageEditor. Renvoie la rotation de la page spécifiée
type: docs
weight: 140
url: /fr/net/aspose.pdf.facades/pdfpageeditor/getpagerotation/
---
## Méthode PdfPageEditor.GetPageRotation

Renvoie la rotation de la page spécifiée.

```csharp
public int GetPageRotation(int page)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| page | Int32 | Index de la page. Les pages du document sont numérotées à partir de 1. |

### Valeur de retour

Rotation de la page en degrés.

## Exemples

L'exemple suivant démontre comment obtenir la rotation de la page:

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("sample.pdf");
int rotation = editor.GetPageSize(1);
Console.WriteLine("Rotation of 1st page : " + rotation + " degrees");        
```

### Voir aussi

* classe [PdfPageEditor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)