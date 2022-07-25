---
title: CreateFileAttachment
second_title: Aspose.PDF per .NET API Reference
description: Crea annotazione file allegato.
type: docs
weight: 150
url: /it/net/aspose.pdf.facades/pdfcontenteditor/createfileattachment/
---
## CreateFileAttachment(Rectangle, string, string, int, string) {#createfileattachment_2}

Crea annotazione file allegato.

```csharp
public void CreateFileAttachment(Rectangle rect, string contents, string filePath, int page, 
    string name)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rect | Rectangle | Il rettangolo di annotazione che definisce la posizione dell'annotazione sulla pagina. |
| contents | String | Il contenuto dell'annotazione. |
| filePath | String | Il percorso del file verrà allegato. |
| page | Int32 | Il numero della pagina originale in cui verrà creata l'annotazione. |
| name | String | Il nome di un'icona verrà utilizzato nella visualizzazione dell'annotazione. Questo valore può essere: "Graph", "PushPin", "Paperclip", "Tag". |

### Esempi

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateFileAttachment(new System.Drawing.Rectangle(0, 0, 100, 100),
    "Welcome to Aspose", "attachment_file.pdf", 1, "Graph");
editor.Save("example_out.pdf");
```

### Guarda anche

* class [PdfContentEditor](../../pdfcontenteditor)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdfcontenteditor)
* assemblea [Aspose.PDF](../../../)

---

## CreateFileAttachment(Rectangle, string, string, int, string, double) {#createfileattachment_3}

Crea annotazione file allegato.

```csharp
public void CreateFileAttachment(Rectangle rect, string contents, string filePath, int page, 
    string name, double opacity)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rect | Rectangle | Il rettangolo di annotazione che definisce la posizione dell'annotazione sulla pagina. |
| contents | String | Il contenuto dell'annotazione. |
| filePath | String | Il percorso del file verrà allegato. |
| page | Int32 | Il numero della pagina originale in cui verrà creata l'annotazione. |
| name | String | Il nome di un'icona verrà utilizzato nella visualizzazione dell'annotazione. Questo valore può essere: "Graph", "PushPin", "Paperclip", "Tag". |
| opacity | Double | Opacità dell'icona da 0 a 1: 0 - completamente trasparente, 1 - completamente opaca. |

### Esempi

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateFileAttachment(new System.Drawing.Rectangle(0, 0, 100, 100),
    "Welcome to Aspose", "attachment_file.pdf", 1, "Graph", 0.5);
editor.Save("example_out.pdf");
```

### Guarda anche

* class [PdfContentEditor](../../pdfcontenteditor)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdfcontenteditor)
* assemblea [Aspose.PDF](../../../)

---

## CreateFileAttachment(Rectangle, string, Stream, string, int, string) {#createfileattachment}

Crea annotazione file allegato.

```csharp
public void CreateFileAttachment(Rectangle rect, string contents, Stream attachmentStream, 
    string attachmentName, int page, string name)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rect | Rectangle | Il rettangolo di annotazione che definisce la posizione dell'annotazione sulla pagina. |
| contents | String | Il contenuto dell'annotazione. |
| attachmentStream | Stream | Il flusso del file allegato. |
| attachmentName | String | Il nome dell'allegato. |
| page | Int32 | Il numero della pagina originale in cui verrà creata l'annotazione. |
| name | String | Il nome di un'icona verrà utilizzato nella visualizzazione dell'annotazione. Questo valore può essere: "Graph", "PushPin", "Paperclip", "Tag". |

### Esempi

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

### Guarda anche

* class [PdfContentEditor](../../pdfcontenteditor)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdfcontenteditor)
* assemblea [Aspose.PDF](../../../)

---

## CreateFileAttachment(Rectangle, string, Stream, string, int, string, double) {#createfileattachment_1}

Crea annotazione file allegato.

```csharp
public void CreateFileAttachment(Rectangle rect, string contents, Stream attachmentStream, 
    string attachmentName, int page, string name, double opacity)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rect | Rectangle | Il rettangolo di annotazione che definisce la posizione dell'annotazione sulla pagina. |
| contents | String | Il contenuto dell'annotazione. |
| attachmentStream | Stream | Il flusso del file allegato. |
| attachmentName | String | Il nome dell'allegato. |
| page | Int32 | Il numero della pagina originale in cui verrà creata l'annotazione. |
| name | String | Il nome di un'icona verrà utilizzato nella visualizzazione dell'annotazione. Questo valore può essere: "Graph", "PushPin", "Paperclip", "Tag". |
| opacity | Double | Opacità dell'icona da 0 a 1: 0 - completamente trasparente, 1 - completamente opaca. |

### Esempi

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

### Guarda anche

* class [PdfContentEditor](../../pdfcontenteditor)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdfcontenteditor)
* assemblea [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
