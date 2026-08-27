---
title: "PdfContentEditor.DeleteStampByIds"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Méthode PdfContentEditor. Supprime les stamps avec les ID spécifiés de toutes les pages du document"
type: docs
weight: 350
url: /fr/net/aspose.pdf.facades/pdfcontenteditor/deletestampbyids/
---
## DeleteStampByIds(int[]) {#deletestampbyids_1}

Supprime les tampons avec les ID spécifiés de toutes les pages du document.

```csharp
public void DeleteStampByIds(int[] stampIds)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| stampIds | Int32[] | Tableau d'ID d'estampilles. |

## Exemples

```csharp
PdfContentEditor contentEditor = new PdfContentEditor();
contentEditor.BindPdf("file.pdf");
contentEditor.DeleteStampByIds(new int[] { 102, 103 } );
contentEditor.Save("outfile.pdf");
```

### Voir aussi

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## DeleteStampByIds(int, int[]) {#deletestampbyids}

Supprime les tampons sur la page spécifiée par plusieurs ID de tampon.

```csharp
public void DeleteStampByIds(int pageNumber, int[] stampIds)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| pageNumber | Int32 | Numéro de page où les estampilles seront supprimées. |
| stampIds | Int32[] | Tableau d'ID d'estampilles. |

## Exemples

```csharp
PdfContentEditor contentEditor = new PdfContentEditor();
contentEditor.BindPdf("file.pdf");
contentEditor.DeleteStampByIds(1, new int[] { 100, 101 } );
contentEditor.Save("outfile.pdf");
```

### Voir aussi

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


