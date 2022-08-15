---
title: PrintLargePdf
second_title: Aspose.PDF för .NET API Referens
description: Öppnar och skriver ut en stor pdf-fil. Om din Pdf-fil har hundratals sidor eller fler eller dess storlek är mer än 3 MB rekommenderas denna metod för att få bättre prestanda.
type: docs
weight: 320
url: /sv/net/aspose.pdf.facades/pdfviewer/printlargepdf/
---
## PrintLargePdf(string) {#printlargepdf_3}

Öppnar och skriver ut en stor pdf-fil. Om din Pdf-fil har hundratals sidor eller fler eller dess storlek är mer än 3 MB, rekommenderas denna metod för att få bättre prestanda.

```csharp
public void PrintLargePdf(string filePath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePath | String | Sökvägen till pdf-fil. |

### Anmärkningar

Denna metod har integrerat öppningen och utskriften av filen och du behöver inte anropa OpenPdfFile() explicit.

### Exempel

```csharp
[C#]
dfViewer viewer = new PdfViewer();
iewer.AutoResize = true;     //skriv ut filen med anpassad storlek
iewer.AutoRotate = true;     //skriv ut filen med justerad rotation
iewer.PrintPageDialog=false;// skapa inte sidnummerdialogrutan vid utskrift
iewer.PrintLargePdf(@"d:\test.pdf");

VisualBasic]
im viewer As PdfViewer = new PdfViewer();
iewer.AutoResize = true      'skriv ut filen med anpassad storlek
iewer.AutoRotate = true      'skriv ut filen med justerad rotation
iewer.PrintPageDialog=false;// skapa inte sidnummerdialogrutan vid utskrift
iewer.PrintLargePdf(@"d:\test.pdf")
iewer.ClosePdfFile();
```

### Se även

* class [PdfViewer](../../pdfviewer)
* namnutrymme [Aspose.Pdf.Facades](../../pdfviewer)
* hopsättning [Aspose.PDF](../../../)

---

## PrintLargePdf(Stream) {#printlargepdf}

Öppnar och skriver ut en stor PDF-ström. Om din Pdf-fil har hundratals sidor eller fler eller dess storlek är mer än 3 MB, rekommenderas denna metod för att få bättre prestanda.

```csharp
public void PrintLargePdf(Stream inputStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputStream | Stream | Pdf-strömmen som ska öppnas och skrivas ut.. |

### Anmärkningar

Denna metod har integrerat öppningen och utskriften av filen och du behöver inte anropa OpenPdfFile() explicit.

### Exempel

```csharp
[C#]
dfViewer viewer = new PdfViewer();
iewer.AutoResize = true;        //skriv ut filen med anpassad storlek
iewer.AutoRotate = true;        //skriv ut filen med justerad rotation
iewer.PrintPageDialog=false;// skapa inte sidnummerdialogrutan vid utskrift
iewer.PrintLargePdf(new MemoryStream(File.ReadAllBytes(@"d:\test.pdf")));
iewer.ClosePdfFile();

VisualBasic]
im viewer As PdfViewer = new PdfViewer();
iewer.AutoResize = true         'skriv ut filen med anpassad storlek
iewer.AutoRotate = true         'skriv ut filen med justerad rotation
iewer.PrintPageDialog=false;// skapa inte sidnummerdialogrutan vid utskrift
iewer.PrintLargePdf(new MemoryStream(File.ReadAllBytes(@"d:\test.pdf")))
iewer.ClosePdfFile()
```

### Se även

* class [PdfViewer](../../pdfviewer)
* namnutrymme [Aspose.Pdf.Facades](../../pdfviewer)
* hopsättning [Aspose.PDF](../../../)

---

## PrintLargePdf(string, PrinterSettings) {#printlargepdf_5}

Öppnar och skriver ut en stor pdf-fil med specificerade skrivarinställningar. Om din Pdf-fil har hundratals sidor eller mer eller dess storlek är mer än 3 MB, rekommenderas denna metod för att få bättre prestanda.

```csharp
public void PrintLargePdf(string filePath, PrinterSettings printerSettings)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePath | String | Sökvägen till pdf-fil. |
| printerSettings | PrinterSettings | Skrivarinställningarna. |

### Anmärkningar

Denna metod har integrerat öppningen och utskriften av filen och du behöver inte anropa OpenPdfFile() explicit.

### Exempel

```csharp
[C#]
dfViewer viewer = new PdfViewer();
iewer.AutoResize = true;       //skriv ut filen med anpassad storlek
iewer.AutoRotate = true;       //skriv ut filen med justerad rotation
iewer.PrintPageDialog=false;// skapa inte sidnummerdialogrutan vid utskrift
ystem.Drawing.Printing.PrinterSettings ps = new System.Drawing.Printing.PrinterSettings();
rintDocument prtdoc = new PrintDocument();
s.PrinterName = prtdoc.PrinterSettings.PrinterName;
iewer.PrintLargePdf(@"d:\test.pdf",ps);
iewer.ClosePdfFile();

VisualBasic]
im viewer As PdfViewer = new PdfViewer();
iewer.AutoResize = true        'skriv ut filen med anpassad storlek
iewer.AutoRotate = true        'skriv ut filen med justerad rotation
iewer.PrintPageDialog=false;// skapa inte sidnummerdialogrutan vid utskrift
im ps As System.Drawing.Printing.PrinterSettings = new System.Drawing.Printing.PrinterSettings()
im prtdoc As PrintDocument = new PrintDocument()
s.PrinterName = prtdoc.PrinterSettings.PrinterName
iewer.PrintLargePdf(@"d:\test.pdf",ps)
iewer.ClosePdfFile()
```

### Se även

* class [PdfViewer](../../pdfviewer)
* namnutrymme [Aspose.Pdf.Facades](../../pdfviewer)
* hopsättning [Aspose.PDF](../../../)

---

## PrintLargePdf(Stream, PrinterSettings) {#printlargepdf_2}

Öppnar och skriver ut en stor PDF-ström med specificerade skrivarinställningar. Om din Pdf-fil har hundratals sidor eller mer eller dess storlek är mer än 3 MB, rekommenderas denna metod för att få bättre prestanda.

```csharp
public void PrintLargePdf(Stream inputStream, PrinterSettings printerSettings)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputStream | Stream | Pdf-strömmen som ska öppnas och skrivas ut.. |
| printerSettings | PrinterSettings | Skrivarinställningarna. |

### Anmärkningar

Denna metod har integrerat öppningen och utskriften av filen och du behöver inte anropa OpenPdfFile() explicit.

### Exempel

```csharp
[C#]
dfViewer viewer = new PdfViewer();
iewer.AutoResize = true;       //skriv ut filen med anpassad storlek
iewer.AutoRotate = true;       //skriv ut filen med justerad rotation
iewer.PrintPageDialog=false;// skapa inte sidnummerdialogrutan vid utskrift
ystem.Drawing.Printing.PrinterSettings ps = new System.Drawing.Printing.PrinterSettings();
rintDocument prtdoc = new PrintDocument();
s.PrinterName = prtdoc.PrinterSettings.PrinterName;
iewer.PrintLargePdf(new MemoryStream(File.ReadAllBytes(@"d:\middleware.pdf")),ps);
iewer.ClosePdfFile();

VisualBasic]
im viewer As PdfViewer = new PdfViewer();
iewer.AutoResize = true        'skriv ut filen med anpassad storlek
iewer.AutoRotate = true        'skriv ut filen med justerad rotation
iewer.PrintPageDialog=false;// skapa inte sidnummerdialogrutan vid utskrift
im ps As System.Drawing.Printing.PrinterSettings = new System.Drawing.Printing.PrinterSettings()
im prtdoc As PrintDocument = new PrintDocument()
s.PrinterName = prtdoc.PrinterSettings.PrinterName
iewer.PrintLargePdf(new MemoryStream(File.ReadAllBytes(@"d:\middleware.pdf")),ps)
iewer.ClosePdfFile()
```

### Se även

* class [PdfViewer](../../pdfviewer)
* namnutrymme [Aspose.Pdf.Facades](../../pdfviewer)
* hopsättning [Aspose.PDF](../../../)

---

## PrintLargePdf(string, PageSettings, PrinterSettings) {#printlargepdf_4}

Öppnar och skriver ut en stor pdf-fil med angivna sidinställningar och skrivarinställningar. Om din Pdf -fil har hundratals sidor eller fler eller dess storlek är mer än 3 MB, rekommenderas denna metod för att få bättre prestanda.

```csharp
public void PrintLargePdf(string filePath, PageSettings pageSettings, 
    PrinterSettings printerSettings)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePath | String | Sökvägen till pdf-fil. |
| pageSettings | PageSettings | Sidinställningarna. |
| printerSettings | PrinterSettings | Skrivarinställningarna. |

### Anmärkningar

Denna metod har integrerat öppningen och utskriften av filen och du behöver inte anropa OpenPdfFile() explicit.

### Exempel

```csharp
[C#]
dfViewer viewer = new PdfViewer();
iewer.AutoResize = true;       //skriv ut filen med anpassad storlek
iewer.AutoRotate = true;       //skriv ut filen med justerad rotation
iewer.PrintPageDialog=false;// skapa inte sidnummerdialogrutan vid utskrift
ystem.Drawing.Printing.PrinterSettings ps = new System.Drawing.Printing.PrinterSettings();
rintDocument prtdoc = new PrintDocument();
s.PrinterName = prtdoc.PrinterSettings.PrinterName;
ageSettings pgs = new PageSettings();
gs.PaperSize = new System.Drawing.Printing.PaperSize("A4", 827, 1169);
gs.Margins = new Margins(0, 0, 0, 0);
iewer.PrintLargePdf(@"d:\test.pdf",pgs,ps);
iewer.ClosePdfFile();

VisualBasic]
im viewer As PdfViewer = new PdfViewer();
iewer.AutoResize = true       'skriv ut filen med anpassad storlek
iewer.AutoRotate = true       'skriv ut filen med justerad rotation
iewer.PrintPageDialog=false;// skapa inte sidnummerdialogrutan vid utskrift
im ps As System.Drawing.Printing.PrinterSettings = new System.Drawing.Printing.PrinterSettings()
im prtdoc As PrintDocument = new PrintDocument()
s.PrinterName = prtdoc.PrinterSettings.PrinterName
im pgs As PageSettings=new PageSettings()
gs.PaperSize = new System.Drawing.Printing.PaperSize("A4", 827, 1169)
gs.Margins = new Margins(0, 0, 0, 0)
iewer.PrintLargePdf(@"d:\test.pdf",pgs,ps)
iewer.ClosePdfFile()
```

### Se även

* class [PdfViewer](../../pdfviewer)
* namnutrymme [Aspose.Pdf.Facades](../../pdfviewer)
* hopsättning [Aspose.PDF](../../../)

---

## PrintLargePdf(Stream, PageSettings, PrinterSettings) {#printlargepdf_1}

Öppnar och skriver ut en stor PDF-ström med angivna sidinställningar och skrivarinställningar. Om din Pdf -fil har hundratals sidor eller fler eller dess storlek är mer än 3 MB, rekommenderas denna metod för att få bättre prestanda.

```csharp
public void PrintLargePdf(Stream inputStream, PageSettings pageSettings, 
    PrinterSettings printerSettings)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputStream | Stream | Pdf-strömmen som ska öppnas och skrivas ut. |
| pageSettings | PageSettings | Sidinställningarna. |
| printerSettings | PrinterSettings | Skrivarinställningarna. |

### Anmärkningar

Denna metod har integrerat öppningen och utskriften av filen och du behöver inte anropa OpenPdfFile() explicit.

### Exempel

```csharp
[C#]
dfViewer viewer = new PdfViewer();
iewer.AutoResize = true;       //skriv ut filen med anpassad storlek
iewer.AutoRotate = true;       //skriv ut filen med justerad rotation
iewer.PrintPageDialog=false;// skapa inte sidnummerdialogrutan vid utskrift
ystem.Drawing.Printing.PrinterSettings ps = new System.Drawing.Printing.PrinterSettings();
rintDocument prtdoc = new PrintDocument();
s.PrinterName = prtdoc.PrinterSettings.PrinterName;
ageSettings pgs = new PageSettings();
gs.PaperSize = new System.Drawing.Printing.PaperSize("A4", 827, 1169);
gs.Margins = new Margins(0, 0, 0, 0);
iewer.PrintLargePdf(new MemoryStream(File.ReadAllBytes(@"d:\middleware.pdf")),pgs,ps);
iewer.ClosePdfFile();

VisualBasic]
im viewer As PdfViewer = new PdfViewer();
iewer.AutoResize = true       'skriv ut filen med anpassad storlek
iewer.AutoRotate = true       'skriv ut filen med justerad rotation
iewer.PrintPageDialog=false;// skapa inte sidnummerdialogrutan vid utskrift
im ps As System.Drawing.Printing.PrinterSettings = new System.Drawing.Printing.PrinterSettings()
im prtdoc As PrintDocument = new PrintDocument()
s.PrinterName = prtdoc.PrinterSettings.PrinterName
im pgs As PageSettings=new PageSettings()
gs.PaperSize = new System.Drawing.Printing.PaperSize("A4", 827, 1169)
gs.Margins = new Margins(0, 0, 0, 0)
iewer.PrintLargePdf(new MemoryStream(File.ReadAllBytes(@"d:\middleware.pdf")),pgs,ps)
iewer.ClosePdfFile()
```

### Se även

* class [PdfViewer](../../pdfviewer)
* namnutrymme [Aspose.Pdf.Facades](../../pdfviewer)
* hopsättning [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
