---
title: "PdfContentEditor.DeleteStampById"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Méthode PdfContentEditor. Supprime le tampon sur la page spécifiée par l'ID du tampon"
type: docs
weight: 340
url: /fr/net/aspose.pdf.facades/pdfcontenteditor/deletestampbyid/
---
## DeleteStampById(int, int) {#deletestampbyid_1}

Supprime le tampon sur la page spécifiée par son ID.

```csharp
public void DeleteStampById(int pageNumber, int stampId)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| pageNumber | Int32 | Numéro de page où le tampon sera supprimé. |
| stampId | Int32 | Identifiant du stanp qui doit être supprimé. |

## Exemples

```csharp
PdfContentEditor contentEditor = new PdfContentEditor();
contentEditor.BindPdf("file.pdf");
contentEditor.DeleteStampById(1, 100);
contentEditor.Save("outfile.pdf");
```

### Voir aussi

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## DeleteStampById(int) {#deletestampbyid}

Supprime le tampon par ID de toutes les pages du document.

```csharp
public void DeleteStampById(int stampId)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| stampId | Int32 | Identifiant du tampon qui doit être supprimé. |

## Exemples

```csharp
PdfContentEditor contentEditor = new PdfContentEditor();
contentEditor.BindPdf("file.pdf");
contentEditor.DeleteStampById(100);
contentEditor.Save("outfile.pdf");
```

### Voir aussi

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


