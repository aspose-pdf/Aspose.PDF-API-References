---
title: PdfContentEditor.CreateFileAttachment
second_title: Aspose.PDF for .NET API Reference
description: Metodo PdfContentEditor. Crea annotazione di allegato file
type: docs
weight: 150
url: /it/net/aspose.pdf.facades/pdfcontenteditor/createfileattachment/
---
## CreateFileAttachment(Rectangle, string, string, int, string) {#createfileattachment_2}

Crea annotazione di allegato file.

```csharp
public void CreateFileAttachment(Rectangle rect, string contents, string filePath, int page, 
    string name)
```

| Parameter | Type | Description |
| --- | --- | --- |
| rect | Rectangle | Il rettangolo dell'annotazione che definisce la posizione dell'annotazione sulla pagina. |
| contents | String | I contenuti dell'annotazione. |
| filePath | String | Il percorso del file che sarà allegato. |
| page | Int32 | Il numero della pagina originale in cui verrà creata l'annotazione. |
| name | String | Il nome di un'icona che sarà utilizzata per visualizzare l'annotazione. Questo valore può essere: "Graph", "PushPin", "Paperclip", "Tag". |

## Examples

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateFileAttachment(new System.Drawing.Rectangle(0, 0, 100, 100),
    "Welcome to Aspose", "attachment_file.pdf", 1, "Graph");
editor.Save("example_out.pdf");
```

### See Also

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreateFileAttachment(Rectangle, string, string, int, string, double) {#createfileattachment_3}

Crea annotazione di allegato file.

```csharp
public void CreateFileAttachment(Rectangle rect, string contents, string filePath, int page, 
    string name, double opacity)
```

| Parameter | Type | Description |
| --- | --- | --- |
| rect | Rectangle | Il rettangolo dell'annotazione che definisce la posizione dell'annotazione sulla pagina. |
| contents | String | I contenuti dell'annotazione. |
| filePath | String | Il percorso del file che sarà allegato. |
| page | Int32 | Il numero della pagina originale in cui verrà creata l'annotazione. |
| name | String | Il nome di un'icona che sarà utilizzata per visualizzare l'annotazione. Questo valore può essere: "Graph", "PushPin", "Paperclip", "Tag". |
| opacity | Double | Opacità dell'icona da 0 a 1: 0 - completamente trasparente, 1 - completamente opaco. |

## Examples

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateFileAttachment(new System.Drawing.Rectangle(0, 0, 100, 100),
    "Welcome to Aspose", "attachment_file.pdf", 1, "Graph", 0.5);
editor.Save("example_out.pdf");
```

### See Also

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreateFileAttachment(Rectangle, string, Stream, string, int, string) {#createfileattachment}

Crea annotazione di allegato file.

```csharp
public void CreateFileAttachment(Rectangle rect, string contents, Stream attachmentStream, 
    string attachmentName, int page, string name)
```

| Parameter | Type | Description |
| --- | --- | --- |
| rect | Rectangle | Il rettangolo dell'annotazione che definisce la posizione dell'annotazione sulla pagina. |
| contents | String | I contenuti dell'annotazione. |
| attachmentStream | Stream | Il flusso del file di allegato. |
| attachmentName | String | Il nome dell'allegato. |
| page | Int32 | Il numero della pagina originale in cui verrà creata l'annotazione. |
| name | String | Il nome di un'icona che sarà utilizzata per visualizzare l'annotazione. Questo valore può essere: "Graph", "PushPin", "Paperclip", "Tag". |

## Examples

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

### See Also

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreateFileAttachment(Rectangle, string, Stream, string, int, string, double) {#createfileattachment_1}

Crea annotazione di allegato file.

```csharp
public void CreateFileAttachment(Rectangle rect, string contents, Stream attachmentStream, 
    string attachmentName, int page, string name, double opacity)
```

| Parameter | Type | Description |
| --- | --- | --- |
| rect | Rectangle | Il rettangolo dell'annotazione che definisce la posizione dell'annotazione sulla pagina. |
| contents | String | I contenuti dell'annotazione. |
| attachmentStream | Stream | Il flusso del file di allegato. |
| attachmentName | String | Il nome dell'allegato. |
| page | Int32 | Il numero della pagina originale in cui verrà creata l'annotazione. |
| name | String | Il nome di un'icona che sarà utilizzata per visualizzare l'annotazione. Questo valore può essere: "Graph", "PushPin", "Paperclip", "Tag". |
| opacity | Double | Opacità dell'icona da 0 a 1: 0 - completamente trasparente, 1 - completamente opaco. |

## Examples

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

### See Also

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)