---
title: PdfViewer.PrintLargePdf
second_title: Aspose.PDF for .NET API Reference
description: Méthode PdfViewer. Ouvre et imprime un grand fichier Pdf. Si votre fichier Pdf contient des centaines de pages ou plus ou si sa taille est supérieure à 3 Mo, cette méthode est recommandée pour obtenir de meilleures performances
type: docs
weight: 350
url: /fr/net/aspose.pdf.facades/pdfviewer/printlargepdf/
---
## PrintLargePdf(string) {#printlargepdf_3}

Ouvre et imprime un grand fichier Pdf. Si votre fichier Pdf contient des centaines de pages ou plus ou si sa taille est supérieure à 3 Mo, cette méthode est recommandée pour obtenir de meilleures performances.

```csharp
public void PrintLargePdf(string filePath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| filePath | String | Le chemin du fichier Pdf. |

## Remarques

Cette méthode intègre l'ouverture et l'impression du fichier et vous n'avez pas besoin d'appeler BindPdf() explicitement.

## Exemples

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

### Voir aussi

* classe [PdfViewer](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## PrintLargePdf(Stream) {#printlargepdf}

Ouvre et imprime un grand flux Pdf. Si votre fichier Pdf contient des centaines de pages ou plus ou si sa taille est supérieure à 3 Mo, cette méthode est recommandée pour obtenir de meilleures performances.

```csharp
public void PrintLargePdf(Stream inputStream)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| inputStream | Stream | Le flux pdf à ouvrir et à imprimer. |

## Remarques

Cette méthode intègre l'ouverture et l'impression du fichier et vous n'avez pas besoin d'appeler BindPdf() explicitement.

## Exemples

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

### Voir aussi

* classe [PdfViewer](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## PrintLargePdf(string, PrinterSettings) {#printlargepdf_5}

Ouvre et imprime un grand fichier Pdf avec des paramètres d'imprimante spécifiés. Si votre fichier Pdf contient des centaines de pages ou plus ou si sa taille est supérieure à 3 Mo, cette méthode est recommandée pour obtenir de meilleures performances.

```csharp
public void PrintLargePdf(string filePath, PrinterSettings printerSettings)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| filePath | String | Le chemin du fichier Pdf. |
| printerSettings | PrinterSettings | Les paramètres de l'imprimante. |

## Remarques

Cette méthode intègre l'ouverture et l'impression du fichier et vous n'avez pas besoin d'appeler BindPdf() explicitement.

## Exemples

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

### Voir aussi

* classe [PrinterSettings](../../../aspose.pdf.printing/printersettings/)
* classe [PdfViewer](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## PrintLargePdf(Stream, PrinterSettings) {#printlargepdf_2}

Ouvre et imprime un grand flux Pdf avec des paramètres d'imprimante spécifiés. Si votre fichier Pdf contient des centaines de pages ou plus ou si sa taille est supérieure à 3 Mo, cette méthode est recommandée pour obtenir de meilleures performances.

```csharp
public void PrintLargePdf(Stream inputStream, PrinterSettings printerSettings)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| inputStream | Stream | Le flux pdf à ouvrir et à imprimer. |
| printerSettings | PrinterSettings | Les paramètres de l'imprimante. |

## Remarques

Cette méthode intègre l'ouverture et l'impression du fichier et vous n'avez pas besoin d'appeler BindPdf() explicitement.

## Exemples

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

### Voir aussi

* classe [PrinterSettings](../../../aspose.pdf.printing/printersettings/)
* classe [PdfViewer](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## PrintLargePdf(string, PageSettings, PrinterSettings) {#printlargepdf_4}

Ouvre et imprime un grand fichier Pdf avec des paramètres de page et des paramètres d'imprimante spécifiés. Si votre fichier Pdf contient des centaines de pages ou plus ou si sa taille est supérieure à 3 Mo, cette méthode est recommandée pour obtenir de meilleures performances.

```csharp
public void PrintLargePdf(string filePath, PageSettings pageSettings, 
    PrinterSettings printerSettings)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| filePath | String | Le chemin du fichier Pdf. |
| pageSettings | PageSettings | Les paramètres de page. |
| printerSettings | PrinterSettings | Les paramètres de l'imprimante. |

## Remarques

Cette méthode intègre l'ouverture et l'impression du fichier et vous n'avez pas besoin d'appeler BindPdf() explicitement.

## Exemples

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

### Voir aussi

* classe [PageSettings](../../../aspose.pdf.printing/pagesettings/)
* classe [PrinterSettings](../../../aspose.pdf.printing/printersettings/)
* classe [PdfViewer](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## PrintLargePdf(Stream, PageSettings, PrinterSettings) {#printlargepdf_1}

Ouvre et imprime un grand flux Pdf avec des paramètres de page et des paramètres d'imprimante spécifiés. Si votre fichier Pdf contient des centaines de pages ou plus ou si sa taille est supérieure à 3 Mo, cette méthode est recommandée pour obtenir de meilleures performances.

```csharp
public void PrintLargePdf(Stream inputStream, PageSettings pageSettings, 
    PrinterSettings printerSettings)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| inputStream | Stream | Le flux pdf à ouvrir et à imprimer. |
| pageSettings | PageSettings | Les paramètres de page. |
| printerSettings | PrinterSettings | Les paramètres de l'imprimante. |

## Remarques

Cette méthode intègre l'ouverture et l'impression du fichier et vous n'avez pas besoin d'appeler BindPdf() explicitement.

## Exemples

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

### Voir aussi

* classe [PageSettings](../../../aspose.pdf.printing/pagesettings/)
* classe [PrinterSettings](../../../aspose.pdf.printing/printersettings/)
* classe [PdfViewer](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)