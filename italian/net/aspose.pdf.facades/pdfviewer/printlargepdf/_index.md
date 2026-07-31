---
title: "Metodo PdfViewer. Apre e stampa un file Pdf di grandi dimensioni. Se il tuo file Pdf ha centinaia di pagine o più o la sua dimensione supera i 3 MB, questo metodo è consigliato per ottenere migliori prestazioni."
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Il percorso del file Pdf."
type: docs
weight: 350
url: /it/net/aspose.pdf.facades/pdfviewer/printlargepdf/
---
## PrintLargePdf(string) {#printlargepdf_3}

Apre e stampa un grande file Pdf. Se il tuo file Pdf ha centinaia di pagine o più o la sua dimensione supera i 3 MB, questo metodo è consigliato per ottenere migliori prestazioni.

```csharp
public void PrintLargePdf(string filePath)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePath | String | Questo metodo integra l'apertura e la stampa del file e non è necessario chiamare esplicitamente BindPdf(). |

## Osservazioni

Il flusso pdf da aprire e stampare.

## Esempi

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

### Vedi anche

* class [PdfViewer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## PrintLargePdf(Stream) {#printlargepdf}

Apre e stampa un grande flusso Pdf. Se il tuo file Pdf ha centinaia di pagine o più o la sua dimensione supera i 3 MB, questo metodo è consigliato per ottenere migliori prestazioni.

```csharp
public void PrintLargePdf(Stream inputStream)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputStream | Stream | Le impostazioni della stampante. |

## Osservazioni

Il flusso pdf da aprire e stampare.

## Esempi

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

### Vedi anche

* class [PdfViewer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## PrintLargePdf(string, PrinterSettings) {#printlargepdf_5}

Apre e stampa un grande file Pdf con le impostazioni della stampante specificate. Se il tuo file Pdf ha centinaia di pagine o più o la sua dimensione supera i 3 MB, questo metodo è consigliato per ottenere migliori prestazioni.

```csharp
public void PrintLargePdf(string filePath, PrinterSettings printerSettings)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePath | String | Questo metodo integra l'apertura e la stampa del file e non è necessario chiamare esplicitamente BindPdf(). |
| printerSettings | PrinterSettings | Questo metodo integra l'apertura e la stampa del file e non è necessario chiamare esplicitamente BindPdf(). |

## Osservazioni

Il flusso pdf da aprire e stampare.

## Esempi

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

### Vedi anche

* class [PrinterSettings](../../../aspose.pdf.printing/printersettings/)
* class [PdfViewer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## PrintLargePdf(Stream, PrinterSettings) {#printlargepdf_2}

Apre e stampa un grande flusso Pdf con le impostazioni della stampante specificate. Se il tuo file Pdf ha centinaia di pagine o più o la sua dimensione supera i 3 MB, questo metodo è consigliato per ottenere migliori prestazioni.

```csharp
public void PrintLargePdf(Stream inputStream, PrinterSettings printerSettings)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputStream | Stream | Le impostazioni della stampante. |
| printerSettings | PrinterSettings | Questo metodo integra l'apertura e la stampa del file e non è necessario chiamare esplicitamente BindPdf(). |

## Osservazioni

Le impostazioni della pagina.

## Esempi

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

### Vedi anche

* class [PrinterSettings](../../../aspose.pdf.printing/printersettings/)
* class [PdfViewer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## PrintLargePdf(string, PageSettings, PrinterSettings) {#printlargepdf_4}

Apre e stampa un grande file Pdf con le impostazioni della pagina e della stampante specificate. Se il tuo file Pdf ha centinaia di pagine o più o la sua dimensione supera i 3 MB, questo metodo è consigliato per ottenere migliori prestazioni.

```csharp
public void PrintLargePdf(string filePath, PageSettings pageSettings, 
    PrinterSettings printerSettings)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePath | String | Questo metodo integra l'apertura e la stampa del file e non è necessario chiamare esplicitamente BindPdf(). |
| pageSettings | PageSettings | PdfViewer.UseIntermidiateImage |
| printerSettings | PrinterSettings | Questo metodo integra l'apertura e la stampa del file e non è necessario chiamare esplicitamente BindPdf(). |

## Osservazioni

Il flusso pdf da aprire e stampare.

## Esempi

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

### Vedi anche

* class [PageSettings](../../../aspose.pdf.printing/pagesettings/)
* class [PrinterSettings](../../../aspose.pdf.printing/printersettings/)
* class [PdfViewer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## PrintLargePdf(Stream, PageSettings, PrinterSettings) {#printlargepdf_1}

Apre e stampa un grande flusso Pdf con le impostazioni della pagina e della stampante specificate. Se il tuo file Pdf ha centinaia di pagine o più o la sua dimensione supera i 3 MB, questo metodo è consigliato per ottenere migliori prestazioni.

```csharp
public void PrintLargePdf(Stream inputStream, PageSettings pageSettings, 
    PrinterSettings printerSettings)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputStream | Stream | Le impostazioni della stampante. |
| pageSettings | PageSettings | PdfViewer.UseIntermidiateImage |
| printerSettings | PrinterSettings | Questo metodo integra l'apertura e la stampa del file e non è necessario chiamare esplicitamente BindPdf(). |

## Osservazioni

Il flusso pdf da aprire e stampare.

## Esempi

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

### Vedi anche

* class [PageSettings](../../../aspose.pdf.printing/pagesettings/)
* class [PrinterSettings](../../../aspose.pdf.printing/printersettings/)
* class [PdfViewer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


