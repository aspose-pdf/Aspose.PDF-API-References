---
title: PdfViewer.PrintLargePdf
second_title: Aspose.PDF for .NET API Reference
description: PdfViewer-Methode. Öffnet und druckt eine große Pdf-Datei. Wenn Ihre Pdf-Datei Hunderte von Seiten oder mehr hat oder ihre Größe mehr als 3 MB beträgt, wird diese Methode empfohlen, um eine bessere Leistung zu erzielen.
type: docs
weight: 350
url: /de/net/aspose.pdf.facades/pdfviewer/printlargepdf/
---
## PrintLargePdf(string) {#printlargepdf_3}

Öffnet und druckt eine große Pdf-Datei. Wenn Ihre Pdf-Datei Hunderte von Seiten oder mehr hat oder ihre Größe mehr als 3 MB beträgt, wird diese Methode empfohlen, um eine bessere Leistung zu erzielen.

```csharp
public void PrintLargePdf(string filePath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePath | String | Der Pfad zur Pdf-Datei. |

## Bemerkungen

Diese Methode integriert das Öffnen und Drucken der Datei, und Sie müssen die BindPdf() nicht explizit aufrufen.

## Beispiele

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

### Siehe auch

* Klasse [PdfViewer](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## PrintLargePdf(Stream) {#printlargepdf}

Öffnet und druckt einen großen Pdf-Stream. Wenn Ihre Pdf-Datei Hunderte von Seiten oder mehr hat oder ihre Größe mehr als 3 MB beträgt, wird diese Methode empfohlen, um eine bessere Leistung zu erzielen.

```csharp
public void PrintLargePdf(Stream inputStream)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputStream | Stream | Der Pdf-Stream, der geöffnet und gedruckt werden soll. |

## Bemerkungen

Diese Methode integriert das Öffnen und Drucken der Datei, und Sie müssen die BindPdf() nicht explizit aufrufen.

## Beispiele

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

### Siehe auch

* Klasse [PdfViewer](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## PrintLargePdf(string, PrinterSettings) {#printlargepdf_5}

Öffnet und druckt eine große Pdf-Datei mit angegebenen Druckereinstellungen. Wenn Ihre Pdf-Datei Hunderte von Seiten oder mehr hat oder ihre Größe mehr als 3 MB beträgt, wird diese Methode empfohlen, um eine bessere Leistung zu erzielen.

```csharp
public void PrintLargePdf(string filePath, PrinterSettings printerSettings)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePath | String | Der Pfad zur Pdf-Datei. |
| printerSettings | PrinterSettings | Die Druckereinstellungen. |

## Bemerkungen

Diese Methode integriert das Öffnen und Drucken der Datei, und Sie müssen die BindPdf() nicht explizit aufrufen.

## Beispiele

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

### Siehe auch

* Klasse [PrinterSettings](../../../aspose.pdf.printing/printersettings/)
* Klasse [PdfViewer](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## PrintLargePdf(Stream, PrinterSettings) {#printlargepdf_2}

Öffnet und druckt einen großen Pdf-Stream mit angegebenen Druckereinstellungen. Wenn Ihre Pdf-Datei Hunderte von Seiten oder mehr hat oder ihre Größe mehr als 3 MB beträgt, wird diese Methode empfohlen, um eine bessere Leistung zu erzielen.

```csharp
public void PrintLargePdf(Stream inputStream, PrinterSettings printerSettings)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputStream | Stream | Der Pdf-Stream, der geöffnet und gedruckt werden soll. |
| printerSettings | PrinterSettings | Die Druckereinstellungen. |

## Bemerkungen

Diese Methode integriert das Öffnen und Drucken der Datei, und Sie müssen die BindPdf() nicht explizit aufrufen.

## Beispiele

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

### Siehe auch

* Klasse [PrinterSettings](../../../aspose.pdf.printing/printersettings/)
* Klasse [PdfViewer](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## PrintLargePdf(string, PageSettings, PrinterSettings) {#printlargepdf_4}

Öffnet und druckt eine große Pdf-Datei mit angegebenen Seiten- und Druckereinstellungen. Wenn Ihre Pdf-Datei Hunderte von Seiten oder mehr hat oder ihre Größe mehr als 3 MB beträgt, wird diese Methode empfohlen, um eine bessere Leistung zu erzielen.

```csharp
public void PrintLargePdf(string filePath, PageSettings pageSettings, 
    PrinterSettings printerSettings)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePath | String | Der Pfad zur Pdf-Datei. |
| pageSettings | PageSettings | Die Seiteneinstellungen. |
| printerSettings | PrinterSettings | Die Druckereinstellungen. |

## Bemerkungen

Diese Methode integriert das Öffnen und Drucken der Datei, und Sie müssen die BindPdf() nicht explizit aufrufen.

## Beispiele

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

### Siehe auch

* Klasse [PageSettings](../../../aspose.pdf.printing/pagesettings/)
* Klasse [PrinterSettings](../../../aspose.pdf.printing/printersettings/)
* Klasse [PdfViewer](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## PrintLargePdf(Stream, PageSettings, PrinterSettings) {#printlargepdf_1}

Öffnet und druckt einen großen Pdf-Stream mit angegebenen Seiten- und Druckereinstellungen. Wenn Ihre Pdf-Datei Hunderte von Seiten oder mehr hat oder ihre Größe mehr als 3 MB beträgt, wird diese Methode empfohlen, um eine bessere Leistung zu erzielen.

```csharp
public void PrintLargePdf(Stream inputStream, PageSettings pageSettings, 
    PrinterSettings printerSettings)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputStream | Stream | Der Pdf-Stream, der geöffnet und gedruckt werden soll. |
| pageSettings | PageSettings | Die Seiteneinstellungen. |
| printerSettings | PrinterSettings | Die Druckereinstellungen. |

## Bemerkungen

Diese Methode integriert das Öffnen und Drucken der Datei, und Sie müssen die BindPdf() nicht explizit aufrufen.

## Beispiele

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

### Siehe auch

* Klasse [PageSettings](../../../aspose.pdf.printing/pagesettings/)
* Klasse [PrinterSettings](../../../aspose.pdf.printing/printersettings/)
* Klasse [PdfViewer](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)