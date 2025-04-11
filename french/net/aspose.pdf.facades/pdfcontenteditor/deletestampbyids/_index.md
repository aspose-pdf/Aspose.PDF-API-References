---
title: PdfContentEditor.DeleteStampByIds
second_title: Aspose.PDF for .NET API Reference
description: Méthode PdfContentEditor. Supprime les tampons avec des ID spécifiés de toutes les pages du document
type: docs
weight: 350
url: /fr/net/aspose.pdf.facades/pdfcontenteditor/deletestampbyids/
---
## DeleteStampByIds(int[]) {#deletestampbyids_1}

Supprime les tampons avec des ID spécifiés de toutes les pages du document.

```csharp
public void DeleteStampByIds(int[] stampIds)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| stampIds | Int32[] | Tableau des ID de tampon. |

## Exemples

```csharp
PdfContentEditor contentEditor = new PdfContentEditor();
contentEditor.BindPdf("file.pdf");
contentEditor.DeleteStampByIds(new int[] { 102, 103 } );
contentEditor.Save("outfile.pdf");
```

### Voir aussi

* classe [PdfContentEditor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## DeleteStampByIds(int, int[]) {#deletestampbyids}

Supprime les tampons sur la page spécifiée par plusieurs ID de tampon.

```csharp
public void DeleteStampByIds(int pageNumber, int[] stampIds)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| pageNumber | Int32 | Numéro de page où les tampons seront supprimés. |
| stampIds | Int32[] | Tableau des ID de tampon. |

## Exemples

```csharp
PdfContentEditor contentEditor = new PdfContentEditor();
contentEditor.BindPdf("file.pdf");
contentEditor.DeleteStampByIds(1, new int[] { 100, 101 } );
contentEditor.Save("outfile.pdf");
```

### Voir aussi

* classe [PdfContentEditor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)