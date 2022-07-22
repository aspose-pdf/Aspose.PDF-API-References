---
title: CreateFileAttachment
second_title: Referencia de API de Aspose.PDF para .NET
description: Crea una anotación de archivos adjuntos.
type: docs
weight: 150
url: /es/net/aspose.pdf.facades/pdfcontenteditor/createfileattachment/
---
## CreateFileAttachment(Rectangle, string, string, int, string) {#createfileattachment_2}

Crea una anotación de archivos adjuntos.

```csharp
public void CreateFileAttachment(Rectangle rect, string contents, string filePath, int page, 
    string name)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| rect | Rectangle | El rectángulo de anotación que define la ubicación de la anotación en la página. |
| contents | String | El contenido de la anotación. |
| filePath | String | Se adjuntará la ruta del archivo. |
| page | Int32 | El número de página original donde se creará la anotación. |
| name | String | El nombre de un icono se utilizará para mostrar la anotación. Este valor puede ser: "Gráfico", "PushPin", "Paperclip", "Tag". |

### Ejemplos

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateFileAttachment(new System.Drawing.Rectangle(0, 0, 100, 100),
    "Welcome to Aspose", "attachment_file.pdf", 1, "Graph");
editor.Save("example_out.pdf");
```

### Ver también

* class [PdfContentEditor](../../pdfcontenteditor)
* espacio de nombres [Aspose.Pdf.Facades](../../pdfcontenteditor)
* asamblea [Aspose.PDF](../../../)

---

## CreateFileAttachment(Rectangle, string, string, int, string, double) {#createfileattachment_3}

Crea una anotación de archivos adjuntos.

```csharp
public void CreateFileAttachment(Rectangle rect, string contents, string filePath, int page, 
    string name, double opacity)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| rect | Rectangle | El rectángulo de anotación que define la ubicación de la anotación en la página. |
| contents | String | El contenido de la anotación. |
| filePath | String | Se adjuntará la ruta del archivo. |
| page | Int32 | El número de página original donde se creará la anotación. |
| name | String | El nombre de un icono se utilizará para mostrar la anotación. Este valor puede ser: "Gráfico", "PushPin", "Paperclip", "Tag". |
| opacity | Double | Opacidad del icono de 0 a 1: 0 - completamente transparente, 1 - completamente opaco. |

### Ejemplos

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateFileAttachment(new System.Drawing.Rectangle(0, 0, 100, 100),
    "Welcome to Aspose", "attachment_file.pdf", 1, "Graph", 0.5);
editor.Save("example_out.pdf");
```

### Ver también

* class [PdfContentEditor](../../pdfcontenteditor)
* espacio de nombres [Aspose.Pdf.Facades](../../pdfcontenteditor)
* asamblea [Aspose.PDF](../../../)

---

## CreateFileAttachment(Rectangle, string, Stream, string, int, string) {#createfileattachment}

Crea una anotación de archivos adjuntos.

```csharp
public void CreateFileAttachment(Rectangle rect, string contents, Stream attachmentStream, 
    string attachmentName, int page, string name)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| rect | Rectangle | El rectángulo de anotación que define la ubicación de la anotación en la página. |
| contents | String | El contenido de la anotación. |
| attachmentStream | Stream | El flujo de archivos adjuntos. |
| attachmentName | String | El nombre del archivo adjunto. |
| page | Int32 | El número de página original donde se creará la anotación. |
| name | String | El nombre de un icono se utilizará para mostrar la anotación. Este valor puede ser: "Gráfico", "PushPin", "Paperclip", "Tag". |

### Ejemplos

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

### Ver también

* class [PdfContentEditor](../../pdfcontenteditor)
* espacio de nombres [Aspose.Pdf.Facades](../../pdfcontenteditor)
* asamblea [Aspose.PDF](../../../)

---

## CreateFileAttachment(Rectangle, string, Stream, string, int, string, double) {#createfileattachment_1}

Crea una anotación de archivos adjuntos.

```csharp
public void CreateFileAttachment(Rectangle rect, string contents, Stream attachmentStream, 
    string attachmentName, int page, string name, double opacity)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| rect | Rectangle | El rectángulo de anotación que define la ubicación de la anotación en la página. |
| contents | String | El contenido de la anotación. |
| attachmentStream | Stream | El flujo de archivos adjuntos. |
| attachmentName | String | El nombre del archivo adjunto. |
| page | Int32 | El número de página original donde se creará la anotación. |
| name | String | El nombre de un icono se utilizará para mostrar la anotación. Este valor puede ser: "Gráfico", "PushPin", "Paperclip", "Tag". |
| opacity | Double | Opacidad del icono de 0 a 1: 0 - completamente transparente, 1 - completamente opaco. |

### Ejemplos

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

### Ver también

* class [PdfContentEditor](../../pdfcontenteditor)
* espacio de nombres [Aspose.Pdf.Facades](../../pdfcontenteditor)
* asamblea [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
