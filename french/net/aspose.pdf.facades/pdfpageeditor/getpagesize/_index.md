---
title: PdfPageEditor.GetPageSize
second_title: Aspose.PDF for .NET API Reference
description: Méthode PdfPageEditor. Renvoie la taille de la page de la page spécifiée
type: docs
weight: 160
url: /fr/net/aspose.pdf.facades/pdfpageeditor/getpagesize/
---
## Méthode PdfPageEditor.GetPageSize

Renvoie la taille de la page de la page spécifiée.

```csharp
public PageSize GetPageSize(int page)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| page | Int32 | Index de la page. Les pages du document sont numérotées à partir de 1. |

### Valeur de retour

Le résultat est une instance de PageSize. Utilisez les propriétés Width et Height de l'objet retourné pour obtenir la largeur et la hauteur de la page.

## Exemples

L'exemple suivant démontre l'utilisation de la méthode GetPageSize :

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("sample.pdf");
PageSize size = editor.GetPageSize(1);
Console.WriteLine("Size of 1st page : " + size.Width + " x " + size.Height);
```

### Voir aussi

* classe [PageSize](../../../aspose.pdf/pagesize/)
* classe [PdfPageEditor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)