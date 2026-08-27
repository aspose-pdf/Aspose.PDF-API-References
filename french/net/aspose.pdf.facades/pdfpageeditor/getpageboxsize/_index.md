---
title: "PdfPageEditor.GetPageBoxSize"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "PdfPageEditor méthode. Retourne la taille de la boîte spécifiée dans le document"
type: docs
weight: 130
url: /fr/net/aspose.pdf.facades/pdfpageeditor/getpageboxsize/
---
## PdfPageEditor.GetPageBoxSize method

Renvoie la taille de la boîte spécifiée dans le document.

```csharp
public Rectangle GetPageBoxSize(int page, string pageBoxName)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| page | Int32 | Indice de page. Les pages du document sont numérotées à partir de 1. |
| pageBoxName | String | Nom du type de boîte. Les valeurs valides sont : "art", "bleed", "crop", "media", "trim". |

### Valeur de retour

Rectangle qui contient la boîte demandée.

## Exemples

L'exemple suivant montre comment obtenir la boîte media de la première page :

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("sample.pdf");
System.Drawing.Rectangle rect = editor.GetBoxSize(1, "media");
```

### Voir aussi

* class [PdfPageEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


