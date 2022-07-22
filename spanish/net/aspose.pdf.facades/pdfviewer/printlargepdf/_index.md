---
title: PrintLargePdf
second_title: Referencia de API de Aspose.PDF para .NET
description: Abre e imprime un archivo PDF grande. Si su archivo PDF tiene cientos de páginas o más o su tamaño es más de 3 MB se recomienda este método para obtener un mejor rendimiento.
type: docs
weight: 320
url: /es/net/aspose.pdf.facades/pdfviewer/printlargepdf/
---
## PrintLargePdf(string) {#printlargepdf_3}

Abre e imprime un archivo PDF grande. Si su archivo PDF tiene cientos de páginas o más o su tamaño es más de 3 MB, se recomienda este método para obtener un mejor rendimiento.

```csharp
public void PrintLargePdf(string filePath)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| filePath | String | La ruta del archivo PDF. |

### Observaciones

Este método ha integrado la apertura y la impresión del archivo y no necesita llamar a OpenPdfFile() explícitamente.

### Ejemplos

```csharp
[C#]
dfViewer viewer = new PdfViewer();
iewer.AutoResize = true;     //imprime el archivo con el tamaño ajustado
iewer.AutoRotate = true;     //imprime el archivo con rotación ajustada
iewer.PrintPageDialog=false;//no producir el cuadro de diálogo de número de página al imprimir
iewer.PrintLargePdf(@"d:\test.pdf");

VisualBasic]
im viewer As PdfViewer = new PdfViewer();
iewer.AutoResize = true      'imprimir el archivo con el tamaño ajustado
iewer.AutoRotate = true      'imprimir el archivo con rotación ajustada
iewer.PrintPageDialog=false;//no producir el cuadro de diálogo de número de página al imprimir
iewer.PrintLargePdf(@"d:\test.pdf")
iewer.ClosePdfFile();
```

### Ver también

* class [PdfViewer](../../pdfviewer)
* espacio de nombres [Aspose.Pdf.Facades](../../pdfviewer)
* asamblea [Aspose.PDF](../../../)

---

## PrintLargePdf(Stream) {#printlargepdf}

Abre e imprime una gran secuencia de PDF. Si su archivo PDF tiene cientos de páginas o más o su tamaño es más de 3 MB, se recomienda este método para obtener un mejor rendimiento.

```csharp
public void PrintLargePdf(Stream inputStream)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| inputStream | Stream | El flujo de pdf para ser abierto e impreso.. |

### Observaciones

Este método ha integrado la apertura y la impresión del archivo y no necesita llamar a OpenPdfFile() explícitamente.

### Ejemplos

```csharp
[C#]
dfViewer viewer = new PdfViewer();
iewer.AutoResize = true;        //imprime el archivo con el tamaño ajustado
iewer.AutoRotate = true;        //imprime el archivo con rotación ajustada
iewer.PrintPageDialog=false;//no producir el cuadro de diálogo de número de página al imprimir
iewer.PrintLargePdf(new MemoryStream(File.ReadAllBytes(@"d:\test.pdf")));
iewer.ClosePdfFile();

VisualBasic]
im viewer As PdfViewer = new PdfViewer();
iewer.AutoResize = true         'imprimir el archivo con el tamaño ajustado
iewer.AutoRotate = true         'imprimir el archivo con rotación ajustada
iewer.PrintPageDialog=false;//no producir el cuadro de diálogo de número de página al imprimir
iewer.PrintLargePdf(new MemoryStream(File.ReadAllBytes(@"d:\test.pdf")))
iewer.ClosePdfFile()
```

### Ver también

* class [PdfViewer](../../pdfviewer)
* espacio de nombres [Aspose.Pdf.Facades](../../pdfviewer)
* asamblea [Aspose.PDF](../../../)

---

## PrintLargePdf(string, PrinterSettings) {#printlargepdf_5}

Abre e imprime un archivo PDF grande con la configuración de impresora especificada. Si su archivo Pdf tiene cientos de de páginas o más o su tamaño es superior a 3 MB, se recomienda este método para obtener un mejor rendimiento.

```csharp
public void PrintLargePdf(string filePath, PrinterSettings printerSettings)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| filePath | String | La ruta del archivo PDF. |
| printerSettings | PrinterSettings | La configuración de la impresora. |

### Observaciones

Este método ha integrado la apertura y la impresión del archivo y no necesita llamar a OpenPdfFile() explícitamente.

### Ejemplos

```csharp
[C#]
dfViewer viewer = new PdfViewer();
iewer.AutoResize = true;       //imprime el archivo con el tamaño ajustado
iewer.AutoRotate = true;       //imprime el archivo con rotación ajustada
iewer.PrintPageDialog=false;//no producir el cuadro de diálogo de número de página al imprimir
ystem.Drawing.Printing.PrinterSettings ps = new System.Drawing.Printing.PrinterSettings();
rintDocument prtdoc = new PrintDocument();
s.PrinterName = prtdoc.PrinterSettings.PrinterName;
iewer.PrintLargePdf(@"d:\test.pdf",ps);
iewer.ClosePdfFile();

VisualBasic]
im viewer As PdfViewer = new PdfViewer();
iewer.AutoResize = true        'imprimir el archivo con el tamaño ajustado
iewer.AutoRotate = true        'imprimir el archivo con rotación ajustada
iewer.PrintPageDialog=false;//no producir el cuadro de diálogo de número de página al imprimir
im ps As System.Drawing.Printing.PrinterSettings = new System.Drawing.Printing.PrinterSettings()
im prtdoc As PrintDocument = new PrintDocument()
s.PrinterName = prtdoc.PrinterSettings.PrinterName
iewer.PrintLargePdf(@"d:\test.pdf",ps)
iewer.ClosePdfFile()
```

### Ver también

* class [PdfViewer](../../pdfviewer)
* espacio de nombres [Aspose.Pdf.Facades](../../pdfviewer)
* asamblea [Aspose.PDF](../../../)

---

## PrintLargePdf(Stream, PrinterSettings) {#printlargepdf_2}

Abre e imprime una gran secuencia de PDF con la configuración de impresora especificada. Si su archivo Pdf tiene cientos de de páginas o más o su tamaño es superior a 3 MB, se recomienda este método para obtener un mejor rendimiento.

```csharp
public void PrintLargePdf(Stream inputStream, PrinterSettings printerSettings)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| inputStream | Stream | El flujo de pdf para ser abierto e impreso.. |
| printerSettings | PrinterSettings | La configuración de la impresora. |

### Observaciones

Este método ha integrado la apertura y la impresión del archivo y no necesita llamar a OpenPdfFile() explícitamente.

### Ejemplos

```csharp
[C#]
dfViewer viewer = new PdfViewer();
iewer.AutoResize = true;       //imprime el archivo con el tamaño ajustado
iewer.AutoRotate = true;       //imprime el archivo con rotación ajustada
iewer.PrintPageDialog=false;//no producir el cuadro de diálogo de número de página al imprimir
ystem.Drawing.Printing.PrinterSettings ps = new System.Drawing.Printing.PrinterSettings();
rintDocument prtdoc = new PrintDocument();
s.PrinterName = prtdoc.PrinterSettings.PrinterName;
iewer.PrintLargePdf(new MemoryStream(File.ReadAllBytes(@"d:\middleware.pdf")),ps);
iewer.ClosePdfFile();

VisualBasic]
im viewer As PdfViewer = new PdfViewer();
iewer.AutoResize = true        'imprimir el archivo con el tamaño ajustado
iewer.AutoRotate = true        'imprimir el archivo con rotación ajustada
iewer.PrintPageDialog=false;//no producir el cuadro de diálogo de número de página al imprimir
im ps As System.Drawing.Printing.PrinterSettings = new System.Drawing.Printing.PrinterSettings()
im prtdoc As PrintDocument = new PrintDocument()
s.PrinterName = prtdoc.PrinterSettings.PrinterName
iewer.PrintLargePdf(new MemoryStream(File.ReadAllBytes(@"d:\middleware.pdf")),ps)
iewer.ClosePdfFile()
```

### Ver también

* class [PdfViewer](../../pdfviewer)
* espacio de nombres [Aspose.Pdf.Facades](../../pdfviewer)
* asamblea [Aspose.PDF](../../../)

---

## PrintLargePdf(string, PageSettings, PrinterSettings) {#printlargepdf_4}

Abre e imprime un archivo PDF grande con la configuración de página y la configuración de la impresora especificadas. Si su archivo Pdf tiene cientos de páginas o más o su tamaño es superior a 3 MB, se recomienda este método para obtener un mejor rendimiento.

```csharp
public void PrintLargePdf(string filePath, PageSettings pageSettings, 
    PrinterSettings printerSettings)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| filePath | String | La ruta del archivo PDF. |
| pageSettings | PageSettings | La configuración de la página. |
| printerSettings | PrinterSettings | La configuración de la impresora. |

### Observaciones

Este método ha integrado la apertura y la impresión del archivo y no necesita llamar a OpenPdfFile() explícitamente.

### Ejemplos

```csharp
[C#]
dfViewer viewer = new PdfViewer();
iewer.AutoResize = true;       //imprime el archivo con el tamaño ajustado
iewer.AutoRotate = true;       //imprime el archivo con rotación ajustada
iewer.PrintPageDialog=false;//no producir el cuadro de diálogo de número de página al imprimir
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
iewer.AutoResize = true       'imprimir el archivo con el tamaño ajustado
iewer.AutoRotate = true       'imprimir el archivo con rotación ajustada
iewer.PrintPageDialog=false;//no producir el cuadro de diálogo de número de página al imprimir
im ps As System.Drawing.Printing.PrinterSettings = new System.Drawing.Printing.PrinterSettings()
im prtdoc As PrintDocument = new PrintDocument()
s.PrinterName = prtdoc.PrinterSettings.PrinterName
im pgs As PageSettings=new PageSettings()
gs.PaperSize = new System.Drawing.Printing.PaperSize("A4", 827, 1169)
gs.Margins = new Margins(0, 0, 0, 0)
iewer.PrintLargePdf(@"d:\test.pdf",pgs,ps)
iewer.ClosePdfFile()
```

### Ver también

* class [PdfViewer](../../pdfviewer)
* espacio de nombres [Aspose.Pdf.Facades](../../pdfviewer)
* asamblea [Aspose.PDF](../../../)

---

## PrintLargePdf(Stream, PageSettings, PrinterSettings) {#printlargepdf_1}

Abre e imprime un flujo de PDF grande con configuraciones de página y configuraciones de impresora específicas. Si su archivo Pdf tiene cientos de páginas o más o su tamaño es superior a 3 MB, se recomienda este método para obtener un mejor rendimiento.

```csharp
public void PrintLargePdf(Stream inputStream, PageSettings pageSettings, 
    PrinterSettings printerSettings)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| inputStream | Stream | El flujo de pdf que se abrirá e imprimirá. |
| pageSettings | PageSettings | La configuración de la página. |
| printerSettings | PrinterSettings | La configuración de la impresora. |

### Observaciones

Este método ha integrado la apertura y la impresión del archivo y no necesita llamar a OpenPdfFile() explícitamente.

### Ejemplos

```csharp
[C#]
dfViewer viewer = new PdfViewer();
iewer.AutoResize = true;       //imprime el archivo con el tamaño ajustado
iewer.AutoRotate = true;       //imprime el archivo con rotación ajustada
iewer.PrintPageDialog=false;//no producir el cuadro de diálogo de número de página al imprimir
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
iewer.AutoResize = true       'imprimir el archivo con el tamaño ajustado
iewer.AutoRotate = true       'imprimir el archivo con rotación ajustada
iewer.PrintPageDialog=false;//no producir el cuadro de diálogo de número de página al imprimir
im ps As System.Drawing.Printing.PrinterSettings = new System.Drawing.Printing.PrinterSettings()
im prtdoc As PrintDocument = new PrintDocument()
s.PrinterName = prtdoc.PrinterSettings.PrinterName
im pgs As PageSettings=new PageSettings()
gs.PaperSize = new System.Drawing.Printing.PaperSize("A4", 827, 1169)
gs.Margins = new Margins(0, 0, 0, 0)
iewer.PrintLargePdf(new MemoryStream(File.ReadAllBytes(@"d:\middleware.pdf")),pgs,ps)
iewer.ClosePdfFile()
```

### Ver también

* class [PdfViewer](../../pdfviewer)
* espacio de nombres [Aspose.Pdf.Facades](../../pdfviewer)
* asamblea [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
