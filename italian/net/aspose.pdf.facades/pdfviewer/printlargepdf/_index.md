---
title: PdfViewer.PrintLargePdf
second_title: Aspose.PDF for .NET API Reference
description: Metodo PdfViewer. Apre e stampa un file Pdf di grandi dimensioni. Se il tuo file Pdf ha centinaia di pagine o più o la sua dimensione è superiore a 3 MB, questo metodo è raccomandato per ottenere migliori prestazioni
type: docs
weight: 350
url: /it/net/aspose.pdf.facades/pdfviewer/printlargepdf/
---
## PrintLargePdf(string) {#printlargepdf_3}

Apre e stampa un file Pdf di grandi dimensioni. Se il tuo file Pdf ha centinaia di pagine o più o la sua dimensione è superiore a 3 MB, questo metodo è raccomandato per ottenere migliori prestazioni.

```csharp
public void PrintLargePdf(string filePath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| filePath | String | Il percorso del file Pdf. |

## Remarks

Questo metodo integra l'apertura e la stampa del file e non è necessario chiamare esplicitamente il BindPdf().

## Examples

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

### See Also

* class [PdfViewer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## PrintLargePdf(Stream) {#printlargepdf}

Apre e stampa un flusso Pdf di grandi dimensioni. Se il tuo file Pdf ha centinaia di pagine o più o la sua dimensione è superiore a 3 MB, questo metodo è raccomandato per ottenere migliori prestazioni.

```csharp
public void PrintLargePdf(Stream inputStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | Stream | Il flusso pdf da aprire e stampare. |

## Remarks

Questo metodo integra l'apertura e la stampa del file e non è necessario chiamare esplicitamente il BindPdf().

## Examples

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

### See Also

* class [PdfViewer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## PrintLargePdf(string, PrinterSettings) {#printlargepdf_5}

Apre e stampa un file Pdf di grandi dimensioni con impostazioni della stampante specificate. Se il tuo file Pdf ha centinaia di pagine o più o la sua dimensione è superiore a 3 MB, questo metodo è raccomandato per ottenere migliori prestazioni.

```csharp
public void PrintLargePdf(string filePath, PrinterSettings printerSettings)
```

| Parameter | Type | Description |
| --- | --- | --- |
| filePath | String | Il percorso del file Pdf. |
| printerSettings | PrinterSettings | Le impostazioni della stampante. |

## Remarks

Questo metodo integra l'apertura e la stampa del file e non è necessario chiamare esplicitamente il BindPdf().

## Examples

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

### See Also

* class [PrinterSettings](../../../aspose.pdf.printing/printersettings/)
* class [PdfViewer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## PrintLargePdf(Stream, PrinterSettings) {#printlargepdf_2}

Apre e stampa un flusso Pdf di grandi dimensioni con impostazioni della stampante specificate. Se il tuo file Pdf ha centinaia di pagine o più o la sua dimensione è superiore a 3 MB, questo metodo è raccomandato per ottenere migliori prestazioni.

```csharp
public void PrintLargePdf(Stream inputStream, PrinterSettings printerSettings)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | Stream | Il flusso pdf da aprire e stampare. |
| printerSettings | PrinterSettings | Le impostazioni della stampante. |

## Remarks

Questo metodo integra l'apertura e la stampa del file e non è necessario chiamare esplicitamente il BindPdf().

## Examples

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

### See Also

* class [PrinterSettings](../../../aspose.pdf.printing/printersettings/)
* class [PdfViewer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## PrintLargePdf(string, PageSettings, PrinterSettings) {#printlargepdf_4}

Apre e stampa un file Pdf di grandi dimensioni con impostazioni di pagina e impostazioni della stampante specificate. Se il tuo file Pdf ha centinaia di pagine o più o la sua dimensione è superiore a 3 MB, questo metodo è raccomandato per ottenere migliori prestazioni.

```csharp
public void PrintLargePdf(string filePath, PageSettings pageSettings, 
    PrinterSettings printerSettings)
```

| Parameter | Type | Description |
| --- | --- | --- |
| filePath | String | Il percorso del file Pdf. |
| pageSettings | PageSettings | Le impostazioni di pagina. |
| printerSettings | PrinterSettings | Le impostazioni della stampante. |

## Remarks

Questo metodo integra l'apertura e la stampa del file e non è necessario chiamare esplicitamente il BindPdf().

## Examples

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

### See Also

* class [PageSettings](../../../aspose.pdf.printing/pagesettings/)
* class [PrinterSettings](../../../aspose.pdf.printing/printersettings/)
* class [PdfViewer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## PrintLargePdf(Stream, PageSettings, PrinterSettings) {#printlargepdf_1}

Apre e stampa un flusso Pdf di grandi dimensioni con impostazioni di pagina e impostazioni della stampante specificate. Se il tuo file Pdf ha centinaia di pagine o più o la sua dimensione è superiore a 3 MB, questo metodo è raccomandato per ottenere migliori prestazioni.

```csharp
public void PrintLargePdf(Stream inputStream, PageSettings pageSettings, 
    PrinterSettings printerSettings)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | Stream | Il flusso pdf da aprire e stampare. |
| pageSettings | PageSettings | Le impostazioni di pagina. |
| printerSettings | PrinterSettings | Le impostazioni della stampante. |

## Remarks

Questo metodo integra l'apertura e la stampa del file e non è necessario chiamare esplicitamente il BindPdf().

## Examples

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

### See Also

* class [PageSettings](../../../aspose.pdf.printing/pagesettings/)
* class [PrinterSettings](../../../aspose.pdf.printing/printersettings/)
* class [PdfViewer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)