---
title: "PdfPageEditor.GetPageSize"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Méthode PdfPageEditor. Retourne la taille de la page spécifiée."
type: docs
weight: 160
url: /fr/net/aspose.pdf.facades/pdfpageeditor/getpagesize/
---
## PdfPageEditor.GetPageSize method

Renvoie la taille de la page spécifiée.

```csharp
public PageSize GetPageSize(int page)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| page | Int32 | Indice de page. Les pages du document sont numérotées à partir de 1. |

### Valeur de retour

Le résultat est une instance de PageSize. Utilisez les propriétés Width et Height de l'objet retourné pour obtenir la largeur et la hauteur de la page.

## Exemples

L'exemple suivant montre l'utilisation de la méthode GetPageSize :

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("sample.pdf");
PageSize size = editor.GetPageSize(1);
Console.WriteLine("Size of 1st page : " + size.Width + " x " + size.Height);
```

### Voir aussi

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfPageEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


