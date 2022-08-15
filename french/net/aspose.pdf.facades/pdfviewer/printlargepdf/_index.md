---
title: PrintLargePdf
second_title: Référence de l'API Aspose.PDF pour .NET
description: Ouvre et imprime un gros fichier PDF. Si votre fichier PDF contient des centaines de pages ou plus ou si sa taille est supérieure à 3 Mo cette méthode est recommandée pour obtenir de meilleures performances.
type: docs
weight: 320
url: /fr/net/aspose.pdf.facades/pdfviewer/printlargepdf/
---
## PrintLargePdf(string) {#printlargepdf_3}

Ouvre et imprime un gros fichier PDF. Si votre fichier PDF contient des centaines de pages ou plus ou si sa taille est supérieure à 3 Mo, cette méthode est recommandée pour obtenir de meilleures performances.

```csharp
public void PrintLargePdf(string filePath)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| filePath | String | Le chemin du fichier Pdf. |

### Remarques

Cette méthode a intégré l'ouverture et l'impression du fichier et vous n'avez pas besoin d'appeler explicitement OpenPdfFile().

### Exemples

```csharp
[C#]
dfViewer viewer = new PdfViewer();
iewer.AutoResize = true;     //imprimer le fichier avec la taille ajustée
iewer.AutoRotate = true;     //imprime le fichier avec une rotation ajustée
iewer.PrintPageDialog=false;// ne produit pas la boîte de dialogue de numéro de page lors de l'impression
iewer.PrintLargePdf(@"d:\test.pdf");

VisualBasic]
im viewer As PdfViewer = new PdfViewer();
iewer.AutoResize = true      'imprimer le fichier avec la taille ajustée
iewer.AutoRotate = true      'imprimer le fichier avec une rotation ajustée
iewer.PrintPageDialog=false;// ne produit pas la boîte de dialogue de numéro de page lors de l'impression
iewer.PrintLargePdf(@"d:\test.pdf")
iewer.ClosePdfFile();
```

### Voir également

* class [PdfViewer](../../pdfviewer)
* espace de noms [Aspose.Pdf.Facades](../../pdfviewer)
* Assemblée [Aspose.PDF](../../../)

---

## PrintLargePdf(Stream) {#printlargepdf}

Ouvre et imprime un gros flux Pdf. Si votre fichier PDF contient des centaines de pages ou plus ou si sa taille est supérieure à 3 Mo, cette méthode est recommandée pour obtenir de meilleures performances.

```csharp
public void PrintLargePdf(Stream inputStream)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| inputStream | Stream | Le flux pdf à ouvrir et imprimer.. |

### Remarques

Cette méthode a intégré l'ouverture et l'impression du fichier et vous n'avez pas besoin d'appeler explicitement OpenPdfFile().

### Exemples

```csharp
[C#]
dfViewer viewer = new PdfViewer();
iewer.AutoResize = true;        //imprimer le fichier avec la taille ajustée
iewer.AutoRotate = true;        //imprime le fichier avec une rotation ajustée
iewer.PrintPageDialog=false;// ne produit pas la boîte de dialogue de numéro de page lors de l'impression
iewer.PrintLargePdf(new MemoryStream(File.ReadAllBytes(@"d:\test.pdf")));
iewer.ClosePdfFile();

VisualBasic]
im viewer As PdfViewer = new PdfViewer();
iewer.AutoResize = true         'imprimer le fichier avec la taille ajustée
iewer.AutoRotate = true         'imprimer le fichier avec une rotation ajustée
iewer.PrintPageDialog=false;// ne produit pas la boîte de dialogue de numéro de page lors de l'impression
iewer.PrintLargePdf(new MemoryStream(File.ReadAllBytes(@"d:\test.pdf")))
iewer.ClosePdfFile()
```

### Voir également

* class [PdfViewer](../../pdfviewer)
* espace de noms [Aspose.Pdf.Facades](../../pdfviewer)
* Assemblée [Aspose.PDF](../../../)

---

## PrintLargePdf(string, PrinterSettings) {#printlargepdf_5}

Ouvre et imprime un gros fichier PDF avec les paramètres d'imprimante spécifiés. Si votre fichier PDF contient des centaines de pages ou plus ou si sa taille est supérieure à 3 Mo, cette méthode est recommandée pour obtenir de meilleures performances.

```csharp
public void PrintLargePdf(string filePath, PrinterSettings printerSettings)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| filePath | String | Le chemin du fichier Pdf. |
| printerSettings | PrinterSettings | Les paramètres de l'imprimante. |

### Remarques

Cette méthode a intégré l'ouverture et l'impression du fichier et vous n'avez pas besoin d'appeler explicitement OpenPdfFile().

### Exemples

```csharp
[C#]
dfViewer viewer = new PdfViewer();
iewer.AutoResize = true;       //imprimer le fichier avec la taille ajustée
iewer.AutoRotate = true;       //imprime le fichier avec une rotation ajustée
iewer.PrintPageDialog=false;// ne produit pas la boîte de dialogue de numéro de page lors de l'impression
ystem.Drawing.Printing.PrinterSettings ps = new System.Drawing.Printing.PrinterSettings();
rintDocument prtdoc = new PrintDocument();
s.PrinterName = prtdoc.PrinterSettings.PrinterName;
iewer.PrintLargePdf(@"d:\test.pdf",ps);
iewer.ClosePdfFile();

VisualBasic]
im viewer As PdfViewer = new PdfViewer();
iewer.AutoResize = true        'imprimer le fichier avec la taille ajustée
iewer.AutoRotate = true        'imprimer le fichier avec une rotation ajustée
iewer.PrintPageDialog=false;// ne produit pas la boîte de dialogue de numéro de page lors de l'impression
im ps As System.Drawing.Printing.PrinterSettings = new System.Drawing.Printing.PrinterSettings()
im prtdoc As PrintDocument = new PrintDocument()
s.PrinterName = prtdoc.PrinterSettings.PrinterName
iewer.PrintLargePdf(@"d:\test.pdf",ps)
iewer.ClosePdfFile()
```

### Voir également

* class [PdfViewer](../../pdfviewer)
* espace de noms [Aspose.Pdf.Facades](../../pdfviewer)
* Assemblée [Aspose.PDF](../../../)

---

## PrintLargePdf(Stream, PrinterSettings) {#printlargepdf_2}

Ouvre et imprime un grand flux Pdf avec les paramètres d'imprimante spécifiés. Si votre fichier PDF contient des centaines de pages ou plus ou si sa taille est supérieure à 3 Mo, cette méthode est recommandée pour obtenir de meilleures performances.

```csharp
public void PrintLargePdf(Stream inputStream, PrinterSettings printerSettings)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| inputStream | Stream | Le flux pdf à ouvrir et imprimer.. |
| printerSettings | PrinterSettings | Les paramètres de l'imprimante. |

### Remarques

Cette méthode a intégré l'ouverture et l'impression du fichier et vous n'avez pas besoin d'appeler explicitement OpenPdfFile().

### Exemples

```csharp
[C#]
dfViewer viewer = new PdfViewer();
iewer.AutoResize = true;       //imprimer le fichier avec la taille ajustée
iewer.AutoRotate = true;       //imprime le fichier avec une rotation ajustée
iewer.PrintPageDialog=false;// ne produit pas la boîte de dialogue de numéro de page lors de l'impression
ystem.Drawing.Printing.PrinterSettings ps = new System.Drawing.Printing.PrinterSettings();
rintDocument prtdoc = new PrintDocument();
s.PrinterName = prtdoc.PrinterSettings.PrinterName;
iewer.PrintLargePdf(new MemoryStream(File.ReadAllBytes(@"d:\middleware.pdf")),ps);
iewer.ClosePdfFile();

VisualBasic]
im viewer As PdfViewer = new PdfViewer();
iewer.AutoResize = true        'imprimer le fichier avec la taille ajustée
iewer.AutoRotate = true        'imprimer le fichier avec une rotation ajustée
iewer.PrintPageDialog=false;// ne produit pas la boîte de dialogue de numéro de page lors de l'impression
im ps As System.Drawing.Printing.PrinterSettings = new System.Drawing.Printing.PrinterSettings()
im prtdoc As PrintDocument = new PrintDocument()
s.PrinterName = prtdoc.PrinterSettings.PrinterName
iewer.PrintLargePdf(new MemoryStream(File.ReadAllBytes(@"d:\middleware.pdf")),ps)
iewer.ClosePdfFile()
```

### Voir également

* class [PdfViewer](../../pdfviewer)
* espace de noms [Aspose.Pdf.Facades](../../pdfviewer)
* Assemblée [Aspose.PDF](../../../)

---

## PrintLargePdf(string, PageSettings, PrinterSettings) {#printlargepdf_4}

Ouvre et imprime un gros fichier PDF avec les paramètres de page et les paramètres d'imprimante spécifiés. Si votre fichier PDF contient des centaines de pages ou plus ou si sa taille est supérieure à 3 Mo, cette méthode est recommandée pour obtenir de meilleures performances.

```csharp
public void PrintLargePdf(string filePath, PageSettings pageSettings, 
    PrinterSettings printerSettings)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| filePath | String | Le chemin du fichier Pdf. |
| pageSettings | PageSettings | Les paramètres de la page. |
| printerSettings | PrinterSettings | Les paramètres de l'imprimante. |

### Remarques

Cette méthode a intégré l'ouverture et l'impression du fichier et vous n'avez pas besoin d'appeler explicitement OpenPdfFile().

### Exemples

```csharp
[C#]
dfViewer viewer = new PdfViewer();
iewer.AutoResize = true;       //imprimer le fichier avec la taille ajustée
iewer.AutoRotate = true;       //imprime le fichier avec une rotation ajustée
iewer.PrintPageDialog=false;// ne produit pas la boîte de dialogue de numéro de page lors de l'impression
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
iewer.AutoResize = true       'imprimer le fichier avec la taille ajustée
iewer.AutoRotate = true       'imprimer le fichier avec une rotation ajustée
iewer.PrintPageDialog=false;// ne produit pas la boîte de dialogue de numéro de page lors de l'impression
im ps As System.Drawing.Printing.PrinterSettings = new System.Drawing.Printing.PrinterSettings()
im prtdoc As PrintDocument = new PrintDocument()
s.PrinterName = prtdoc.PrinterSettings.PrinterName
im pgs As PageSettings=new PageSettings()
gs.PaperSize = new System.Drawing.Printing.PaperSize("A4", 827, 1169)
gs.Margins = new Margins(0, 0, 0, 0)
iewer.PrintLargePdf(@"d:\test.pdf",pgs,ps)
iewer.ClosePdfFile()
```

### Voir également

* class [PdfViewer](../../pdfviewer)
* espace de noms [Aspose.Pdf.Facades](../../pdfviewer)
* Assemblée [Aspose.PDF](../../../)

---

## PrintLargePdf(Stream, PageSettings, PrinterSettings) {#printlargepdf_1}

Ouvre et imprime un flux Pdf volumineux avec des paramètres de page et des paramètres d'imprimante spécifiés. Si votre fichier PDF contient des centaines de pages ou plus ou si sa taille est supérieure à 3 Mo, cette méthode est recommandée pour obtenir de meilleures performances.

```csharp
public void PrintLargePdf(Stream inputStream, PageSettings pageSettings, 
    PrinterSettings printerSettings)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| inputStream | Stream | Le flux pdf à ouvrir et à imprimer. |
| pageSettings | PageSettings | Les paramètres de la page. |
| printerSettings | PrinterSettings | Les paramètres de l'imprimante. |

### Remarques

Cette méthode a intégré l'ouverture et l'impression du fichier et vous n'avez pas besoin d'appeler explicitement OpenPdfFile().

### Exemples

```csharp
[C#]
dfViewer viewer = new PdfViewer();
iewer.AutoResize = true;       //imprimer le fichier avec la taille ajustée
iewer.AutoRotate = true;       //imprime le fichier avec une rotation ajustée
iewer.PrintPageDialog=false;// ne produit pas la boîte de dialogue de numéro de page lors de l'impression
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
iewer.AutoResize = true       'imprimer le fichier avec la taille ajustée
iewer.AutoRotate = true       'imprimer le fichier avec une rotation ajustée
iewer.PrintPageDialog=false;// ne produit pas la boîte de dialogue de numéro de page lors de l'impression
im ps As System.Drawing.Printing.PrinterSettings = new System.Drawing.Printing.PrinterSettings()
im prtdoc As PrintDocument = new PrintDocument()
s.PrinterName = prtdoc.PrinterSettings.PrinterName
im pgs As PageSettings=new PageSettings()
gs.PaperSize = new System.Drawing.Printing.PaperSize("A4", 827, 1169)
gs.Margins = new Margins(0, 0, 0, 0)
iewer.PrintLargePdf(new MemoryStream(File.ReadAllBytes(@"d:\middleware.pdf")),pgs,ps)
iewer.ClosePdfFile()
```

### Voir également

* class [PdfViewer](../../pdfviewer)
* espace de noms [Aspose.Pdf.Facades](../../pdfviewer)
* Assemblée [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
