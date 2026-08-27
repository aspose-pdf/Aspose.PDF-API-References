---
title: "PdfContentEditor.CreateFileAttachment"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "PdfContentEditor method. Crée une annotation de pièce jointe de fichier"
type: docs
weight: 150
url: /fr/net/aspose.pdf.facades/pdfcontenteditor/createfileattachment/
---
## CreateFileAttachment(Rectangle, string, string, int, string) {#createfileattachment_2}

Crée une annotation de pièce jointe de fichier.

```csharp
public void CreateFileAttachment(Rectangle rect, string contents, string filePath, int page, 
    string name)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| rect | Rectangle | Le rectangle d'annotation définissant l'emplacement de l'annotation sur la page. |
| contents | String | Le contenu de l'annotation. |
| filePath | String | Le chemin du fichier sera joint. |
| page | Int32 | Le numéro de la page d'origine où l'annotation sera créée. |
| nom | String | Le nom d'une icône sera utilisé lors de l'affichage de l'annotation. Cette valeur peut être : "Graph", "PushPin", "Paperclip", "Tag". |

## Exemples

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateFileAttachment(new System.Drawing.Rectangle(0, 0, 100, 100),
    "Welcome to Aspose", "attachment_file.pdf", 1, "Graph");
editor.Save("example_out.pdf");
```

### Voir aussi

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreateFileAttachment(Rectangle, string, string, int, string, double) {#createfileattachment_3}

Crée une annotation de pièce jointe de fichier.

```csharp
public void CreateFileAttachment(Rectangle rect, string contents, string filePath, int page, 
    string name, double opacity)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| rect | Rectangle | Le rectangle d'annotation définissant l'emplacement de l'annotation sur la page. |
| contents | String | Le contenu de l'annotation. |
| filePath | String | Le chemin du fichier sera joint. |
| page | Int32 | Le numéro de la page d'origine où l'annotation sera créée. |
| nom | String | Le nom d'une icône sera utilisé lors de l'affichage de l'annotation. Cette valeur peut être : "Graph", "PushPin", "Paperclip", "Tag". |
| opacité | Double | Opacité de l'icône de 0 à 1 : 0 - complètement transparent, 1 - complètement opaque. |

## Exemples

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateFileAttachment(new System.Drawing.Rectangle(0, 0, 100, 100),
    "Welcome to Aspose", "attachment_file.pdf", 1, "Graph", 0.5);
editor.Save("example_out.pdf");
```

### Voir aussi

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreateFileAttachment(Rectangle, string, Stream, string, int, string) {#createfileattachment}

Crée une annotation de pièce jointe de fichier.

```csharp
public void CreateFileAttachment(Rectangle rect, string contents, Stream attachmentStream, 
    string attachmentName, int page, string name)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| rect | Rectangle | Le rectangle d'annotation définissant l'emplacement de l'annotation sur la page. |
| contents | String | Le contenu de l'annotation. |
| attachmentStream | Stream | Le flux du fichier de la pièce jointe. |
| attachmentName | String | Le nom de la pièce jointe. |
| page | Int32 | Le numéro de la page d'origine où l'annotation sera créée. |
| nom | String | Le nom d'une icône sera utilisé lors de l'affichage de l'annotation. Cette valeur peut être : "Graph", "PushPin", "Paperclip", "Tag". |

## Exemples

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

### Voir aussi

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreateFileAttachment(Rectangle, string, Stream, string, int, string, double) {#createfileattachment_1}

Crée une annotation de pièce jointe de fichier.

```csharp
public void CreateFileAttachment(Rectangle rect, string contents, Stream attachmentStream, 
    string attachmentName, int page, string name, double opacity)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| rect | Rectangle | Le rectangle d'annotation définissant l'emplacement de l'annotation sur la page. |
| contents | String | Le contenu de l'annotation. |
| attachmentStream | Stream | Le flux du fichier de la pièce jointe. |
| attachmentName | String | Le nom de la pièce jointe. |
| page | Int32 | Le numéro de la page d'origine où l'annotation sera créée. |
| nom | String | Le nom d'une icône sera utilisé lors de l'affichage de l'annotation. Cette valeur peut être : "Graph", "PushPin", "Paperclip", "Tag". |
| opacité | Double | Opacité de l'icône de 0 à 1 : 0 - complètement transparent, 1 - complètement opaque. |

## Exemples

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

### Voir aussi

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


