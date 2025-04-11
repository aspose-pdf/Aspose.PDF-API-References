---
title: PdfContentEditor.CreateFileAttachment
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor-Methode. Erstellt eine Dateianhang-Anmerkung
type: docs
weight: 150
url: /de/net/aspose.pdf.facades/pdfcontenteditor/createfileattachment/
---
## CreateFileAttachment(Rectangle, string, string, int, string) {#createfileattachment_2}

Erstellt eine Dateianhang-Anmerkung.

```csharp
public void CreateFileAttachment(Rectangle rect, string contents, string filePath, int page, 
    string name)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | Rectangle | Das Anmerkungsrechteck, das den Standort der Anmerkung auf der Seite definiert. |
| contents | String | Der Inhalt der Anmerkung. |
| filePath | String | Der Pfad der Datei, die angehängt wird. |
| page | Int32 | Die Nummer der Originalseite, auf der die Anmerkung erstellt wird. |
| name | String | Der Name eines Symbols, das zur Anzeige der Anmerkung verwendet wird. Dieser Wert kann sein: "Graph", "PushPin", "Paperclip", "Tag". |

## Beispiele

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateFileAttachment(new System.Drawing.Rectangle(0, 0, 100, 100),
    "Welcome to Aspose", "attachment_file.pdf", 1, "Graph");
editor.Save("example_out.pdf");
```

### Siehe auch

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreateFileAttachment(Rectangle, string, string, int, string, double) {#createfileattachment_3}

Erstellt eine Dateianhang-Anmerkung.

```csharp
public void CreateFileAttachment(Rectangle rect, string contents, string filePath, int page, 
    string name, double opacity)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | Rectangle | Das Anmerkungsrechteck, das den Standort der Anmerkung auf der Seite definiert. |
| contents | String | Der Inhalt der Anmerkung. |
| filePath | String | Der Pfad der Datei, die angehängt wird. |
| page | Int32 | Die Nummer der Originalseite, auf der die Anmerkung erstellt wird. |
| name | String | Der Name eines Symbols, das zur Anzeige der Anmerkung verwendet wird. Dieser Wert kann sein: "Graph", "PushPin", "Paperclip", "Tag". |
| opacity | Double | Die Opazität des Symbols von 0 bis 1: 0 - vollständig transparent, 1 - vollständig undurchsichtig. |

## Beispiele

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateFileAttachment(new System.Drawing.Rectangle(0, 0, 100, 100),
    "Welcome to Aspose", "attachment_file.pdf", 1, "Graph", 0.5);
editor.Save("example_out.pdf");
```

### Siehe auch

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreateFileAttachment(Rectangle, string, Stream, string, int, string) {#createfileattachment}

Erstellt eine Dateianhang-Anmerkung.

```csharp
public void CreateFileAttachment(Rectangle rect, string contents, Stream attachmentStream, 
    string attachmentName, int page, string name)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | Rectangle | Das Anmerkungsrechteck, das den Standort der Anmerkung auf der Seite definiert. |
| contents | String | Der Inhalt der Anmerkung. |
| attachmentStream | Stream | Der Anhang-Dateistream. |
| attachmentName | String | Der Name des Anhangs. |
| page | Int32 | Die Nummer der Originalseite, auf der die Anmerkung erstellt wird. |
| name | String | Der Name eines Symbols, das zur Anzeige der Anmerkung verwendet wird. Dieser Wert kann sein: "Graph", "PushPin", "Paperclip", "Tag". |

## Beispiele

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

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreateFileAttachment(Rectangle, string, Stream, string, int, string, double) {#createfileattachment_1}

Erstellt eine Dateianhang-Anmerkung.

```csharp
public void CreateFileAttachment(Rectangle rect, string contents, Stream attachmentStream, 
    string attachmentName, int page, string name, double opacity)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | Rectangle | Das Anmerkungsrechteck, das den Standort der Anmerkung auf der Seite definiert. |
| contents | String | Der Inhalt der Anmerkung. |
| attachmentStream | Stream | Der Anhang-Dateistream. |
| attachmentName | String | Der Name des Anhangs. |
| page | Int32 | Die Nummer der Originalseite, auf der die Anmerkung erstellt wird. |
| name | String | Der Name eines Symbols, das zur Anzeige der Anmerkung verwendet wird. Dieser Wert kann sein: "Graph", "PushPin", "Paperclip", "Tag". |
| opacity | Double | Die Opazität des Symbols von 0 bis 1: 0 - vollständig transparent, 1 - vollständig undurchsichtig. |

## Beispiele

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

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)