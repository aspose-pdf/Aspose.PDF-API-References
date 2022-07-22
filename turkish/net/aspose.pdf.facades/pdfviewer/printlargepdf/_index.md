---
title: PrintLargePdf
second_title: Aspose.PDF for .NET API Referansı
description: Büyük bir Pdf dosyası açar ve yazdırır. Pdf dosyanız yüzlerce veya daha fazla sayfa içeriyorsa veya boyutu 3 MBden ise daha iyi performans elde etmek için bu yöntem önerilir.
type: docs
weight: 320
url: /tr/net/aspose.pdf.facades/pdfviewer/printlargepdf/
---
## PrintLargePdf(string) {#printlargepdf_3}

Büyük bir Pdf dosyası açar ve yazdırır. Pdf dosyanız yüzlerce veya daha fazla sayfa içeriyorsa veya boyutu 3 MB'den ise, daha iyi performans elde etmek için bu yöntem önerilir.

```csharp
public void PrintLargePdf(string filePath)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| filePath | String | Pdf dosyasının yolu. |

### Notlar

Bu yöntem, dosyanın açılmasını ve yazdırılmasını entegre etmiştir ve OpenPdfFile() öğesini açıkça çağırmanız gerekmez.

### Örnekler

```csharp
[C#]
dfViewer viewer = new PdfViewer();
iewer.AutoResize = true;     // dosyayı ayarlanmış boyutta yazdır
iewer.AutoRotate = true;     // dosyayı ayarlanmış rotasyonla yazdır
iewer.PrintPageDialog=false;// yazdırırken sayfa numarası diyaloğunu oluşturma
iewer.PrintLargePdf(@"d:\test.pdf");

VisualBasic]
im viewer As PdfViewer = new PdfViewer();
iewer.AutoResize = true      'dosyayı ayarlanmış boyutta yazdır
iewer.AutoRotate = true      'dosyayı ayarlanmış rotasyonla yazdır
iewer.PrintPageDialog=false;// yazdırırken sayfa numarası diyaloğunu oluşturma
iewer.PrintLargePdf(@"d:\test.pdf")
iewer.ClosePdfFile();
```

### Ayrıca bakınız

* class [PdfViewer](../../pdfviewer)
* ad alanı [Aspose.Pdf.Facades](../../pdfviewer)
* toplantı [Aspose.PDF](../../../)

---

## PrintLargePdf(Stream) {#printlargepdf}

Büyük bir Pdf akışını açar ve yazdırır. Pdf dosyanız yüzlerce veya daha fazla sayfa içeriyorsa veya boyutu 3 MB'den ise, daha iyi performans elde etmek için bu yöntem önerilir.

```csharp
public void PrintLargePdf(Stream inputStream)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| inputStream | Stream | Açılacak ve yazdırılacak pdf akışı.. |

### Notlar

Bu yöntem, dosyanın açılmasını ve yazdırılmasını entegre etmiştir ve OpenPdfFile() öğesini açıkça çağırmanız gerekmez.

### Örnekler

```csharp
[C#]
dfViewer viewer = new PdfViewer();
iewer.AutoResize = true;        // dosyayı ayarlanmış boyutta yazdır
iewer.AutoRotate = true;        // dosyayı ayarlanmış rotasyonla yazdır
iewer.PrintPageDialog=false;// yazdırırken sayfa numarası diyaloğunu oluşturma
iewer.PrintLargePdf(new MemoryStream(File.ReadAllBytes(@"d:\test.pdf")));
iewer.ClosePdfFile();

VisualBasic]
im viewer As PdfViewer = new PdfViewer();
iewer.AutoResize = true         'dosyayı ayarlanmış boyutta yazdır
iewer.AutoRotate = true         'dosyayı ayarlanmış rotasyonla yazdır
iewer.PrintPageDialog=false;// yazdırırken sayfa numarası diyaloğunu oluşturma
iewer.PrintLargePdf(new MemoryStream(File.ReadAllBytes(@"d:\test.pdf")))
iewer.ClosePdfFile()
```

### Ayrıca bakınız

* class [PdfViewer](../../pdfviewer)
* ad alanı [Aspose.Pdf.Facades](../../pdfviewer)
* toplantı [Aspose.PDF](../../../)

---

## PrintLargePdf(string, PrinterSettings) {#printlargepdf_5}

Belirtilen yazıcı ayarlarıyla büyük bir Pdf dosyası açar ve yazdırır. Pdf dosyanız yüzlerce veya daha fazla sayfa içeriyorsa veya boyutu 3 MB'den büyükse, daha iyi performans elde etmek için bu yöntem önerilir.

```csharp
public void PrintLargePdf(string filePath, PrinterSettings printerSettings)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| filePath | String | Pdf dosyasının yolu. |
| printerSettings | PrinterSettings | Yazıcı ayarları. |

### Notlar

Bu yöntem, dosyanın açılmasını ve yazdırılmasını entegre etmiştir ve OpenPdfFile() öğesini açıkça çağırmanız gerekmez.

### Örnekler

```csharp
[C#]
dfViewer viewer = new PdfViewer();
iewer.AutoResize = true;       // dosyayı ayarlanmış boyutta yazdır
iewer.AutoRotate = true;       // dosyayı ayarlanmış rotasyonla yazdır
iewer.PrintPageDialog=false;// yazdırırken sayfa numarası diyaloğunu oluşturma
ystem.Drawing.Printing.PrinterSettings ps = new System.Drawing.Printing.PrinterSettings();
rintDocument prtdoc = new PrintDocument();
s.PrinterName = prtdoc.PrinterSettings.PrinterName;
iewer.PrintLargePdf(@"d:\test.pdf",ps);
iewer.ClosePdfFile();

VisualBasic]
im viewer As PdfViewer = new PdfViewer();
iewer.AutoResize = true        'dosyayı ayarlanmış boyutta yazdır
iewer.AutoRotate = true        'dosyayı ayarlanmış rotasyonla yazdır
iewer.PrintPageDialog=false;// yazdırırken sayfa numarası diyaloğunu oluşturma
im ps As System.Drawing.Printing.PrinterSettings = new System.Drawing.Printing.PrinterSettings()
im prtdoc As PrintDocument = new PrintDocument()
s.PrinterName = prtdoc.PrinterSettings.PrinterName
iewer.PrintLargePdf(@"d:\test.pdf",ps)
iewer.ClosePdfFile()
```

### Ayrıca bakınız

* class [PdfViewer](../../pdfviewer)
* ad alanı [Aspose.Pdf.Facades](../../pdfviewer)
* toplantı [Aspose.PDF](../../../)

---

## PrintLargePdf(Stream, PrinterSettings) {#printlargepdf_2}

Belirtilen yazıcı ayarlarıyla büyük bir Pdf akışını açar ve yazdırır. Pdf dosyanız yüzlerce veya daha fazla sayfa içeriyorsa veya boyutu 3 MB'den büyükse, daha iyi performans elde etmek için bu yöntem önerilir.

```csharp
public void PrintLargePdf(Stream inputStream, PrinterSettings printerSettings)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| inputStream | Stream | Açılacak ve yazdırılacak pdf akışı.. |
| printerSettings | PrinterSettings | Yazıcı ayarları. |

### Notlar

Bu yöntem, dosyanın açılmasını ve yazdırılmasını entegre etmiştir ve OpenPdfFile() öğesini açıkça çağırmanız gerekmez.

### Örnekler

```csharp
[C#]
dfViewer viewer = new PdfViewer();
iewer.AutoResize = true;       // dosyayı ayarlanmış boyutta yazdır
iewer.AutoRotate = true;       // dosyayı ayarlanmış rotasyonla yazdır
iewer.PrintPageDialog=false;// yazdırırken sayfa numarası diyaloğunu oluşturma
ystem.Drawing.Printing.PrinterSettings ps = new System.Drawing.Printing.PrinterSettings();
rintDocument prtdoc = new PrintDocument();
s.PrinterName = prtdoc.PrinterSettings.PrinterName;
iewer.PrintLargePdf(new MemoryStream(File.ReadAllBytes(@"d:\middleware.pdf")),ps);
iewer.ClosePdfFile();

VisualBasic]
im viewer As PdfViewer = new PdfViewer();
iewer.AutoResize = true        'dosyayı ayarlanmış boyutta yazdır
iewer.AutoRotate = true        'dosyayı ayarlanmış rotasyonla yazdır
iewer.PrintPageDialog=false;// yazdırırken sayfa numarası diyaloğunu oluşturma
im ps As System.Drawing.Printing.PrinterSettings = new System.Drawing.Printing.PrinterSettings()
im prtdoc As PrintDocument = new PrintDocument()
s.PrinterName = prtdoc.PrinterSettings.PrinterName
iewer.PrintLargePdf(new MemoryStream(File.ReadAllBytes(@"d:\middleware.pdf")),ps)
iewer.ClosePdfFile()
```

### Ayrıca bakınız

* class [PdfViewer](../../pdfviewer)
* ad alanı [Aspose.Pdf.Facades](../../pdfviewer)
* toplantı [Aspose.PDF](../../../)

---

## PrintLargePdf(string, PageSettings, PrinterSettings) {#printlargepdf_4}

Belirtilen sayfa ayarları ve yazıcı ayarları ile büyük bir Pdf dosyası açar ve yazdırır. Pdf dosyanız yüzlerce veya daha fazla sayfa içeriyorsa veya boyutu 3 MB'den büyükse, daha iyi performans elde etmek için bu yöntem önerilir.

```csharp
public void PrintLargePdf(string filePath, PageSettings pageSettings, 
    PrinterSettings printerSettings)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| filePath | String | Pdf dosyasının yolu. |
| pageSettings | PageSettings | Sayfa ayarları. |
| printerSettings | PrinterSettings | Yazıcı ayarları. |

### Notlar

Bu yöntem, dosyanın açılmasını ve yazdırılmasını entegre etmiştir ve OpenPdfFile() öğesini açıkça çağırmanız gerekmez.

### Örnekler

```csharp
[C#]
dfViewer viewer = new PdfViewer();
iewer.AutoResize = true;       // dosyayı ayarlanmış boyutta yazdır
iewer.AutoRotate = true;       // dosyayı ayarlanmış rotasyonla yazdır
iewer.PrintPageDialog=false;// yazdırırken sayfa numarası diyaloğunu oluşturma
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
iewer.AutoResize = true       'dosyayı ayarlanmış boyutta yazdır
iewer.AutoRotate = true       'dosyayı ayarlanmış rotasyonla yazdır
iewer.PrintPageDialog=false;// yazdırırken sayfa numarası diyaloğunu oluşturma
im ps As System.Drawing.Printing.PrinterSettings = new System.Drawing.Printing.PrinterSettings()
im prtdoc As PrintDocument = new PrintDocument()
s.PrinterName = prtdoc.PrinterSettings.PrinterName
im pgs As PageSettings=new PageSettings()
gs.PaperSize = new System.Drawing.Printing.PaperSize("A4", 827, 1169)
gs.Margins = new Margins(0, 0, 0, 0)
iewer.PrintLargePdf(@"d:\test.pdf",pgs,ps)
iewer.ClosePdfFile()
```

### Ayrıca bakınız

* class [PdfViewer](../../pdfviewer)
* ad alanı [Aspose.Pdf.Facades](../../pdfviewer)
* toplantı [Aspose.PDF](../../../)

---

## PrintLargePdf(Stream, PageSettings, PrinterSettings) {#printlargepdf_1}

Belirtilen sayfa ayarları ve yazıcı ayarları ile büyük bir Pdf akışını açar ve yazdırır. Pdf dosyanız yüzlerce veya daha fazla sayfa içeriyorsa veya boyutu 3 MB'den büyükse, daha iyi performans elde etmek için bu yöntem önerilir.

```csharp
public void PrintLargePdf(Stream inputStream, PageSettings pageSettings, 
    PrinterSettings printerSettings)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| inputStream | Stream | Açılacak ve yazdırılacak pdf akışı. |
| pageSettings | PageSettings | Sayfa ayarları. |
| printerSettings | PrinterSettings | Yazıcı ayarları. |

### Notlar

Bu yöntem, dosyanın açılmasını ve yazdırılmasını entegre etmiştir ve OpenPdfFile() öğesini açıkça çağırmanız gerekmez.

### Örnekler

```csharp
[C#]
dfViewer viewer = new PdfViewer();
iewer.AutoResize = true;       // dosyayı ayarlanmış boyutta yazdır
iewer.AutoRotate = true;       // dosyayı ayarlanmış rotasyonla yazdır
iewer.PrintPageDialog=false;// yazdırırken sayfa numarası diyaloğunu oluşturma
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
iewer.AutoResize = true       'dosyayı ayarlanmış boyutta yazdır
iewer.AutoRotate = true       'dosyayı ayarlanmış rotasyonla yazdır
iewer.PrintPageDialog=false;// yazdırırken sayfa numarası diyaloğunu oluşturma
im ps As System.Drawing.Printing.PrinterSettings = new System.Drawing.Printing.PrinterSettings()
im prtdoc As PrintDocument = new PrintDocument()
s.PrinterName = prtdoc.PrinterSettings.PrinterName
im pgs As PageSettings=new PageSettings()
gs.PaperSize = new System.Drawing.Printing.PaperSize("A4", 827, 1169)
gs.Margins = new Margins(0, 0, 0, 0)
iewer.PrintLargePdf(new MemoryStream(File.ReadAllBytes(@"d:\middleware.pdf")),pgs,ps)
iewer.ClosePdfFile()
```

### Ayrıca bakınız

* class [PdfViewer](../../pdfviewer)
* ad alanı [Aspose.Pdf.Facades](../../pdfviewer)
* toplantı [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
