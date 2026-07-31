---
title: "PdfViewer.PrintDocuments"
second_title: "Aspose.PDF für .NET API-Referenz"
description: "PdfViewer-Methode. Druckt mehrere PDF-Dokumente mit den Standarddrucker- und Seiteneinstellungen."
type: docs
weight: 370
url: /de/net/aspose.pdf.facades/pdfviewer/printdocuments/
---
## PrintDocuments(params Document[]) {#printdocuments}

Druckt mehrere PDF-Dokumente mit den Standarddrucker- und Seiteneinstellungen.

```csharp
public static void PrintDocuments(params Document[] documents)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| documents | Document[] | Ein Array von [`Document`](../../../aspose.pdf/document/)‑Objekten, die die zu druckenden PDF-Dokumente darstellen. |

## Hinweise

Diese Methode ermöglicht das Drucken mehrerer PDF-Dokumente in einem einzigen Druckauftrag.

## Beispiele

```csharp
[C#]
using (Aspose.Pdf.Document document1 = new Aspose.Pdf.Document(dataDir + "PrintDocument.pdf"),
                           document2 = new Aspose.Pdf.Document(dataDir + "Print-PageRange.pdf"),
                           document3 = new Aspose.Pdf.Document(dataDir + "35925_1_3.xps", new Aspose.Pdf.XpsLoadOptions()))
{
    Aspose.Pdf.Facades.PdfViewer.PrintDocuments(document1, document2, document3);
}

[VisualBasic]
Using document1 As New Aspose.Pdf.Document(dataDir & "PrintDocument.pdf"),
      document2 As New Aspose.Pdf.Document(dataDir & "Print-PageRange.pdf"),
      document3 As New Aspose.Pdf.Document(dataDir & "35925_1_3.xps", New Aspose.Pdf.XpsLoadOptions())
     Aspose.Pdf.Facades.PdfViewer.PrintDocuments(document1, document2, document3)
End Using
```

### Siehe auch

* class [Document](../../../aspose.pdf/document/)
* class [PdfViewer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## PrintDocuments(params string[]) {#printdocuments_8}

Druckt mehrere PDF-Dokumente mit den Standarddrucker- und Seiteneinstellungen.

```csharp
public static void PrintDocuments(params string[] filePaths)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePaths | String[] | Ein Array von Dateipfaden, die die zu druckenden PDF-Dokumente darstellen. |

## Hinweise

Diese Methode ermöglicht das Drucken mehrerer PDF-Dokumente in einem einzigen Druckauftrag. Stellen Sie sicher, dass die angegebenen Dateipfade gültig und zugänglich sind.

## Beispiele

```csharp
[C#]
var path1 = dataDir + "PrintDocument.pdf";
var path2 = dataDir + "Print-PageRange.pdf";
var path3 = dataDir + "35925_1_3.xps";

Aspose.Pdf.Facades.PdfViewer.PrintDocuments(path1, path2, path3);

[VisualBasic]
Dim path1 As String = dataDir & "PrintDocument.pdf"
Dim path2 As String = dataDir & "Print-PageRange.pdf"
Dim path3 As String = dataDir & "35925_1_3.xps"

Aspose.Pdf.Facades.PdfViewer.PrintDocuments(path1, path2, path3)
```

### Siehe auch

* class [PdfViewer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## PrintDocuments(params Stream[]) {#printdocuments_7}

Druckt mehrere PDF-Dokumente aus den bereitgestellten Streams mit den Standarddrucker- und Seiteneinstellungen.

```csharp
public static void PrintDocuments(params Stream[] documentStreams)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| documentStreams | Stream[] | Ein Array von Streams, die die zu druckenden PDF-Dokumente enthalten. |

## Hinweise

Diese Methode ermöglicht das Drucken mehrerer PDF-Dokumente in einem einzigen Vorgang. Stellen Sie sicher, dass die bereitgestellten Streams während des Druckvorgangs gültig und zugänglich sind.

## Beispiele

```csharp
[C#]
using (Stream stream1 = File.OpenRead(dataDir + "PrintDocument.pdf"),
              stream2 = File.OpenRead(dataDir + "Print-PageRange.pdf"),
              stream3 = File.OpenRead(dataDir + "35925_1_3.xps"))
{
    Aspose.Pdf.Facades.PdfViewer.PrintDocuments(stream1, stream2, stream3);
}

[VisualBasic]
Using stream1 As Stream = File.OpenRead(dataDir & "PrintDocument.pdf"),
      stream2 As Stream = File.OpenRead(dataDir & "Print-PageRange.pdf"),
      stream3 As Stream = File.OpenRead(dataDir & "35925_1_3.xps")
    Aspose.Pdf.Facades.PdfViewer.PrintDocuments(stream1, stream2, stream3)
End Using
```

### Siehe auch

* class [PdfViewer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## PrintDocuments(PrinterSettings, params Document[]) {#printdocuments_1}

Druckt mehrere PDF-Dokumente mit den angegebenen Druckereinstellungen.

```csharp
public static void PrintDocuments(PrinterSettings printerSettings, params Document[] documents)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| printerSettings | PrinterSettings | Das [`PrinterSettings`](../../../aspose.pdf.printing/printersettings/)‑Objekt, das die für den Druck zu verwendenden Druckereinstellungen angibt. |
| documents | Document[] | Ein Array von [`Document`](../../../aspose.pdf/document/)‑Objekten, die die zu druckenden PDF-Dokumente darstellen. |

## Hinweise

Diese Methode ermöglicht das Drucken mehrerer PDF-Dokumente mit benutzerdefinierten Druckereinstellungen.

## Beispiele

```csharp
[C#]
using (Aspose.Pdf.Document document1 = new Aspose.Pdf.Document(dataDir + "PrintDocument.pdf"),
                           document2 = new Aspose.Pdf.Document(dataDir + "Print-PageRange.pdf"),
                           document3 = new Aspose.Pdf.Document(dataDir + "35925_1_3.xps", new Aspose.Pdf.XpsLoadOptions()))
{
    var printDocument = new PrintDocument();
    Aspose.Pdf.Printing.PrinterSettings printerSettings = new Aspose.Pdf.Printing.PrinterSettings();
    printerSettings.PrinterName = printDocument.PrinterSettings.PrinterName;

    Aspose.Pdf.Facades.PdfViewer.PrintDocuments(printerSettings, document1, document2, document3);
}

[VisualBasic]
Using document1 As New Aspose.Pdf.Document(dataDir & "PrintDocument.pdf"),
      document2 As New Aspose.Pdf.Document(dataDir & "Print-PageRange.pdf"),
      document3 As New Aspose.Pdf.Document(dataDir & "35925_1_3.xps", New Aspose.Pdf.XpsLoadOptions())
     Dim printDocument As New PrintDocument()
     Dim printerSettings As New Aspose.Pdf.Printing.PrinterSettings()
     printerSettings.PrinterName = printDocument.PrinterSettings.PrinterName

     Aspose.Pdf.Facades.PdfViewer.PrintDocuments(printerSettings, document1, document2, document3)
End Using
```

### Siehe auch

* class [PrinterSettings](../../../aspose.pdf.printing/printersettings/)
* class [Document](../../../aspose.pdf/document/)
* class [PdfViewer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## PrintDocuments(PrinterSettings, params string[]) {#printdocuments_6}

Druckt mehrere PDF-Dokumente mit den angegebenen Druckereinstellungen.

```csharp
public static void PrintDocuments(PrinterSettings printerSettings, params string[] filePaths)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| printerSettings | PrinterSettings | Das [`PrinterSettings`](../../../aspose.pdf.printing/printersettings/) Objekt, das Druckerkonfigurationsdetails enthält. |
| filePaths | String[] | Ein Array von Dateipfaden, die die zu druckenden PDF-Dokumente darstellen. |

## Hinweise

Diese Methode ermöglicht das Drucken mehrerer PDF-Dokumente in einem einzigen Druckauftrag. Stellen Sie sicher, dass die angegebenen Dateipfade gültig und zugänglich sind.

## Beispiele

```csharp
[C#]
var path1 = dataDir + "PrintDocument.pdf";
var path2 = dataDir + "Print-PageRange.pdf";
var path3 = dataDir + "35925_1_3.xps";

var printDocument = new PrintDocument();
Aspose.Pdf.Printing.PrinterSettings printerSettings = new Aspose.Pdf.Printing.PrinterSettings();
printerSettings.PrinterName = printDocument.PrinterSettings.PrinterName;

Aspose.Pdf.Facades.PdfViewer.PrintDocuments(printerSettings, path1, path2, path3);

[VisualBasic]
Dim path1 As String = dataDir & "PrintDocument.pdf"
Dim path2 As String = dataDir & "Print-PageRange.pdf"
Dim path3 As String = dataDir & "35925_1_3.xps"

Dim printDocument As New PrintDocument()
Dim printerSettings As New Aspose.Pdf.Printing.PrinterSettings()
printerSettings.PrinterName = printDocument.PrinterSettings.PrinterName

Aspose.Pdf.Facades.PdfViewer.PrintDocuments(printerSettings, path1, path2, path3)
```

### Siehe auch

* class [PrinterSettings](../../../aspose.pdf.printing/printersettings/)
* class [PdfViewer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## PrintDocuments(PrinterSettings, params Stream[]) {#printdocuments_5}

Druckt mehrere PDF-Dokumente aus den bereitgestellten Streams unter Verwendung der angegebenen Druckereinstellungen.

```csharp
public static void PrintDocuments(PrinterSettings printerSettings, params Stream[] documentStreams)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| printerSettings | PrinterSettings | Die Druckereinstellungen, die während des Druckvorgangs angewendet werden. |
| documentStreams | Stream[] | Ein Array von Streams, die die zu druckenden PDF-Dokumente enthalten. |

## Hinweise

Diese Methode ermöglicht das Drucken mehrerer PDF-Dokumente in einem einzigen Vorgang. Stellen Sie sicher, dass die bereitgestellten Streams während des Druckvorgangs gültig und zugänglich sind.

## Beispiele

```csharp
[C#]
using (Stream stream1 = File.OpenRead(dataDir + "PrintDocument.pdf"),
              stream2 = File.OpenRead(dataDir + "Print-PageRange.pdf"),
              stream3 = File.OpenRead(dataDir + "35925_1_3.xps"))
{
    var printDocument = new PrintDocument();
    Aspose.Pdf.Printing.PrinterSettings printerSettings = new Aspose.Pdf.Printing.PrinterSettings();
    printerSettings.PrinterName = printDocument.PrinterSettings.PrinterName;

    Aspose.Pdf.Facades.PdfViewer.PrintDocuments(printerSettings, stream1, stream2, stream3);
}

[VisualBasic]
Using stream1 As Stream = File.OpenRead(dataDir & "PrintDocument.pdf"),
      stream2 As Stream = File.OpenRead(dataDir & "Print-PageRange.pdf"),
      stream3 As Stream = File.OpenRead(dataDir & "35925_1_3.xps")
    Dim printDocument As New PrintDocument()
    Dim printerSettings As New Aspose.Pdf.Printing.PrinterSettings()
    printerSettings.PrinterName = printDocument.PrinterSettings.PrinterName

    Aspose.Pdf.Facades.PdfViewer.PrintDocuments(printerSettings, stream1, stream2, stream3)
End Using
```

### Siehe auch

* class [PrinterSettings](../../../aspose.pdf.printing/printersettings/)
* class [PdfViewer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## PrintDocuments(PrinterSettings, PageSettings, params Document[]) {#printdocuments_2}

Druckt mehrere PDF-Dokumente unter Verwendung des angegebenen Druckers und der Seiteneinstellungen.

```csharp
public static void PrintDocuments(PrinterSettings printerSettings, PageSettings pageSettings, 
    params Document[] documents)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| printerSettings | PrinterSettings | Das [`PrinterSettings`](../../../aspose.pdf.printing/printersettings/)‑Objekt, das die für den Druck zu verwendenden Druckereinstellungen angibt. |
| pageSettings | PageSettings | Das [`PageSettings`](../../../aspose.pdf.printing/pagesettings/) Objekt, das die für den Druck zu verwendenden Seiteneinstellungen angibt. |
| documents | Document[] | Ein Array von [`Document`](../../../aspose.pdf/document/)‑Objekten, die die zu druckenden PDF-Dokumente darstellen. |

## Hinweise

Diese Methode ermöglicht das Drucken mehrerer PDF-Dokumente mit benutzerdefinierten Drucker- und Seiteneinstellungen.

## Beispiele

```csharp
[C#]
using (Aspose.Pdf.Document document1 = new Aspose.Pdf.Document(dataDir + "PrintDocument.pdf"),
                           document2 = new Aspose.Pdf.Document(dataDir + "Print-PageRange.pdf"),
                           document3 = new Aspose.Pdf.Document(dataDir + "35925_1_3.xps", new Aspose.Pdf.XpsLoadOptions()))
{
    var printDocument = new PrintDocument();
    Aspose.Pdf.Printing.PrinterSettings printerSettings = new Aspose.Pdf.Printing.PrinterSettings();
    printerSettings.PrinterName = printDocument.PrinterSettings.PrinterName;

    Aspose.Pdf.Printing.PageSettings pageSettings = new Aspose.Pdf.Printing.PageSettings();
    pageSettings.PaperSize = Aspose.Pdf.Printing.PaperSizes.A4;
    pageSettings.Margins = new Aspose.Pdf.Devices.Margins(0, 0, 0, 0);

    Aspose.Pdf.Facades.PdfViewer.PrintDocuments(printerSettings, pageSettings, document1, document2, document3);
}

[VisualBasic]
Using document1 As New Aspose.Pdf.Document(dataDir & "PrintDocument.pdf"),
      document2 As New Aspose.Pdf.Document(dataDir & "Print-PageRange.pdf"),
      document3 As New Aspose.Pdf.Document(dataDir & "35925_1_3.xps", New Aspose.Pdf.XpsLoadOptions())
     Dim printDocument As New PrintDocument()
     Dim printerSettings As New Aspose.Pdf.Printing.PrinterSettings()
     printerSettings.PrinterName = printDocument.PrinterSettings.PrinterName

     Dim pageSettings As New Aspose.Pdf.Printing.PageSettings()
     pageSettings.PaperSize = Aspose.Pdf.Printing.PaperSizes.A4
     pageSettings.Margins = New Aspose.Pdf.Devices.Margins(0, 0, 0, 0)

     Aspose.Pdf.Facades.PdfViewer.PrintDocuments(printerSettings, pageSettings, document1, document2, document3)
End Using
```

### Siehe auch

* class [PrinterSettings](../../../aspose.pdf.printing/printersettings/)
* class [PageSettings](../../../aspose.pdf.printing/pagesettings/)
* class [Document](../../../aspose.pdf/document/)
* class [PdfViewer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## PrintDocuments(PrinterSettings, PageSettings, params string[]) {#printdocuments_4}

Druckt mehrere PDF-Dokumente unter Verwendung des angegebenen Druckers und der Seiteneinstellungen.

```csharp
public static void PrintDocuments(PrinterSettings printerSettings, PageSettings pageSettings, 
    params string[] filePaths)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| printerSettings | PrinterSettings | Das [`PrinterSettings`](../../../aspose.pdf.printing/printersettings/) Objekt, das Druckerkonfigurationsdetails enthält. |
| pageSettings | PageSettings | Das [`PageSettings`](../../../aspose.pdf.printing/pagesettings/) Objekt, das Seitenlayout und -einstellungen spezifiziert. |
| filePaths | String[] | Ein Array von Dateipfaden, die die zu druckenden PDF-Dokumente darstellen. |

## Hinweise

Diese Methode ermöglicht das Drucken mehrerer PDF-Dokumente in einem einzigen Druckauftrag. Stellen Sie sicher, dass die angegebenen Dateipfade gültig und zugänglich sind.

## Beispiele

```csharp
[C#]
var path1 = dataDir + "PrintDocument.pdf";
var path2 = dataDir + "Print-PageRange.pdf";
var path3 = dataDir + "35925_1_3.xps";

var printDocument = new PrintDocument();
Aspose.Pdf.Printing.PrinterSettings printerSettings = new Aspose.Pdf.Printing.PrinterSettings();
printerSettings.PrinterName = printDocument.PrinterSettings.PrinterName;

Aspose.Pdf.Printing.PageSettings pageSettings = new Aspose.Pdf.Printing.PageSettings();
pageSettings.PaperSize = Aspose.Pdf.Printing.PaperSizes.A4;
pageSettings.Margins = new Aspose.Pdf.Devices.Margins(0, 0, 0, 0);

Aspose.Pdf.Facades.PdfViewer.PrintDocuments(printerSettings, pageSettings, path1, path2, path3);

[VisualBasic]
Dim path1 As String = dataDir & "PrintDocument.pdf"
Dim path2 As String = dataDir & "Print-PageRange.pdf"
Dim path3 As String = dataDir & "35925_1_3.xps"

Dim printDocument As New PrintDocument()
Dim printerSettings As New Aspose.Pdf.Printing.PrinterSettings()
printerSettings.PrinterName = printDocument.PrinterSettings.PrinterName

Dim pageSettings As New Aspose.Pdf.Printing.PageSettings()
pageSettings.PaperSize = Aspose.Pdf.Printing.PaperSizes.A4
pageSettings.Margins = New Aspose.Pdf.Devices.Margins(0, 0, 0, 0)

Aspose.Pdf.Facades.PdfViewer.PrintDocuments(printerSettings, pageSettings, path1, path2, path3)
```

### Siehe auch

* class [PrinterSettings](../../../aspose.pdf.printing/printersettings/)
* class [PageSettings](../../../aspose.pdf.printing/pagesettings/)
* class [PdfViewer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## PrintDocuments(PrinterSettings, PageSettings, params Stream[]) {#printdocuments_3}

Druckt mehrere PDF-Dokumente aus den bereitgestellten Streams unter Verwendung des angegebenen Druckers und der Seiteneinstellungen.

```csharp
public static void PrintDocuments(PrinterSettings printerSettings, PageSettings pageSettings, 
    params Stream[] documentStreams)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| printerSettings | PrinterSettings | Die Druckereinstellungen, die während des Druckvorgangs angewendet werden. |
| pageSettings | PageSettings | Die Seiteneinstellungen, die jedem Dokument während des Druckens angewendet werden. |
| documentStreams | Stream[] | Ein Array von Streams, die die zu druckenden PDF-Dokumente enthalten. |

## Hinweise

Diese Methode ermöglicht das Drucken mehrerer PDF-Dokumente in einem einzigen Vorgang. Stellen Sie sicher, dass die bereitgestellten Streams während des Druckvorgangs gültig und zugänglich sind.

## Beispiele

```csharp
[C#]
using (Stream stream1 = File.OpenRead(dataDir + "PrintDocument.pdf"),
              stream2 = File.OpenRead(dataDir + "Print-PageRange.pdf"),
              stream3 = File.OpenRead(dataDir + "35925_1_3.xps"))
{
    var printDocument = new PrintDocument();
    Aspose.Pdf.Printing.PrinterSettings printerSettings = new Aspose.Pdf.Printing.PrinterSettings();
    printerSettings.PrinterName = printDocument.PrinterSettings.PrinterName;

    Aspose.Pdf.Printing.PageSettings pageSettings = new Aspose.Pdf.Printing.PageSettings();
    pageSettings.PaperSize = Aspose.Pdf.Printing.PaperSizes.A4;
    pageSettings.Margins = new Aspose.Pdf.Devices.Margins(0, 0, 0, 0);

    Aspose.Pdf.Facades.PdfViewer.PrintDocuments(printerSettings, pageSettings, stream1, stream2, stream3);
}

[VisualBasic]
Using stream1 As Stream = File.OpenRead(dataDir & "PrintDocument.pdf"),
      stream2 As Stream = File.OpenRead(dataDir & "Print-PageRange.pdf"),
      stream3 As Stream = File.OpenRead(dataDir & "35925_1_3.xps")
    Dim printDocument As New PrintDocument()
    Dim printerSettings As New Aspose.Pdf.Printing.PrinterSettings()
    printerSettings.PrinterName = printDocument.PrinterSettings.PrinterName

    Dim pageSettings As New Aspose.Pdf.Printing.PageSettings()
    pageSettings.PaperSize = Aspose.Pdf.Printing.PaperSizes.A4
    pageSettings.Margins = New Aspose.Pdf.Devices.Margins(0, 0, 0, 0)

    Aspose.Pdf.Facades.PdfViewer.PrintDocuments(printerSettings, pageSettings, stream1, stream2, stream3)
End Using
```

### Siehe auch

* class [PrinterSettings](../../../aspose.pdf.printing/printersettings/)
* class [PageSettings](../../../aspose.pdf.printing/pagesettings/)
* class [PdfViewer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


