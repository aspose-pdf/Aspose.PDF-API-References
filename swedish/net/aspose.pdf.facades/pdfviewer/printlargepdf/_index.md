---
title: PdfViewer.PrintLargePdf
second_title: Aspose.PDF for .NET API Reference
description: PdfViewer-metod. Öppnar och skriver ut en stor Pdf-fil. Om din Pdf-fil har hundratals sidor eller mer eller dess storlek är mer än 3 MB rekommenderas denna metod för att få bättre prestanda
type: docs
weight: 350
url: /sv/net/aspose.pdf.facades/pdfviewer/printlargepdf/
---
## PrintLargePdf(string) {#printlargepdf_3}

Öppnar och skriver ut en stor Pdf-fil. Om din Pdf-fil har hundratals sidor eller mer eller dess storlek är mer än 3 MB, rekommenderas denna metod för att få bättre prestanda.

```csharp
public void PrintLargePdf(string filePath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePath | Sträng | Sökvägen till Pdf-filen. |

## Anmärkningar

Denna metod integrerar öppnandet och utskriften av filen och du behöver inte anropa BindPdf() explicit.

## Exempel

```csharp
[C#]
dfViewer viewer = new PdfViewer();
iewer.AutoResize = true;     //print the file with adjusted size
iewer.AutoRotate = true;     //print the file with adjusted rotation
iewer.PrintPageDialog=false; //do not produce the page number dialog when printing
iewer.PrintLargePdf(@"d:\test.pdf");
iewer.Close();

VisualBasic]
im viewer As New PdfViewer()
iewer.AutoResize = True       'print the file with adjusted size
iewer.AutoRotate = True       'print the file with adjusted rotation
iewer.PrintPageDialog = False 'do not produce the page number dialog when printing
iewer.PrintLargePdf(@"d:\test.pdf")
iewer.Close()
```

### Se Även

* klass [PdfViewer](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## PrintLargePdf(Stream) {#printlargepdf}

Öppnar och skriver ut en stor Pdf-ström. Om din Pdf-fil har hundratals sidor eller mer eller dess storlek är mer än 3 MB, rekommenderas denna metod för att få bättre prestanda.

```csharp
public void PrintLargePdf(Stream inputStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputStream | Ström | Pdf-strömmen som ska öppnas och skrivas ut. |

## Anmärkningar

Denna metod integrerar öppnandet och utskriften av filen och du behöver inte anropa BindPdf() explicit.

## Exempel

```csharp
[C#]
dfViewer viewer = new PdfViewer();
iewer.AutoResize = true;        //print the file with adjusted size
iewer.AutoRotate = true;        //print the file with adjusted rotation
iewer.PrintPageDialog=false;    //do not produce the page number dialog when printing
iewer.PrintLargePdf(new MemoryStream(File.ReadAllBytes(@"d:\test.pdf")));
iewer.Close();

VisualBasic]
im viewer As New PdfViewer()
iewer.AutoResize = True         'print the file with adjusted size
iewer.AutoRotate = True         'print the file with adjusted rotation
iewer.PrintPageDialog = False   'do not produce the page number dialog when printing
iewer.PrintLargePdf(new MemoryStream(File.ReadAllBytes(@"d:\test.pdf")))
iewer.Close()
```

### Se Även

* klass [PdfViewer](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## PrintLargePdf(string, PrinterSettings) {#printlargepdf_5}

Öppnar och skriver ut en stor Pdf-fil med angivna skrivareinställningar. Om din Pdf-fil har hundratals sidor eller mer eller dess storlek är mer än 3 MB, rekommenderas denna metod för att få bättre prestanda.

```csharp
public void PrintLargePdf(string filePath, PrinterSettings printerSettings)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePath | Sträng | Sökvägen till Pdf-filen. |
| printerSettings | PrinterSettings | Skrivareinställningarna. |

## Anmärkningar

Denna metod integrerar öppnandet och utskriften av filen och du behöver inte anropa BindPdf() explicit.

## Exempel

```csharp
[C#]
dfViewer viewer = new PdfViewer();
iewer.AutoResize = true;       //print the file with adjusted size
iewer.AutoRotate = true;       //print the file with adjusted rotation
iewer.PrintPageDialog = false; //do not produce the page number dialog when printing
spose.Pdf.Printing.PrinterSettings ps = new Aspose.Pdf.Printing.PrinterSettings();
rintDocument prtdoc = new PrintDocument();
s.PrinterName = prtdoc.PrinterSettings.PrinterName;
iewer.PrintLargePdf(@"d:\test.pdf",ps);
iewer.Close();

VisualBasic]
im viewer As New PdfViewer()
iewer.AutoResize = True        'print the file with adjusted size
iewer.AutoRotate = True        'print the file with adjusted rotation
iewer.PrintPageDialog = False  'do not produce the page number dialog when printing
im ps As New Aspose.Pdf.Printing.PrinterSettings()
im prtdoc As New PrintDocument()
s.PrinterName = prtdoc.PrinterSettings.PrinterName
iewer.PrintLargePdf(@"d:\test.pdf",ps)
iewer.Close()
```

### Se Även

* klass [PrinterSettings](../../../aspose.pdf.printing/printersettings/)
* klass [PdfViewer](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## PrintLargePdf(Stream, PrinterSettings) {#printlargepdf_2}

Öppnar och skriver ut en stor Pdf-ström med angivna skrivareinställningar. Om din Pdf-fil har hundratals sidor eller mer eller dess storlek är mer än 3 MB, rekommenderas denna metod för att få bättre prestanda.

```csharp
public void PrintLargePdf(Stream inputStream, PrinterSettings printerSettings)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputStream | Ström | Pdf-strömmen som ska öppnas och skrivas ut. |
| printerSettings | PrinterSettings | Skrivareinställningarna. |

## Anmärkningar

Denna metod integrerar öppnandet och utskriften av filen och du behöver inte anropa BindPdf() explicit.

## Exempel

```csharp
[C#]
dfViewer viewer = new PdfViewer();
iewer.AutoResize = true;       //print the file with adjusted size
iewer.AutoRotate = true;       //print the file with adjusted rotation
iewer.PrintPageDialog = false; //do not produce the page number dialog when printing
spose.Pdf.Printing.PrinterSettings ps = new Aspose.Pdf.Printing.PrinterSettings();
rintDocument prtdoc = new PrintDocument();
s.PrinterName = prtdoc.PrinterSettings.PrinterName;
iewer.PrintLargePdf(new MemoryStream(File.ReadAllBytes(@"d:\middleware.pdf")),ps);
iewer.Close();

VisualBasic]
im viewer As New PdfViewer()
iewer.AutoResize = True        'print the file with adjusted size
iewer.AutoRotate = True        'print the file with adjusted rotation
iewer.PrintPageDialog = False  'do not produce the page number dialog when printing
im ps As New Aspose.Pdf.Printing.PrinterSettings()
im prtdoc As New PrintDocument()
s.PrinterName = prtdoc.PrinterSettings.PrinterName
iewer.PrintLargePdf(new MemoryStream(File.ReadAllBytes(@"d:\middleware.pdf")),ps)
iewer.Close()
```

### Se Även

* klass [PrinterSettings](../../../aspose.pdf.printing/printersettings/)
* klass [PdfViewer](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## PrintLargePdf(string, PageSettings, PrinterSettings) {#printlargepdf_4}

Öppnar och skriver ut en stor Pdf-fil med angivna sidinställningar och skrivareinställningar. Om din Pdf-fil har hundratals sidor eller mer eller dess storlek är mer än 3 MB, rekommenderas denna metod för att få bättre prestanda.

```csharp
public void PrintLargePdf(string filePath, PageSettings pageSettings, 
    PrinterSettings printerSettings)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePath | Sträng | Sökvägen till Pdf-filen. |
| pageSettings | PageSettings | Sidinställningarna. |
| printerSettings | PrinterSettings | Skrivareinställningarna. |

## Anmärkningar

Denna metod integrerar öppnandet och utskriften av filen och du behöver inte anropa BindPdf() explicit.

## Exempel

```csharp
[C#]
dfViewer viewer = new PdfViewer();
iewer.AutoResize = true;       //print the file with adjusted size
iewer.AutoRotate = true;       //print the file with adjusted rotation
iewer.PrintPageDialog = false; //do not produce the page number dialog when printing
spose.Pdf.Printing.PrinterSettings ps = new Aspose.Pdf.Printing.PrinterSettings();
rintDocument prtdoc = new PrintDocument();
s.PrinterName = prtdoc.PrinterSettings.PrinterName;
spose.Pdf.Printing.PageSettings pgs = new Aspose.Pdf.Printing.PageSettings();
gs.PaperSize = new Aspose.Pdf.Printing.PaperSize("A4", 827, 1169);
gs.Margins = new Aspose.Pdf.Devices.Margins(0, 0, 0, 0);
iewer.PrintLargePdf(@"d:\test.pdf",pgs,ps);
iewer.Close();

VisualBasic]
im viewer As New PdfViewer()
iewer.AutoResize = True       'print the file with adjusted size
iewer.AutoRotate = True       'print the file with adjusted rotation
iewer.PrintPageDialog = False 'do not produce the page number dialog when printing
im ps As New Aspose.Pdf.Printing.PrinterSettings()
im prtdoc As New PrintDocument()
s.PrinterName = prtdoc.PrinterSettings.PrinterName
im pgs As New Aspose.Pdf.Printing.PageSettings()
gs.PaperSize = New Aspose.Pdf.Printing.PaperSize("A4", 827, 1169)
gs.Margins = New Aspose.Pdf.Devices.Margins(0, 0, 0, 0)
iewer.PrintLargePdf(@"d:\test.pdf",pgs,ps)
iewer.Close()
```

### Se Även

* klass [PageSettings](../../../aspose.pdf.printing/pagesettings/)
* klass [PrinterSettings](../../../aspose.pdf.printing/printersettings/)
* klass [PdfViewer](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## PrintLargePdf(Stream, PageSettings, PrinterSettings) {#printlargepdf_1}

Öppnar och skriver ut en stor Pdf-ström med angivna sidinställningar och skrivareinställningar. Om din Pdf-fil har hundratals sidor eller mer eller dess storlek är mer än 3 MB, rekommenderas denna metod för att få bättre prestanda.

```csharp
public void PrintLargePdf(Stream inputStream, PageSettings pageSettings, 
    PrinterSettings printerSettings)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputStream | Ström | Pdf-strömmen som ska öppnas och skrivas ut. |
| pageSettings | PageSettings | Sidinställningarna. |
| printerSettings | PrinterSettings | Skrivareinställningarna. |

## Anmärkningar

Denna metod integrerar öppnandet och utskriften av filen och du behöver inte anropa BindPdf() explicit.

## Exempel

```csharp
[C#]
dfViewer viewer = new PdfViewer();
iewer.AutoResize = true;       //print the file with adjusted size
iewer.AutoRotate = true;       //print the file with adjusted rotation
iewer.PrintPageDialog = false; //do not produce the page number dialog when printing
spose.Pdf.Printing.PrinterSettings ps = new Aspose.Pdf.Printing.PrinterSettings();
rintDocument prtdoc = new PrintDocument();
s.PrinterName = prtdoc.PrinterSettings.PrinterName;
spose.Pdf.Printing.PageSettings pgs = new Aspose.Pdf.Printing.PageSettings();
gs.PaperSize = new Aspose.Pdf.Printing.PaperSize("A4", 827, 1169);
gs.Margins = new Aspose.Pdf.Devices.Margins(0, 0, 0, 0);
iewer.PrintLargePdf(new MemoryStream(File.ReadAllBytes(@"d:\middleware.pdf")),pgs,ps);
iewer.Close();

VisualBasic]
im viewer As New PdfViewer()
iewer.AutoResize = True       'print the file with adjusted size
iewer.AutoRotate = True       'print the file with adjusted rotation
iewer.PrintPageDialog = False 'do not produce the page number dialog when printing
im ps As New Aspose.Pdf.Printing.PrinterSettings()
im prtdoc As New PrintDocument()
s.PrinterName = prtdoc.PrinterSettings.PrinterName
im pgs As New Aspose.Pdf.Printing.PageSettings()
gs.PaperSize = New Aspose.Pdf.Printing.PaperSize("A4", 827, 1169)
gs.Margins = New Aspose.Pdf.Devices.Margins(0, 0, 0, 0)
iewer.PrintLargePdf(new MemoryStream(File.ReadAllBytes(@"d:\middleware.pdf")),pgs,ps)
iewer.Close()
```

### Se Även

* klass [PageSettings](../../../aspose.pdf.printing/pagesettings/)
* klass [PrinterSettings](../../../aspose.pdf.printing/printersettings/)
* klass [PdfViewer](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)