---
title: PdfViewer.PrintLargePdf
second_title: Aspose.PDF for .NET API Reference
description: Metode PdfViewer. Membuka dan mencetak file Pdf besar. Jika file Pdf Anda memiliki ratusan halaman atau lebih atau ukurannya lebih dari 3 MB, metode ini disarankan untuk mendapatkan kinerja yang lebih baik
type: docs
weight: 350
url: /id/net/aspose.pdf.facades/pdfviewer/printlargepdf/
---
## PrintLargePdf(string) {#printlargepdf_3}

Membuka dan mencetak file Pdf besar. Jika file Pdf Anda memiliki ratusan halaman atau lebih atau ukurannya lebih dari 3 MB, metode ini disarankan untuk mendapatkan kinerja yang lebih baik.

```csharp
public void PrintLargePdf(string filePath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| filePath | String | Jalur file Pdf. |

## Remarks

Metode ini mengintegrasikan pembukaan dan pencetakan file dan Anda tidak perlu memanggil BindPdf() secara eksplisit.

## Contoh

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

### Lihat Juga

* kelas [PdfViewer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## PrintLargePdf(Stream) {#printlargepdf}

Membuka dan mencetak aliran Pdf besar. Jika file Pdf Anda memiliki ratusan halaman atau lebih atau ukurannya lebih dari 3 MB, metode ini disarankan untuk mendapatkan kinerja yang lebih baik.

```csharp
public void PrintLargePdf(Stream inputStream)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputStream | Stream | Aliran pdf yang akan dibuka dan dicetak. |

## Remarks

Metode ini mengintegrasikan pembukaan dan pencetakan file dan Anda tidak perlu memanggil BindPdf() secara eksplisit.

## Contoh

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

### Lihat Juga

* kelas [PdfViewer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## PrintLargePdf(string, PrinterSettings) {#printlargepdf_5}

Membuka dan mencetak file Pdf besar dengan pengaturan printer yang ditentukan. Jika file Pdf Anda memiliki ratusan halaman atau lebih atau ukurannya lebih dari 3 MB, metode ini disarankan untuk mendapatkan kinerja yang lebih baik.

```csharp
public void PrintLargePdf(string filePath, PrinterSettings printerSettings)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| filePath | String | Jalur file Pdf. |
| printerSettings | PrinterSettings | Pengaturan printer. |

## Remarks

Metode ini mengintegrasikan pembukaan dan pencetakan file dan Anda tidak perlu memanggil BindPdf() secara eksplisit.

## Contoh

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

### Lihat Juga

* kelas [PrinterSettings](../../../aspose.pdf.printing/printersettings/)
* kelas [PdfViewer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## PrintLargePdf(Stream, PrinterSettings) {#printlargepdf_2}

Membuka dan mencetak aliran Pdf besar dengan pengaturan printer yang ditentukan. Jika file Pdf Anda memiliki ratusan halaman atau lebih atau ukurannya lebih dari 3 MB, metode ini disarankan untuk mendapatkan kinerja yang lebih baik.

```csharp
public void PrintLargePdf(Stream inputStream, PrinterSettings printerSettings)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputStream | Stream | Aliran pdf yang akan dibuka dan dicetak. |
| printerSettings | PrinterSettings | Pengaturan printer. |

## Remarks

Metode ini mengintegrasikan pembukaan dan pencetakan file dan Anda tidak perlu memanggil BindPdf() secara eksplisit.

## Contoh

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

### Lihat Juga

* kelas [PrinterSettings](../../../aspose.pdf.printing/printersettings/)
* kelas [PdfViewer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## PrintLargePdf(string, PageSettings, PrinterSettings) {#printlargepdf_4}

Membuka dan mencetak file Pdf besar dengan pengaturan halaman dan pengaturan printer yang ditentukan. Jika file Pdf Anda memiliki ratusan halaman atau lebih atau ukurannya lebih dari 3 MB, metode ini disarankan untuk mendapatkan kinerja yang lebih baik.

```csharp
public void PrintLargePdf(string filePath, PageSettings pageSettings, 
    PrinterSettings printerSettings)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| filePath | String | Jalur file Pdf. |
| pageSettings | PageSettings | Pengaturan halaman. |
| printerSettings | PrinterSettings | Pengaturan printer. |

## Remarks

Metode ini mengintegrasikan pembukaan dan pencetakan file dan Anda tidak perlu memanggil BindPdf() secara eksplisit.

## Contoh

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

### Lihat Juga

* kelas [PageSettings](../../../aspose.pdf.printing/pagesettings/)
* kelas [PrinterSettings](../../../aspose.pdf.printing/printersettings/)
* kelas [PdfViewer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## PrintLargePdf(Stream, PageSettings, PrinterSettings) {#printlargepdf_1}

Membuka dan mencetak aliran Pdf besar dengan pengaturan halaman dan pengaturan printer yang ditentukan. Jika file Pdf Anda memiliki ratusan halaman atau lebih atau ukurannya lebih dari 3 MB, metode ini disarankan untuk mendapatkan kinerja yang lebih baik.

```csharp
public void PrintLargePdf(Stream inputStream, PageSettings pageSettings, 
    PrinterSettings printerSettings)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputStream | Stream | Aliran pdf yang akan dibuka dan dicetak. |
| pageSettings | PageSettings | Pengaturan halaman. |
| printerSettings | PrinterSettings | Pengaturan printer. |

## Remarks

Metode ini mengintegrasikan pembukaan dan pencetakan file dan Anda tidak perlu memanggil BindPdf() secara eksplisit.

## Contoh

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

### Lihat Juga

* kelas [PageSettings](../../../aspose.pdf.printing/pagesettings/)
* kelas [PrinterSettings](../../../aspose.pdf.printing/printersettings/)
* kelas [PdfViewer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)