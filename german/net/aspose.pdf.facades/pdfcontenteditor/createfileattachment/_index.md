---
title: CreateFileAttachment
second_title: Aspose.PDF für .NET-API-Referenz
description: Erstellt Anmerkungen zu Dateianhängen.
type: docs
weight: 150
url: /de/net/aspose.pdf.facades/pdfcontenteditor/createfileattachment/
---
## CreateFileAttachment(Rectangle, string, string, int, string) {#createfileattachment_2}

Erstellt Anmerkungen zu Dateianhängen.

```csharp
public void CreateFileAttachment(Rectangle rect, string contents, string filePath, int page, 
    string name)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | Rectangle | Das Anmerkungsrechteck, das die Position der Anmerkung auf der Seite definiert. |
| contents | String | Der Inhalt der Anmerkung. |
| filePath | String | Der Pfad der Datei wird angehängt. |
| page | Int32 | Die Nummer der Originalseite, auf der die Anmerkung erstellt wird. |
| name | String | Der Name eines Symbols wird beim Anzeigen der Anmerkung verwendet. Dieser Wert kann sein: "Graph", "PushPin", "Paperclip", "Tag". |

### Beispiele

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateFileAttachment(new System.Drawing.Rectangle(0, 0, 100, 100),
    "Welcome to Aspose", "attachment_file.pdf", 1, "Graph");
editor.Save("example_out.pdf");
```

### Siehe auch

* class [PdfContentEditor](../../pdfcontenteditor)
* namensraum [Aspose.Pdf.Facades](../../pdfcontenteditor)
* Montage [Aspose.PDF](../../../)

---

## CreateFileAttachment(Rectangle, string, string, int, string, double) {#createfileattachment_3}

Erstellt Anmerkungen zu Dateianhängen.

```csharp
public void CreateFileAttachment(Rectangle rect, string contents, string filePath, int page, 
    string name, double opacity)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | Rectangle | Das Anmerkungsrechteck, das die Position der Anmerkung auf der Seite definiert. |
| contents | String | Der Inhalt der Anmerkung. |
| filePath | String | Der Pfad der Datei wird angehängt. |
| page | Int32 | Die Nummer der Originalseite, auf der die Anmerkung erstellt wird. |
| name | String | Der Name eines Symbols wird beim Anzeigen der Anmerkung verwendet. Dieser Wert kann sein: "Graph", "PushPin", "Paperclip", "Tag". |
| opacity | Double | Deckkraft des Symbols von 0 bis 1: 0 – vollständig transparent, 1 – vollständig undurchsichtig. |

### Beispiele

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateFileAttachment(new System.Drawing.Rectangle(0, 0, 100, 100),
    "Welcome to Aspose", "attachment_file.pdf", 1, "Graph", 0.5);
editor.Save("example_out.pdf");
```

### Siehe auch

* class [PdfContentEditor](../../pdfcontenteditor)
* namensraum [Aspose.Pdf.Facades](../../pdfcontenteditor)
* Montage [Aspose.PDF](../../../)

---

## CreateFileAttachment(Rectangle, string, Stream, string, int, string) {#createfileattachment}

Erstellt Anmerkungen zu Dateianhängen.

```csharp
public void CreateFileAttachment(Rectangle rect, string contents, Stream attachmentStream, 
    string attachmentName, int page, string name)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | Rectangle | Das Anmerkungsrechteck, das die Position der Anmerkung auf der Seite definiert. |
| contents | String | Der Inhalt der Anmerkung. |
| attachmentStream | Stream | Der Anhangdateistream. |
| attachmentName | String | Der Name des Anhangs. |
| page | Int32 | Die Nummer der Originalseite, auf der die Anmerkung erstellt wird. |
| name | String | Der Name eines Symbols wird beim Anzeigen der Anmerkung verwendet. Dieser Wert kann sein: "Graph", "PushPin", "Paperclip", "Tag". |

### Beispiele

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

### Siehe auch

* class [PdfContentEditor](../../pdfcontenteditor)
* namensraum [Aspose.Pdf.Facades](../../pdfcontenteditor)
* Montage [Aspose.PDF](../../../)

---

## CreateFileAttachment(Rectangle, string, Stream, string, int, string, double) {#createfileattachment_1}

Erstellt Anmerkungen zu Dateianhängen.

```csharp
public void CreateFileAttachment(Rectangle rect, string contents, Stream attachmentStream, 
    string attachmentName, int page, string name, double opacity)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | Rectangle | Das Anmerkungsrechteck, das die Position der Anmerkung auf der Seite definiert. |
| contents | String | Der Inhalt der Anmerkung. |
| attachmentStream | Stream | Der Anhangdateistream. |
| attachmentName | String | Der Name des Anhangs. |
| page | Int32 | Die Nummer der Originalseite, auf der die Anmerkung erstellt wird. |
| name | String | Der Name eines Symbols wird beim Anzeigen der Anmerkung verwendet. Dieser Wert kann sein: "Graph", "PushPin", "Paperclip", "Tag". |
| opacity | Double | Deckkraft des Symbols von 0 bis 1: 0 – vollständig transparent, 1 – vollständig undurchsichtig. |

### Beispiele

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

### Siehe auch

* class [PdfContentEditor](../../pdfcontenteditor)
* namensraum [Aspose.Pdf.Facades](../../pdfcontenteditor)
* Montage [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
