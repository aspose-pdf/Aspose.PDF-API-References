---
title: PdfPageEditor.GetPageBoxSize
second_title: Aspose.PDF for .NET API Reference
description: Méthode PdfPageEditor. Renvoie la taille de la boîte spécifiée dans le document
type: docs
weight: 130
url: /fr/net/aspose.pdf.facades/pdfpageeditor/getpageboxsize/
---
## Méthode PdfPageEditor.GetPageBoxSize

Renvoie la taille de la boîte spécifiée dans le document.

```csharp
public Rectangle GetPageBoxSize(int page, string pageBoxName)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| page | Int32 | Index de la page. Les pages du document sont numérotées à partir de 1. |
| pageBoxName | String | Nom du type de boîte. Les valeurs valides sont : "art", "bleed", "crop", "media", "trim". |

### Valeur de retour

Rectangle qui contient la boîte demandée.

## Exemples

L'exemple suivant démontre comment obtenir la boîte média de la 1ère page :

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("sample.pdf");
System.Drawing.Rectangle rect = editor.GetBoxSize(1, "media");
```

### Voir aussi

* classe [PdfPageEditor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)