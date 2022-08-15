---
title: CreateFileAttachment
second_title: Référence de l'API Aspose.PDF pour .NET
description: Crée une annotation de pièce jointe.
type: docs
weight: 150
url: /fr/net/aspose.pdf.facades/pdfcontenteditor/createfileattachment/
---
## CreateFileAttachment(Rectangle, string, string, int, string) {#createfileattachment_2}

Crée une annotation de pièce jointe.

```csharp
public void CreateFileAttachment(Rectangle rect, string contents, string filePath, int page, 
    string name)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| rect | Rectangle | Rectangle d'annotation définissant l'emplacement de l'annotation sur la page. |
| contents | String | Le contenu de l'annotation. |
| filePath | String | Le chemin du fichier sera joint. |
| page | Int32 | Le numéro de la page d'origine où l'annotation sera créée. |
| name | String | Le nom d'une icône sera utilisé dans l'affichage de l'annotation. Cette valeur peut être : "Graph", "PushPin", "Paperclip", "Tag". |

### Exemples

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateFileAttachment(new System.Drawing.Rectangle(0, 0, 100, 100),
    "Welcome to Aspose", "attachment_file.pdf", 1, "Graph");
editor.Save("example_out.pdf");
```

### Voir également

* class [PdfContentEditor](../../pdfcontenteditor)
* espace de noms [Aspose.Pdf.Facades](../../pdfcontenteditor)
* Assemblée [Aspose.PDF](../../../)

---

## CreateFileAttachment(Rectangle, string, string, int, string, double) {#createfileattachment_3}

Crée une annotation de pièce jointe.

```csharp
public void CreateFileAttachment(Rectangle rect, string contents, string filePath, int page, 
    string name, double opacity)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| rect | Rectangle | Rectangle d'annotation définissant l'emplacement de l'annotation sur la page. |
| contents | String | Le contenu de l'annotation. |
| filePath | String | Le chemin du fichier sera joint. |
| page | Int32 | Le numéro de la page d'origine où l'annotation sera créée. |
| name | String | Le nom d'une icône sera utilisé dans l'affichage de l'annotation. Cette valeur peut être : "Graph", "PushPin", "Paperclip", "Tag". |
| opacity | Double | Opacité de l'icône de 0 à 1 : 0 - complètement transparent, 1 - complètement opaque. |

### Exemples

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateFileAttachment(new System.Drawing.Rectangle(0, 0, 100, 100),
    "Welcome to Aspose", "attachment_file.pdf", 1, "Graph", 0.5);
editor.Save("example_out.pdf");
```

### Voir également

* class [PdfContentEditor](../../pdfcontenteditor)
* espace de noms [Aspose.Pdf.Facades](../../pdfcontenteditor)
* Assemblée [Aspose.PDF](../../../)

---

## CreateFileAttachment(Rectangle, string, Stream, string, int, string) {#createfileattachment}

Crée une annotation de pièce jointe.

```csharp
public void CreateFileAttachment(Rectangle rect, string contents, Stream attachmentStream, 
    string attachmentName, int page, string name)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| rect | Rectangle | Rectangle d'annotation définissant l'emplacement de l'annotation sur la page. |
| contents | String | Le contenu de l'annotation. |
| attachmentStream | Stream | Le flux de fichiers joints. |
| attachmentName | String | Le nom de la pièce jointe. |
| page | Int32 | Le numéro de la page d'origine où l'annotation sera créée. |
| name | String | Le nom d'une icône sera utilisé dans l'affichage de l'annotation. Cette valeur peut être : "Graph", "PushPin", "Paperclip", "Tag". |

### Exemples

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
using(System.IO.FileStream attStream = System.IO.File.OpenRead("attachment_file.pdf"))
{
    editor.CreateFileAttachment(new System.Drawing.Rectangle(0, 0, 100, 100),
        "Welcome to Aspose", attStream, "attachment_file.pdf", 1, "Graph");
    editor.Save("example_out.pdf");
}
```

### Voir également

* class [PdfContentEditor](../../pdfcontenteditor)
* espace de noms [Aspose.Pdf.Facades](../../pdfcontenteditor)
* Assemblée [Aspose.PDF](../../../)

---

## CreateFileAttachment(Rectangle, string, Stream, string, int, string, double) {#createfileattachment_1}

Crée une annotation de pièce jointe.

```csharp
public void CreateFileAttachment(Rectangle rect, string contents, Stream attachmentStream, 
    string attachmentName, int page, string name, double opacity)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| rect | Rectangle | Rectangle d'annotation définissant l'emplacement de l'annotation sur la page. |
| contents | String | Le contenu de l'annotation. |
| attachmentStream | Stream | Le flux de fichiers joints. |
| attachmentName | String | Le nom de la pièce jointe. |
| page | Int32 | Le numéro de la page d'origine où l'annotation sera créée. |
| name | String | Le nom d'une icône sera utilisé dans l'affichage de l'annotation. Cette valeur peut être : "Graph", "PushPin", "Paperclip", "Tag". |
| opacity | Double | Opacité de l'icône de 0 à 1 : 0 - complètement transparent, 1 - complètement opaque. |

### Exemples

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
using(System.IO.FileStream attStream = System.IO.File.OpenRead("attachment_file.pdf"))
{
    editor.CreateFileAttachment(new System.Drawing.Rectangle(0, 0, 100, 100),
        "Welcome to Aspose", attStream, "attachment_file.pdf", 1, "Graph", 0.5);
    editor.Save("example_out.pdf");
}
```

### Voir également

* class [PdfContentEditor](../../pdfcontenteditor)
* espace de noms [Aspose.Pdf.Facades](../../pdfcontenteditor)
* Assemblée [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
