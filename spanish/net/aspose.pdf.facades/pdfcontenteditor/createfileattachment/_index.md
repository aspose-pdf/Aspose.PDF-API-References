---
title: PdfContentEditor.CreateFileAttachment
second_title: Aspose.PDF for .NET API Reference
description: Método PdfContentEditor. Crea una anotación de archivo adjunto
type: docs
weight: 150
url: /es/net/aspose.pdf.facades/pdfcontenteditor/createfileattachment/
---
## CreateFileAttachment(Rectangle, string, string, int, string) {#createfileattachment_2}

Crea una anotación de archivo adjunto.

```csharp
public void CreateFileAttachment(Rectangle rect, string contents, string filePath, int page, 
    string name)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | Rectangle | El rectángulo de anotación que define la ubicación de la anotación en la página. |
| contents | String | El contenido de la anotación. |
| filePath | String | La ruta del archivo que se adjuntará. |
| page | Int32 | El número de la página original donde se creará la anotación. |
| name | String | El nombre de un ícono que se utilizará para mostrar la anotación. Este valor puede ser: "Graph", "PushPin", "Paperclip", "Tag". |

## Ejemplos

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateFileAttachment(new System.Drawing.Rectangle(0, 0, 100, 100),
    "Welcome to Aspose", "attachment_file.pdf", 1, "Graph");
editor.Save("example_out.pdf");
```

### Ver También

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreateFileAttachment(Rectangle, string, string, int, string, double) {#createfileattachment_3}

Crea una anotación de archivo adjunto.

```csharp
public void CreateFileAttachment(Rectangle rect, string contents, string filePath, int page, 
    string name, double opacity)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | Rectangle | El rectángulo de anotación que define la ubicación de la anotación en la página. |
| contents | String | El contenido de la anotación. |
| filePath | String | La ruta del archivo que se adjuntará. |
| page | Int32 | El número de la página original donde se creará la anotación. |
| name | String | El nombre de un ícono que se utilizará para mostrar la anotación. Este valor puede ser: "Graph", "PushPin", "Paperclip", "Tag". |
| opacity | Double | Opacidad del ícono de 0 a 1: 0 - completamente transparente, 1 - completamente opaco. |

## Ejemplos

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateFileAttachment(new System.Drawing.Rectangle(0, 0, 100, 100),
    "Welcome to Aspose", "attachment_file.pdf", 1, "Graph", 0.5);
editor.Save("example_out.pdf");
```

### Ver También

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreateFileAttachment(Rectangle, string, Stream, string, int, string) {#createfileattachment}

Crea una anotación de archivo adjunto.

```csharp
public void CreateFileAttachment(Rectangle rect, string contents, Stream attachmentStream, 
    string attachmentName, int page, string name)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | Rectangle | El rectángulo de anotación que define la ubicación de la anotación en la página. |
| contents | String | El contenido de la anotación. |
| attachmentStream | Stream | El flujo del archivo adjunto. |
| attachmentName | String | El nombre del archivo adjunto. |
| page | Int32 | El número de la página original donde se creará la anotación. |
| name | String | El nombre de un ícono que se utilizará para mostrar la anotación. Este valor puede ser: "Graph", "PushPin", "Paperclip", "Tag". |

## Ejemplos

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

### Ver También

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreateFileAttachment(Rectangle, string, Stream, string, int, string, double) {#createfileattachment_1}

Crea una anotación de archivo adjunto.

```csharp
public void CreateFileAttachment(Rectangle rect, string contents, Stream attachmentStream, 
    string attachmentName, int page, string name, double opacity)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | Rectangle | El rectángulo de anotación que define la ubicación de la anotación en la página. |
| contents | String | El contenido de la anotación. |
| attachmentStream | Stream | El flujo del archivo adjunto. |
| attachmentName | String | El nombre del archivo adjunto. |
| page | Int32 | El número de la página original donde se creará la anotación. |
| name | String | El nombre de un ícono que se utilizará para mostrar la anotación. Este valor puede ser: "Graph", "PushPin", "Paperclip", "Tag". |
| opacity | Double | Opacidad del ícono de 0 a 1: 0 - completamente transparente, 1 - completamente opaco. |

## Ejemplos

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

### Ver También

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)