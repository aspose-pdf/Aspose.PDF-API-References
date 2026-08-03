---
title: "PdfViewer.PrintDocuments"
second_title: "Aspose.PDF för .NET API‑referens"
description: "PdfViewer‑metod. Skriver ut flera PDF‑dokument med standardskrivare och sidinställningar"
type: docs
weight: 370
url: /sv/net/aspose.pdf.facades/pdfviewer/printdocuments/
---
## PrintDocuments(params Document[]) {#printdocuments}

Skriver ut flera PDF-dokument med standardskrivare och sidinställningar.

```csharp
public static void PrintDocuments(params Document[] documents)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| documents | Document[] | En array av [`Document`](../../../aspose.pdf/document/)‑objekt som representerar PDF‑dokumenten som ska skrivas ut. |

## Anmärkningar

Denna metod möjliggör utskrift av flera PDF‑dokument i ett enda utskriftsjobb.

## Exempel

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

### Se även

* class [Document](../../../aspose.pdf/document/)
* class [PdfViewer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## PrintDocuments(params string[]) {#printdocuments_8}

Skriver ut flera PDF-dokument med standardskrivare och sidinställningar.

```csharp
public static void PrintDocuments(params string[] filePaths)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePaths | String[] | En array av filsökvägar som representerar PDF‑dokumenten som ska skrivas ut. |

## Anmärkningar

Denna metod möjliggör utskrift av flera PDF‑dokument i ett enda utskriftsjobb. Säkerställ att de angivna filsökvägarna är giltiga och åtkomliga.

## Exempel

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

### Se även

* class [PdfViewer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## PrintDocuments(params Stream[]) {#printdocuments_7}

Skriver ut flera PDF-dokument från de angivna strömmarna med standardskrivare och sidinställningar.

```csharp
public static void PrintDocuments(params Stream[] documentStreams)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| documentStreams | Stream[] | En array av strömmar som innehåller PDF‑dokumenten som ska skrivas ut. |

## Anmärkningar

Denna metod möjliggör utskrift av flera PDF‑dokument i en enda operation. Säkerställ att de angivna strömmarna är giltiga och åtkomliga under utskriftsprocessen.

## Exempel

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

### Se även

* class [PdfViewer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## PrintDocuments(PrinterSettings, params Document[]) {#printdocuments_1}

Skriver ut flera PDF-dokument med de angivna skrivarinställningarna.

```csharp
public static void PrintDocuments(PrinterSettings printerSettings, params Document[] documents)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| printerSettings | PrinterSettings | Det [`PrinterSettings`](../../../aspose.pdf.printing/printersettings/)‑objektet som specificerar skrivarinställningarna att använda för utskrift. |
| documents | Document[] | En array av [`Document`](../../../aspose.pdf/document/)‑objekt som representerar PDF‑dokumenten som ska skrivas ut. |

## Anmärkningar

Denna metod möjliggör utskrift av flera PDF‑dokument med anpassade skrivarinställningar.

## Exempel

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

### Se även

* class [PrinterSettings](../../../aspose.pdf.printing/printersettings/)
* class [Document](../../../aspose.pdf/document/)
* class [PdfViewer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## PrintDocuments(PrinterSettings, params string[]) {#printdocuments_6}

Skriver ut flera PDF-dokument med de angivna skrivarinställningarna.

```csharp
public static void PrintDocuments(PrinterSettings printerSettings, params string[] filePaths)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| printerSettings | PrinterSettings | Objektet [`PrinterSettings`](../../../aspose.pdf.printing/printersettings/) som innehåller skrivarkonfigurationsdetaljer. |
| filePaths | String[] | En array av filsökvägar som representerar PDF‑dokumenten som ska skrivas ut. |

## Anmärkningar

Denna metod möjliggör utskrift av flera PDF‑dokument i ett enda utskriftsjobb. Säkerställ att de angivna filsökvägarna är giltiga och åtkomliga.

## Exempel

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

### Se även

* class [PrinterSettings](../../../aspose.pdf.printing/printersettings/)
* class [PdfViewer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## PrintDocuments(PrinterSettings, params Stream[]) {#printdocuments_5}

Skriver ut flera PDF-dokument från de angivna strömmarna med de angivna skrivarinställningarna.

```csharp
public static void PrintDocuments(PrinterSettings printerSettings, params Stream[] documentStreams)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| printerSettings | PrinterSettings | Skrivarinställningarna som ska tillämpas under utskriftsprocessen. |
| documentStreams | Stream[] | En array av strömmar som innehåller PDF‑dokumenten som ska skrivas ut. |

## Anmärkningar

Denna metod möjliggör utskrift av flera PDF‑dokument i en enda operation. Säkerställ att de angivna strömmarna är giltiga och åtkomliga under utskriftsprocessen.

## Exempel

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

### Se även

* class [PrinterSettings](../../../aspose.pdf.printing/printersettings/)
* class [PdfViewer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## PrintDocuments(PrinterSettings, PageSettings, params Document[]) {#printdocuments_2}

Skriver ut flera PDF-dokument med de angivna skrivar- och sidinställningarna.

```csharp
public static void PrintDocuments(PrinterSettings printerSettings, PageSettings pageSettings, 
    params Document[] documents)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| printerSettings | PrinterSettings | Det [`PrinterSettings`](../../../aspose.pdf.printing/printersettings/)‑objektet som specificerar skrivarinställningarna att använda för utskrift. |
| pageSettings | PageSettings | Objektet [`PageSettings`](../../../aspose.pdf.printing/pagesettings/) som specificerar sidinställningarna att använda för utskrift. |
| documents | Document[] | En array av [`Document`](../../../aspose.pdf/document/)‑objekt som representerar PDF‑dokumenten som ska skrivas ut. |

## Anmärkningar

Denna metod möjliggör utskrift av flera PDF-dokument med anpassade skrivare- och sidinställningar.

## Exempel

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

### Se även

* class [PrinterSettings](../../../aspose.pdf.printing/printersettings/)
* class [PageSettings](../../../aspose.pdf.printing/pagesettings/)
* class [Document](../../../aspose.pdf/document/)
* class [PdfViewer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## PrintDocuments(PrinterSettings, PageSettings, params string[]) {#printdocuments_4}

Skriver ut flera PDF-dokument med de angivna skrivar- och sidinställningarna.

```csharp
public static void PrintDocuments(PrinterSettings printerSettings, PageSettings pageSettings, 
    params string[] filePaths)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| printerSettings | PrinterSettings | Objektet [`PrinterSettings`](../../../aspose.pdf.printing/printersettings/) som innehåller skrivarkonfigurationsdetaljer. |
| pageSettings | PageSettings | Objektet [`PageSettings`](../../../aspose.pdf.printing/pagesettings/) som specificerar sidlayout och inställningar. |
| filePaths | String[] | En array av filsökvägar som representerar PDF‑dokumenten som ska skrivas ut. |

## Anmärkningar

Denna metod möjliggör utskrift av flera PDF‑dokument i ett enda utskriftsjobb. Säkerställ att de angivna filsökvägarna är giltiga och åtkomliga.

## Exempel

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

### Se även

* class [PrinterSettings](../../../aspose.pdf.printing/printersettings/)
* class [PageSettings](../../../aspose.pdf.printing/pagesettings/)
* class [PdfViewer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## PrintDocuments(PrinterSettings, PageSettings, params Stream[]) {#printdocuments_3}

Skriver ut flera PDF-dokument från de angivna strömmarna med de angivna skrivar- och sidinställningarna.

```csharp
public static void PrintDocuments(PrinterSettings printerSettings, PageSettings pageSettings, 
    params Stream[] documentStreams)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| printerSettings | PrinterSettings | Skrivarinställningarna som ska tillämpas under utskriftsprocessen. |
| pageSettings | PageSettings | Sidinställningarna som ska tillämpas på varje dokument under utskrift. |
| documentStreams | Stream[] | En array av strömmar som innehåller PDF‑dokumenten som ska skrivas ut. |

## Anmärkningar

Denna metod möjliggör utskrift av flera PDF‑dokument i en enda operation. Säkerställ att de angivna strömmarna är giltiga och åtkomliga under utskriftsprocessen.

## Exempel

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

### Se även

* class [PrinterSettings](../../../aspose.pdf.printing/printersettings/)
* class [PageSettings](../../../aspose.pdf.printing/pagesettings/)
* class [PdfViewer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


