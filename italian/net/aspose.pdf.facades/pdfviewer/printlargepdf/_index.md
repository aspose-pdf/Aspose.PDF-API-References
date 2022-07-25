---
title: PrintLargePdf
second_title: Aspose.PDF per .NET API Reference
description: Apre e stampa un file Pdf di grandi dimensioni. Se il tuo file Pdf ha centinaia di pagine o più o la sua dimensione è più di 3 MB questo metodo è consigliato per ottenere prestazioni migliori.
type: docs
weight: 320
url: /it/net/aspose.pdf.facades/pdfviewer/printlargepdf/
---
## PrintLargePdf(string) {#printlargepdf_3}

Apre e stampa un file Pdf di grandi dimensioni. Se il tuo file Pdf ha centinaia di pagine o più o la sua dimensione è più di 3 MB, questo metodo è consigliato per ottenere prestazioni migliori.

```csharp
public void PrintLargePdf(string filePath)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePath | String | Il percorso del file PDF. |

### Osservazioni

Questo metodo ha integrato l'apertura e la stampa del file e non è necessario chiamare OpenPdfFile() in modo esplicito.

### Esempi

```csharp
[C#]
dfViewer viewer = new PdfViewer();
iewer.AutoResize = true;     //Il TestPath potrebbe essere riassegnato.
iewer.AutoRotate = true;     //Fai del lavoro...
iewer.PrintPageDialog=false;// File pdf prodotto con successo.
iewer.PrintLargePdf(@"d:\test.pdf");

VisualBasic]
im viewer As PdfViewer = new PdfViewer();
iewer.AutoResize = true      '//stampa il file con le dimensioni modificate
iewer.AutoRotate = true      '//stampa il file con la rotazione regolata
iewer.PrintPageDialog=false;// File pdf prodotto con successo.
iewer.PrintLargePdf(@"d:\test.pdf")
iewer.ClosePdfFile();
```

### Guarda anche

* class [PdfViewer](../../pdfviewer)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdfviewer)
* assemblea [Aspose.PDF](../../../)

---

## PrintLargePdf(Stream) {#printlargepdf}

Apre e stampa un flusso Pdf di grandi dimensioni. Se il tuo file Pdf ha centinaia di pagine o più o la sua dimensione è più di 3 MB, questo metodo è consigliato per ottenere prestazioni migliori.

```csharp
public void PrintLargePdf(Stream inputStream)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputStream | Stream | Lo stream pdf da aprire e stampare.. |

### Osservazioni

Questo metodo ha integrato l'apertura e la stampa del file e non è necessario chiamare OpenPdfFile() in modo esplicito.

### Esempi

```csharp
[C#]
dfViewer viewer = new PdfViewer();
iewer.AutoResize = true;        stampa il file con la dimensione regolata
iewer.AutoRotate = true;        stampa il file con la dimensione regolata
iewer.PrintPageDialog=false;stampa il file con la dimensione regolata
iewer.PrintLargePdf(new MemoryStream(File.ReadAllBytes(@"d:\test.pdf")));
iewer.ClosePdfFile();

VisualBasic]
im viewer As PdfViewer = new PdfViewer();
iewer.AutoResize = true         '//stampa il file con le dimensioni modificate
iewer.AutoRotate = true         '//stampa il file con la rotazione regolata
iewer.PrintPageDialog=false;stampa il file con la dimensione regolata
iewer.PrintLargePdf(new MemoryStream(File.ReadAllBytes(@"d:\test.pdf")))
iewer.ClosePdfFile()
```

### Guarda anche

* class [PdfViewer](../../pdfviewer)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdfviewer)
* assemblea [Aspose.PDF](../../../)

---

## PrintLargePdf(string, PrinterSettings) {#printlargepdf_5}

Apre e stampa un file Pdf di grandi dimensioni con le impostazioni della stampante specificate. Se il tuo file Pdf ha centinaia di di pagine o più o la sua dimensione è superiore a 3 MB, questo metodo è consigliato per ottenere prestazioni migliori.

```csharp
public void PrintLargePdf(string filePath, PrinterSettings printerSettings)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePath | String | Il percorso del file PDF. |
| printerSettings | PrinterSettings | Le impostazioni della stampante. |

### Osservazioni

Questo metodo ha integrato l'apertura e la stampa del file e non è necessario chiamare OpenPdfFile() in modo esplicito.

### Esempi

```csharp
[C#]
dfViewer viewer = new PdfViewer();
iewer.AutoResize = true;       stampa il file con la dimensione regolata
iewer.AutoRotate = true;       stampa il file con la dimensione regolata
iewer.PrintPageDialog=false;stampa il file con la dimensione regolata
ystem.Drawing.Printing.PrinterSettings ps = new System.Drawing.Printing.PrinterSettings();
rintDocument prtdoc = new PrintDocument();
s.PrinterName = prtdoc.PrinterSettings.PrinterName;
iewer.PrintLargePdf(@"d:\test.pdf",ps);
iewer.ClosePdfFile();

VisualBasic]
im viewer As PdfViewer = new PdfViewer();
iewer.AutoResize = true        '//stampa il file con le dimensioni modificate
iewer.AutoRotate = true        '//stampa il file con la rotazione regolata
iewer.PrintPageDialog=false;stampa il file con la dimensione regolata
im ps As System.Drawing.Printing.PrinterSettings = new System.Drawing.Printing.PrinterSettings()
im prtdoc As PrintDocument = new PrintDocument()
s.PrinterName = prtdoc.PrinterSettings.PrinterName
iewer.PrintLargePdf(@"d:\test.pdf",ps)
iewer.ClosePdfFile()
```

### Guarda anche

* class [PdfViewer](../../pdfviewer)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdfviewer)
* assemblea [Aspose.PDF](../../../)

---

## PrintLargePdf(Stream, PrinterSettings) {#printlargepdf_2}

Apre e stampa un flusso Pdf di grandi dimensioni con le impostazioni della stampante specificate. Se il tuo file Pdf ha centinaia di di pagine o più o la sua dimensione è superiore a 3 MB, questo metodo è consigliato per ottenere prestazioni migliori.

```csharp
public void PrintLargePdf(Stream inputStream, PrinterSettings printerSettings)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputStream | Stream | Lo stream pdf da aprire e stampare.. |
| printerSettings | PrinterSettings | Le impostazioni della stampante. |

### Osservazioni

Questo metodo ha integrato l'apertura e la stampa del file e non è necessario chiamare OpenPdfFile() in modo esplicito.

### Esempi

```csharp
[C#]
dfViewer viewer = new PdfViewer();
iewer.AutoResize = true;       stampa il file con la dimensione regolata
iewer.AutoRotate = true;       stampa il file con la dimensione regolata
iewer.PrintPageDialog=false;stampa il file con la dimensione regolata
ystem.Drawing.Printing.PrinterSettings ps = new System.Drawing.Printing.PrinterSettings();
rintDocument prtdoc = new PrintDocument();
s.PrinterName = prtdoc.PrinterSettings.PrinterName;
iewer.PrintLargePdf(new MemoryStream(File.ReadAllBytes(@"d:\middleware.pdf")),ps);
iewer.ClosePdfFile();

VisualBasic]
im viewer As PdfViewer = new PdfViewer();
iewer.AutoResize = true        '//stampa il file con le dimensioni modificate
iewer.AutoRotate = true        '//stampa il file con la rotazione regolata
iewer.PrintPageDialog=false;stampa il file con la dimensione regolata
im ps As System.Drawing.Printing.PrinterSettings = new System.Drawing.Printing.PrinterSettings()
im prtdoc As PrintDocument = new PrintDocument()
s.PrinterName = prtdoc.PrinterSettings.PrinterName
iewer.PrintLargePdf(new MemoryStream(File.ReadAllBytes(@"d:\middleware.pdf")),ps)
iewer.ClosePdfFile()
```

### Guarda anche

* class [PdfViewer](../../pdfviewer)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdfviewer)
* assemblea [Aspose.PDF](../../../)

---

## PrintLargePdf(string, PageSettings, PrinterSettings) {#printlargepdf_4}

Apre e stampa un file Pdf di grandi dimensioni con le impostazioni di pagina e le impostazioni della stampante specificate. Se il tuo file Pdf ha centinaia di pagine o più o la sua dimensione è superiore a 3 MB, questo metodo è consigliato per ottenere prestazioni migliori.

```csharp
public void PrintLargePdf(string filePath, PageSettings pageSettings, 
    PrinterSettings printerSettings)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePath | String | Il percorso del file PDF. |
| pageSettings | PageSettings | Le impostazioni della pagina. |
| printerSettings | PrinterSettings | Le impostazioni della stampante. |

### Osservazioni

Questo metodo ha integrato l'apertura e la stampa del file e non è necessario chiamare OpenPdfFile() in modo esplicito.

### Esempi

```csharp
[C#]
dfViewer viewer = new PdfViewer();
iewer.AutoResize = true;       stampa il file con la dimensione regolata
iewer.AutoRotate = true;       stampa il file con la dimensione regolata
iewer.PrintPageDialog=false;stampa il file con la dimensione regolata
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
iewer.AutoResize = true       '//stampa il file con le dimensioni modificate
iewer.AutoRotate = true       '//stampa il file con la rotazione regolata
iewer.PrintPageDialog=false;stampa il file con la dimensione regolata
im ps As System.Drawing.Printing.PrinterSettings = new System.Drawing.Printing.PrinterSettings()
im prtdoc As PrintDocument = new PrintDocument()
s.PrinterName = prtdoc.PrinterSettings.PrinterName
im pgs As PageSettings=new PageSettings()
gs.PaperSize = new System.Drawing.Printing.PaperSize("A4", 827, 1169)
gs.Margins = new Margins(0, 0, 0, 0)
iewer.PrintLargePdf(@"d:\test.pdf",pgs,ps)
iewer.ClosePdfFile()
```

### Guarda anche

* class [PdfViewer](../../pdfviewer)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdfviewer)
* assemblea [Aspose.PDF](../../../)

---

## PrintLargePdf(Stream, PageSettings, PrinterSettings) {#printlargepdf_1}

Apre e stampa un flusso Pdf di grandi dimensioni con le impostazioni di pagina e le impostazioni della stampante specificate. Se il tuo file Pdf ha centinaia di pagine o più o la sua dimensione è superiore a 3 MB, questo metodo è consigliato per ottenere prestazioni migliori.

```csharp
public void PrintLargePdf(Stream inputStream, PageSettings pageSettings, 
    PrinterSettings printerSettings)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputStream | Stream | Il flusso pdf da aprire e stampare. |
| pageSettings | PageSettings | Le impostazioni della pagina. |
| printerSettings | PrinterSettings | Le impostazioni della stampante. |

### Osservazioni

Questo metodo ha integrato l'apertura e la stampa del file e non è necessario chiamare OpenPdfFile() in modo esplicito.

### Esempi

```csharp
[C#]
dfViewer viewer = new PdfViewer();
iewer.AutoResize = true;       stampa il file con la dimensione regolata
iewer.AutoRotate = true;       stampa il file con la dimensione regolata
iewer.PrintPageDialog=false;stampa il file con la dimensione regolata
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
iewer.AutoResize = true       '//stampa il file con le dimensioni modificate
iewer.AutoRotate = true       '//stampa il file con la rotazione regolata
iewer.PrintPageDialog=false;stampa il file con la dimensione regolata
im ps As System.Drawing.Printing.PrinterSettings = new System.Drawing.Printing.PrinterSettings()
im prtdoc As PrintDocument = new PrintDocument()
s.PrinterName = prtdoc.PrinterSettings.PrinterName
im pgs As PageSettings=new PageSettings()
gs.PaperSize = new System.Drawing.Printing.PaperSize("A4", 827, 1169)
gs.Margins = new Margins(0, 0, 0, 0)
iewer.PrintLargePdf(new MemoryStream(File.ReadAllBytes(@"d:\middleware.pdf")),pgs,ps)
iewer.ClosePdfFile()
```

### Guarda anche

* class [PdfViewer](../../pdfviewer)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdfviewer)
* assemblea [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
