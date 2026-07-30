---
title: "PdfPageEditor.GetPageRotation"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Méthode PdfPageEditor. Retourne la rotation de la page spécifiée"
type: docs
weight: 140
url: /fr/net/aspose.pdf.facades/pdfpageeditor/getpagerotation/
---
## PdfPageEditor.GetPageRotation method

Renvoie la rotation de la page spécifiée.

```csharp
public int GetPageRotation(int page)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| page | Int32 | Indice de page. Les pages du document sont numérotées à partir de 1. |

### Valeur de retour

Rotation de la page en degrés.

## Exemples

L'exemple suivant montre comment obtenir la rotation de la page :

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("sample.pdf");
int rotation = editor.GetPageSize(1);
Console.WriteLine("Rotation of 1st page : " + rotation + " degrees");        
```

### Voir aussi

* class [PdfPageEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


