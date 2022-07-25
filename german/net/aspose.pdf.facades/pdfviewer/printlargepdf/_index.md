---
title: PrintLargePdf
second_title: Aspose.PDF für .NET-API-Referenz
description: Öffnet und druckt eine große PDF-Datei. Wenn Ihre PDF-Datei Hunderte von Seiten oder mehr hat oder ihre Größe mehr als 3 MB beträgt wird diese Methode empfohlen um eine bessere Leistung zu erzielen.
type: docs
weight: 320
url: /de/net/aspose.pdf.facades/pdfviewer/printlargepdf/
---
## PrintLargePdf(string) {#printlargepdf_3}

Öffnet und druckt eine große PDF-Datei. Wenn Ihre PDF-Datei Hunderte von Seiten oder mehr hat oder ihre Größe mehr als 3 MB beträgt, wird diese Methode empfohlen, um eine bessere Leistung zu erzielen.

```csharp
public void PrintLargePdf(string filePath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePath | String | Der Pfad der PDF-Datei. |

### Bemerkungen

Diese Methode hat das Öffnen und Drucken der Datei integriert und Sie müssen OpenPdfFile() nicht explizit aufrufen.

### Beispiele

```csharp
[C#]
dfViewer viewer = new PdfViewer();
iewer.AutoResize = true;     //Drucken Sie die Datei mit angepasster Größe
iewer.AutoRotate = true;     // Datei mit angepasster Rotation drucken
iewer.PrintPageDialog=false;// erzeugt beim Drucken keinen Seitenzahldialog
iewer.PrintLargePdf(@"d:\test.pdf");

VisualBasic]
im viewer As PdfViewer = new PdfViewer();
iewer.AutoResize = true      'Drucken Sie die Datei mit angepasster Größe
iewer.AutoRotate = true      'Drucken Sie die Datei mit angepasster Drehung
iewer.PrintPageDialog=false;// erzeugt beim Drucken keinen Seitenzahldialog
iewer.PrintLargePdf(@"d:\test.pdf")
iewer.ClosePdfFile();
```

### Siehe auch

* class [PdfViewer](../../pdfviewer)
* namensraum [Aspose.Pdf.Facades](../../pdfviewer)
* Montage [Aspose.PDF](../../../)

---

## PrintLargePdf(Stream) {#printlargepdf}

Öffnet und druckt einen großen PDF-Stream. Wenn Ihre PDF-Datei Hunderte von Seiten oder mehr hat oder ihre Größe mehr als 3 MB beträgt, wird diese Methode empfohlen, um eine bessere Leistung zu erzielen.

```csharp
public void PrintLargePdf(Stream inputStream)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputStream | Stream | Der pdf-Stream zum Öffnen und Ausdrucken.. |

### Bemerkungen

Diese Methode hat das Öffnen und Drucken der Datei integriert und Sie müssen OpenPdfFile() nicht explizit aufrufen.

### Beispiele

```csharp
[C#]
dfViewer viewer = new PdfViewer();
iewer.AutoResize = true;        //Drucken Sie die Datei mit angepasster Größe
iewer.AutoRotate = true;        // Datei mit angepasster Rotation drucken
iewer.PrintPageDialog=false;// erzeugt beim Drucken keinen Seitenzahldialog
iewer.PrintLargePdf(new MemoryStream(File.ReadAllBytes(@"d:\test.pdf")));
iewer.ClosePdfFile();

VisualBasic]
im viewer As PdfViewer = new PdfViewer();
iewer.AutoResize = true         'Drucken Sie die Datei mit angepasster Größe
iewer.AutoRotate = true         'Drucken Sie die Datei mit angepasster Drehung
iewer.PrintPageDialog=false;// erzeugt beim Drucken keinen Seitenzahldialog
iewer.PrintLargePdf(new MemoryStream(File.ReadAllBytes(@"d:\test.pdf")))
iewer.ClosePdfFile()
```

### Siehe auch

* class [PdfViewer](../../pdfviewer)
* namensraum [Aspose.Pdf.Facades](../../pdfviewer)
* Montage [Aspose.PDF](../../../)

---

## PrintLargePdf(string, PrinterSettings) {#printlargepdf_5}

Öffnet und druckt eine große PDF-Datei mit festgelegten Druckereinstellungen. Wenn Ihre PDF-Datei hunderte Seiten oder mehr hat oder ihre Größe mehr als 3 MB beträgt, wird diese Methode empfohlen, um eine bessere Leistung zu erzielen.

```csharp
public void PrintLargePdf(string filePath, PrinterSettings printerSettings)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePath | String | Der Pfad der PDF-Datei. |
| printerSettings | PrinterSettings | Die Druckereinstellungen. |

### Bemerkungen

Diese Methode hat das Öffnen und Drucken der Datei integriert und Sie müssen OpenPdfFile() nicht explizit aufrufen.

### Beispiele

```csharp
[C#]
dfViewer viewer = new PdfViewer();
iewer.AutoResize = true;       //Drucken Sie die Datei mit angepasster Größe
iewer.AutoRotate = true;       // Datei mit angepasster Rotation drucken
iewer.PrintPageDialog=false;// erzeugt beim Drucken keinen Seitenzahldialog
ystem.Drawing.Printing.PrinterSettings ps = new System.Drawing.Printing.PrinterSettings();
rintDocument prtdoc = new PrintDocument();
s.PrinterName = prtdoc.PrinterSettings.PrinterName;
iewer.PrintLargePdf(@"d:\test.pdf",ps);
iewer.ClosePdfFile();

VisualBasic]
im viewer As PdfViewer = new PdfViewer();
iewer.AutoResize = true        'Drucken Sie die Datei mit angepasster Größe
iewer.AutoRotate = true        'Drucken Sie die Datei mit angepasster Drehung
iewer.PrintPageDialog=false;// erzeugt beim Drucken keinen Seitenzahldialog
im ps As System.Drawing.Printing.PrinterSettings = new System.Drawing.Printing.PrinterSettings()
im prtdoc As PrintDocument = new PrintDocument()
s.PrinterName = prtdoc.PrinterSettings.PrinterName
iewer.PrintLargePdf(@"d:\test.pdf",ps)
iewer.ClosePdfFile()
```

### Siehe auch

* class [PdfViewer](../../pdfviewer)
* namensraum [Aspose.Pdf.Facades](../../pdfviewer)
* Montage [Aspose.PDF](../../../)

---

## PrintLargePdf(Stream, PrinterSettings) {#printlargepdf_2}

Öffnet und druckt einen großen PDF-Stream mit festgelegten Druckereinstellungen. Wenn Ihre PDF-Datei hunderte Seiten oder mehr hat oder ihre Größe mehr als 3 MB beträgt, wird diese Methode empfohlen, um eine bessere Leistung zu erzielen.

```csharp
public void PrintLargePdf(Stream inputStream, PrinterSettings printerSettings)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputStream | Stream | Der pdf-Stream zum Öffnen und Ausdrucken.. |
| printerSettings | PrinterSettings | Die Druckereinstellungen. |

### Bemerkungen

Diese Methode hat das Öffnen und Drucken der Datei integriert und Sie müssen OpenPdfFile() nicht explizit aufrufen.

### Beispiele

```csharp
[C#]
dfViewer viewer = new PdfViewer();
iewer.AutoResize = true;       //Drucken Sie die Datei mit angepasster Größe
iewer.AutoRotate = true;       // Datei mit angepasster Rotation drucken
iewer.PrintPageDialog=false;// erzeugt beim Drucken keinen Seitenzahldialog
ystem.Drawing.Printing.PrinterSettings ps = new System.Drawing.Printing.PrinterSettings();
rintDocument prtdoc = new PrintDocument();
s.PrinterName = prtdoc.PrinterSettings.PrinterName;
iewer.PrintLargePdf(new MemoryStream(File.ReadAllBytes(@"d:\middleware.pdf")),ps);
iewer.ClosePdfFile();

VisualBasic]
im viewer As PdfViewer = new PdfViewer();
iewer.AutoResize = true        'Drucken Sie die Datei mit angepasster Größe
iewer.AutoRotate = true        'Drucken Sie die Datei mit angepasster Drehung
iewer.PrintPageDialog=false;// erzeugt beim Drucken keinen Seitenzahldialog
im ps As System.Drawing.Printing.PrinterSettings = new System.Drawing.Printing.PrinterSettings()
im prtdoc As PrintDocument = new PrintDocument()
s.PrinterName = prtdoc.PrinterSettings.PrinterName
iewer.PrintLargePdf(new MemoryStream(File.ReadAllBytes(@"d:\middleware.pdf")),ps)
iewer.ClosePdfFile()
```

### Siehe auch

* class [PdfViewer](../../pdfviewer)
* namensraum [Aspose.Pdf.Facades](../../pdfviewer)
* Montage [Aspose.PDF](../../../)

---

## PrintLargePdf(string, PageSettings, PrinterSettings) {#printlargepdf_4}

Öffnet und druckt eine große PDF-Datei mit festgelegten Seiteneinstellungen und Druckereinstellungen. Wenn Ihre PDF- -Datei Hunderte von Seiten oder mehr umfasst oder ihre Größe mehr als 3 MB beträgt, wird diese Methode empfohlen, um eine bessere Leistung zu erzielen.

```csharp
public void PrintLargePdf(string filePath, PageSettings pageSettings, 
    PrinterSettings printerSettings)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePath | String | Der Pfad der PDF-Datei. |
| pageSettings | PageSettings | Die Seiteneinstellungen. |
| printerSettings | PrinterSettings | Die Druckereinstellungen. |

### Bemerkungen

Diese Methode hat das Öffnen und Drucken der Datei integriert und Sie müssen OpenPdfFile() nicht explizit aufrufen.

### Beispiele

```csharp
[C#]
dfViewer viewer = new PdfViewer();
iewer.AutoResize = true;       //Drucken Sie die Datei mit angepasster Größe
iewer.AutoRotate = true;       // Datei mit angepasster Rotation drucken
iewer.PrintPageDialog=false;// erzeugt beim Drucken keinen Seitenzahldialog
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
iewer.AutoResize = true       'Drucken Sie die Datei mit angepasster Größe
iewer.AutoRotate = true       'Drucken Sie die Datei mit angepasster Drehung
iewer.PrintPageDialog=false;// erzeugt beim Drucken keinen Seitenzahldialog
im ps As System.Drawing.Printing.PrinterSettings = new System.Drawing.Printing.PrinterSettings()
im prtdoc As PrintDocument = new PrintDocument()
s.PrinterName = prtdoc.PrinterSettings.PrinterName
im pgs As PageSettings=new PageSettings()
gs.PaperSize = new System.Drawing.Printing.PaperSize("A4", 827, 1169)
gs.Margins = new Margins(0, 0, 0, 0)
iewer.PrintLargePdf(@"d:\test.pdf",pgs,ps)
iewer.ClosePdfFile()
```

### Siehe auch

* class [PdfViewer](../../pdfviewer)
* namensraum [Aspose.Pdf.Facades](../../pdfviewer)
* Montage [Aspose.PDF](../../../)

---

## PrintLargePdf(Stream, PageSettings, PrinterSettings) {#printlargepdf_1}

Öffnet und druckt einen großen PDF-Stream mit festgelegten Seiteneinstellungen und Druckereinstellungen. Wenn Ihre PDF- -Datei Hunderte von Seiten oder mehr umfasst oder ihre Größe mehr als 3 MB beträgt, wird diese Methode empfohlen, um eine bessere Leistung zu erzielen.

```csharp
public void PrintLargePdf(Stream inputStream, PageSettings pageSettings, 
    PrinterSettings printerSettings)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputStream | Stream | Der zu öffnende und auszudruckende PDF-Stream. |
| pageSettings | PageSettings | Die Seiteneinstellungen. |
| printerSettings | PrinterSettings | Die Druckereinstellungen. |

### Bemerkungen

Diese Methode hat das Öffnen und Drucken der Datei integriert und Sie müssen OpenPdfFile() nicht explizit aufrufen.

### Beispiele

```csharp
[C#]
dfViewer viewer = new PdfViewer();
iewer.AutoResize = true;       //Drucken Sie die Datei mit angepasster Größe
iewer.AutoRotate = true;       // Datei mit angepasster Rotation drucken
iewer.PrintPageDialog=false;// erzeugt beim Drucken keinen Seitenzahldialog
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
iewer.AutoResize = true       'Drucken Sie die Datei mit angepasster Größe
iewer.AutoRotate = true       'Drucken Sie die Datei mit angepasster Drehung
iewer.PrintPageDialog=false;// erzeugt beim Drucken keinen Seitenzahldialog
im ps As System.Drawing.Printing.PrinterSettings = new System.Drawing.Printing.PrinterSettings()
im prtdoc As PrintDocument = new PrintDocument()
s.PrinterName = prtdoc.PrinterSettings.PrinterName
im pgs As PageSettings=new PageSettings()
gs.PaperSize = new System.Drawing.Printing.PaperSize("A4", 827, 1169)
gs.Margins = new Margins(0, 0, 0, 0)
iewer.PrintLargePdf(new MemoryStream(File.ReadAllBytes(@"d:\middleware.pdf")),pgs,ps)
iewer.ClosePdfFile()
```

### Siehe auch

* class [PdfViewer](../../pdfviewer)
* namensraum [Aspose.Pdf.Facades](../../pdfviewer)
* Montage [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
