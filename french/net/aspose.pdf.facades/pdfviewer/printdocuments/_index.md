---
title: "PdfViewer.PrintDocuments"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Méthode PdfViewer. Imprime plusieurs documents PDF en utilisant l'imprimante par défaut et les paramètres de page"
type: docs
weight: 370
url: /fr/net/aspose.pdf.facades/pdfviewer/printdocuments/
---
## PrintDocuments(params Document[]) {#printdocuments}

Imprime plusieurs documents PDF en utilisant l'imprimante et les paramètres de page par défaut.

```csharp
public static void PrintDocuments(params Document[] documents)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| documents | Document[] | Un tableau d'objets [`Document`](../../../aspose.pdf/document/) représentant les documents PDF à imprimer. |

## Remarques

Cette méthode permet d'imprimer plusieurs documents PDF en une seule tâche d'impression.

## Exemples

```csharp
[C#]
using (Aspose.Pdf.Document document1 = new Aspose.Pdf.Document(dataDir + "PrintDocument.pdf"),
                           document2 = new Aspose.Pdf.Document(dataDir + "Print-PageRange.pdf"),
                           document3 = new Aspose.Pdf.Document(dataDir + "35925_1_3.xps", new Aspose.Pdf.XpsLoadOptions()))
{
    Aspose.Pdf.Facades.PdfViewer.PrintDocuments(document1, document2, document3);
}

[VisualBasic]
Using document1 As New Aspose.Pdf.Document(dataDir & "PrintDocument.pdf"),
      document2 As New Aspose.Pdf.Document(dataDir & "Print-PageRange.pdf"),
      document3 As New Aspose.Pdf.Document(dataDir & "35925_1_3.xps", New Aspose.Pdf.XpsLoadOptions())
     Aspose.Pdf.Facades.PdfViewer.PrintDocuments(document1, document2, document3)
End Using
```

### Voir aussi

* class [Document](../../../aspose.pdf/document/)
* class [PdfViewer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## PrintDocuments(params string[]) {#printdocuments_8}

Imprime plusieurs documents PDF en utilisant l'imprimante et les paramètres de page par défaut.

```csharp
public static void PrintDocuments(params string[] filePaths)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| filePaths | String[] | Un tableau de chemins de fichiers représentant les documents PDF à imprimer. |

## Remarques

Cette méthode permet d'imprimer plusieurs documents PDF en une seule tâche d'impression. Assurez-vous que les chemins de fichiers fournis sont valides et accessibles.

## Exemples

```csharp
[C#]
var path1 = dataDir + "PrintDocument.pdf";
var path2 = dataDir + "Print-PageRange.pdf";
var path3 = dataDir + "35925_1_3.xps";

Aspose.Pdf.Facades.PdfViewer.PrintDocuments(path1, path2, path3);

[VisualBasic]
Dim path1 As String = dataDir & "PrintDocument.pdf"
Dim path2 As String = dataDir & "Print-PageRange.pdf"
Dim path3 As String = dataDir & "35925_1_3.xps"

Aspose.Pdf.Facades.PdfViewer.PrintDocuments(path1, path2, path3)
```

### Voir aussi

* class [PdfViewer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## PrintDocuments(params Stream[]) {#printdocuments_7}

Imprime plusieurs documents PDF à partir des flux fournis en utilisant l'imprimante et les paramètres de page par défaut.

```csharp
public static void PrintDocuments(params Stream[] documentStreams)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| documentStreams | Stream[] | Un tableau de flux contenant les documents PDF à imprimer. |

## Remarques

Cette méthode permet d'imprimer plusieurs documents PDF en une seule opération. Assurez-vous que les flux fournis sont valides et accessibles pendant le processus d'impression.

## Exemples

```csharp
[C#]
using (Stream stream1 = File.OpenRead(dataDir + "PrintDocument.pdf"),
              stream2 = File.OpenRead(dataDir + "Print-PageRange.pdf"),
              stream3 = File.OpenRead(dataDir + "35925_1_3.xps"))
{
    Aspose.Pdf.Facades.PdfViewer.PrintDocuments(stream1, stream2, stream3);
}

[VisualBasic]
Using stream1 As Stream = File.OpenRead(dataDir & "PrintDocument.pdf"),
      stream2 As Stream = File.OpenRead(dataDir & "Print-PageRange.pdf"),
      stream3 As Stream = File.OpenRead(dataDir & "35925_1_3.xps")
    Aspose.Pdf.Facades.PdfViewer.PrintDocuments(stream1, stream2, stream3)
End Using
```

### Voir aussi

* class [PdfViewer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## PrintDocuments(PrinterSettings, params Document[]) {#printdocuments_1}

Imprime plusieurs documents PDF en utilisant les paramètres d'imprimante spécifiés.

```csharp
public static void PrintDocuments(PrinterSettings printerSettings, params Document[] documents)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| printerSettings | PrinterSettings | L'objet [`PrinterSettings`](../../../aspose.pdf.printing/printersettings/) qui spécifie les paramètres d'imprimante à utiliser pour l'impression. |
| documents | Document[] | Un tableau d'objets [`Document`](../../../aspose.pdf/document/) représentant les documents PDF à imprimer. |

## Remarques

Cette méthode permet d'imprimer plusieurs documents PDF avec des paramètres d'imprimante personnalisés.

## Exemples

```csharp
[C#]
using (Aspose.Pdf.Document document1 = new Aspose.Pdf.Document(dataDir + "PrintDocument.pdf"),
                           document2 = new Aspose.Pdf.Document(dataDir + "Print-PageRange.pdf"),
                           document3 = new Aspose.Pdf.Document(dataDir + "35925_1_3.xps", new Aspose.Pdf.XpsLoadOptions()))
{
    var printDocument = new PrintDocument();
    Aspose.Pdf.Printing.PrinterSettings printerSettings = new Aspose.Pdf.Printing.PrinterSettings();
    printerSettings.PrinterName = printDocument.PrinterSettings.PrinterName;

    Aspose.Pdf.Facades.PdfViewer.PrintDocuments(printerSettings, document1, document2, document3);
}

[VisualBasic]
Using document1 As New Aspose.Pdf.Document(dataDir & "PrintDocument.pdf"),
      document2 As New Aspose.Pdf.Document(dataDir & "Print-PageRange.pdf"),
      document3 As New Aspose.Pdf.Document(dataDir & "35925_1_3.xps", New Aspose.Pdf.XpsLoadOptions())
     Dim printDocument As New PrintDocument()
     Dim printerSettings As New Aspose.Pdf.Printing.PrinterSettings()
     printerSettings.PrinterName = printDocument.PrinterSettings.PrinterName

     Aspose.Pdf.Facades.PdfViewer.PrintDocuments(printerSettings, document1, document2, document3)
End Using
```

### Voir aussi

* class [PrinterSettings](../../../aspose.pdf.printing/printersettings/)
* class [Document](../../../aspose.pdf/document/)
* class [PdfViewer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## PrintDocuments(PrinterSettings, params string[]) {#printdocuments_6}

Imprime plusieurs documents PDF en utilisant les paramètres d'imprimante spécifiés.

```csharp
public static void PrintDocuments(PrinterSettings printerSettings, params string[] filePaths)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| printerSettings | PrinterSettings | L'objet [`PrinterSettings`](../../../aspose.pdf.printing/printersettings/) contenant les détails de configuration de l'imprimante. |
| filePaths | String[] | Un tableau de chemins de fichiers représentant les documents PDF à imprimer. |

## Remarques

Cette méthode permet d'imprimer plusieurs documents PDF en une seule tâche d'impression. Assurez-vous que les chemins de fichiers fournis sont valides et accessibles.

## Exemples

```csharp
[C#]
var path1 = dataDir + "PrintDocument.pdf";
var path2 = dataDir + "Print-PageRange.pdf";
var path3 = dataDir + "35925_1_3.xps";

var printDocument = new PrintDocument();
Aspose.Pdf.Printing.PrinterSettings printerSettings = new Aspose.Pdf.Printing.PrinterSettings();
printerSettings.PrinterName = printDocument.PrinterSettings.PrinterName;

Aspose.Pdf.Facades.PdfViewer.PrintDocuments(printerSettings, path1, path2, path3);

[VisualBasic]
Dim path1 As String = dataDir & "PrintDocument.pdf"
Dim path2 As String = dataDir & "Print-PageRange.pdf"
Dim path3 As String = dataDir & "35925_1_3.xps"

Dim printDocument As New PrintDocument()
Dim printerSettings As New Aspose.Pdf.Printing.PrinterSettings()
printerSettings.PrinterName = printDocument.PrinterSettings.PrinterName

Aspose.Pdf.Facades.PdfViewer.PrintDocuments(printerSettings, path1, path2, path3)
```

### Voir aussi

* class [PrinterSettings](../../../aspose.pdf.printing/printersettings/)
* class [PdfViewer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## PrintDocuments(PrinterSettings, params Stream[]) {#printdocuments_5}

Imprime plusieurs documents PDF à partir des flux fournis en utilisant les paramètres d'imprimante spécifiés.

```csharp
public static void PrintDocuments(PrinterSettings printerSettings, params Stream[] documentStreams)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| printerSettings | PrinterSettings | Les paramètres d'imprimante à appliquer pendant le processus d'impression. |
| documentStreams | Stream[] | Un tableau de flux contenant les documents PDF à imprimer. |

## Remarques

Cette méthode permet d'imprimer plusieurs documents PDF en une seule opération. Assurez-vous que les flux fournis sont valides et accessibles pendant le processus d'impression.

## Exemples

```csharp
[C#]
using (Stream stream1 = File.OpenRead(dataDir + "PrintDocument.pdf"),
              stream2 = File.OpenRead(dataDir + "Print-PageRange.pdf"),
              stream3 = File.OpenRead(dataDir + "35925_1_3.xps"))
{
    var printDocument = new PrintDocument();
    Aspose.Pdf.Printing.PrinterSettings printerSettings = new Aspose.Pdf.Printing.PrinterSettings();
    printerSettings.PrinterName = printDocument.PrinterSettings.PrinterName;

    Aspose.Pdf.Facades.PdfViewer.PrintDocuments(printerSettings, stream1, stream2, stream3);
}

[VisualBasic]
Using stream1 As Stream = File.OpenRead(dataDir & "PrintDocument.pdf"),
      stream2 As Stream = File.OpenRead(dataDir & "Print-PageRange.pdf"),
      stream3 As Stream = File.OpenRead(dataDir & "35925_1_3.xps")
    Dim printDocument As New PrintDocument()
    Dim printerSettings As New Aspose.Pdf.Printing.PrinterSettings()
    printerSettings.PrinterName = printDocument.PrinterSettings.PrinterName

    Aspose.Pdf.Facades.PdfViewer.PrintDocuments(printerSettings, stream1, stream2, stream3)
End Using
```

### Voir aussi

* class [PrinterSettings](../../../aspose.pdf.printing/printersettings/)
* class [PdfViewer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## PrintDocuments(PrinterSettings, PageSettings, params Document[]) {#printdocuments_2}

Imprime plusieurs documents PDF en utilisant l'imprimante et les paramètres de page spécifiés.

```csharp
public static void PrintDocuments(PrinterSettings printerSettings, PageSettings pageSettings, 
    params Document[] documents)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| printerSettings | PrinterSettings | L'objet [`PrinterSettings`](../../../aspose.pdf.printing/printersettings/) qui spécifie les paramètres d'imprimante à utiliser pour l'impression. |
| pageSettings | PageSettings | L'objet [`PageSettings`](../../../aspose.pdf.printing/pagesettings/) qui spécifie les paramètres de page à utiliser pour l'impression. |
| documents | Document[] | Un tableau d'objets [`Document`](../../../aspose.pdf/document/) représentant les documents PDF à imprimer. |

## Remarques

Cette méthode permet d'imprimer plusieurs documents PDF avec des paramètres d'imprimante et de page personnalisés.

## Exemples

```csharp
[C#]
using (Aspose.Pdf.Document document1 = new Aspose.Pdf.Document(dataDir + "PrintDocument.pdf"),
                           document2 = new Aspose.Pdf.Document(dataDir + "Print-PageRange.pdf"),
                           document3 = new Aspose.Pdf.Document(dataDir + "35925_1_3.xps", new Aspose.Pdf.XpsLoadOptions()))
{
    var printDocument = new PrintDocument();
    Aspose.Pdf.Printing.PrinterSettings printerSettings = new Aspose.Pdf.Printing.PrinterSettings();
    printerSettings.PrinterName = printDocument.PrinterSettings.PrinterName;

    Aspose.Pdf.Printing.PageSettings pageSettings = new Aspose.Pdf.Printing.PageSettings();
    pageSettings.PaperSize = Aspose.Pdf.Printing.PaperSizes.A4;
    pageSettings.Margins = new Aspose.Pdf.Devices.Margins(0, 0, 0, 0);

    Aspose.Pdf.Facades.PdfViewer.PrintDocuments(printerSettings, pageSettings, document1, document2, document3);
}

[VisualBasic]
Using document1 As New Aspose.Pdf.Document(dataDir & "PrintDocument.pdf"),
      document2 As New Aspose.Pdf.Document(dataDir & "Print-PageRange.pdf"),
      document3 As New Aspose.Pdf.Document(dataDir & "35925_1_3.xps", New Aspose.Pdf.XpsLoadOptions())
     Dim printDocument As New PrintDocument()
     Dim printerSettings As New Aspose.Pdf.Printing.PrinterSettings()
     printerSettings.PrinterName = printDocument.PrinterSettings.PrinterName

     Dim pageSettings As New Aspose.Pdf.Printing.PageSettings()
     pageSettings.PaperSize = Aspose.Pdf.Printing.PaperSizes.A4
     pageSettings.Margins = New Aspose.Pdf.Devices.Margins(0, 0, 0, 0)

     Aspose.Pdf.Facades.PdfViewer.PrintDocuments(printerSettings, pageSettings, document1, document2, document3)
End Using
```

### Voir aussi

* class [PrinterSettings](../../../aspose.pdf.printing/printersettings/)
* class [PageSettings](../../../aspose.pdf.printing/pagesettings/)
* class [Document](../../../aspose.pdf/document/)
* class [PdfViewer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## PrintDocuments(PrinterSettings, PageSettings, params string[]) {#printdocuments_4}

Imprime plusieurs documents PDF en utilisant l'imprimante et les paramètres de page spécifiés.

```csharp
public static void PrintDocuments(PrinterSettings printerSettings, PageSettings pageSettings, 
    params string[] filePaths)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| printerSettings | PrinterSettings | L'objet [`PrinterSettings`](../../../aspose.pdf.printing/printersettings/) contenant les détails de configuration de l'imprimante. |
| pageSettings | PageSettings | L'objet [`PageSettings`](../../../aspose.pdf.printing/pagesettings/) spécifiant la mise en page et les paramètres de la page. |
| filePaths | String[] | Un tableau de chemins de fichiers représentant les documents PDF à imprimer. |

## Remarques

Cette méthode permet d'imprimer plusieurs documents PDF en une seule tâche d'impression. Assurez-vous que les chemins de fichiers fournis sont valides et accessibles.

## Exemples

```csharp
[C#]
var path1 = dataDir + "PrintDocument.pdf";
var path2 = dataDir + "Print-PageRange.pdf";
var path3 = dataDir + "35925_1_3.xps";

var printDocument = new PrintDocument();
Aspose.Pdf.Printing.PrinterSettings printerSettings = new Aspose.Pdf.Printing.PrinterSettings();
printerSettings.PrinterName = printDocument.PrinterSettings.PrinterName;

Aspose.Pdf.Printing.PageSettings pageSettings = new Aspose.Pdf.Printing.PageSettings();
pageSettings.PaperSize = Aspose.Pdf.Printing.PaperSizes.A4;
pageSettings.Margins = new Aspose.Pdf.Devices.Margins(0, 0, 0, 0);

Aspose.Pdf.Facades.PdfViewer.PrintDocuments(printerSettings, pageSettings, path1, path2, path3);

[VisualBasic]
Dim path1 As String = dataDir & "PrintDocument.pdf"
Dim path2 As String = dataDir & "Print-PageRange.pdf"
Dim path3 As String = dataDir & "35925_1_3.xps"

Dim printDocument As New PrintDocument()
Dim printerSettings As New Aspose.Pdf.Printing.PrinterSettings()
printerSettings.PrinterName = printDocument.PrinterSettings.PrinterName

Dim pageSettings As New Aspose.Pdf.Printing.PageSettings()
pageSettings.PaperSize = Aspose.Pdf.Printing.PaperSizes.A4
pageSettings.Margins = New Aspose.Pdf.Devices.Margins(0, 0, 0, 0)

Aspose.Pdf.Facades.PdfViewer.PrintDocuments(printerSettings, pageSettings, path1, path2, path3)
```

### Voir aussi

* class [PrinterSettings](../../../aspose.pdf.printing/printersettings/)
* class [PageSettings](../../../aspose.pdf.printing/pagesettings/)
* class [PdfViewer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## PrintDocuments(PrinterSettings, PageSettings, params Stream[]) {#printdocuments_3}

Imprime plusieurs documents PDF à partir des flux fournis en utilisant l'imprimante et les paramètres de page spécifiés.

```csharp
public static void PrintDocuments(PrinterSettings printerSettings, PageSettings pageSettings, 
    params Stream[] documentStreams)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| printerSettings | PrinterSettings | Les paramètres d'imprimante à appliquer pendant le processus d'impression. |
| pageSettings | PageSettings | Les paramètres de page à appliquer à chaque document lors de l'impression. |
| documentStreams | Stream[] | Un tableau de flux contenant les documents PDF à imprimer. |

## Remarques

Cette méthode permet d'imprimer plusieurs documents PDF en une seule opération. Assurez-vous que les flux fournis sont valides et accessibles pendant le processus d'impression.

## Exemples

```csharp
[C#]
using (Stream stream1 = File.OpenRead(dataDir + "PrintDocument.pdf"),
              stream2 = File.OpenRead(dataDir + "Print-PageRange.pdf"),
              stream3 = File.OpenRead(dataDir + "35925_1_3.xps"))
{
    var printDocument = new PrintDocument();
    Aspose.Pdf.Printing.PrinterSettings printerSettings = new Aspose.Pdf.Printing.PrinterSettings();
    printerSettings.PrinterName = printDocument.PrinterSettings.PrinterName;

    Aspose.Pdf.Printing.PageSettings pageSettings = new Aspose.Pdf.Printing.PageSettings();
    pageSettings.PaperSize = Aspose.Pdf.Printing.PaperSizes.A4;
    pageSettings.Margins = new Aspose.Pdf.Devices.Margins(0, 0, 0, 0);

    Aspose.Pdf.Facades.PdfViewer.PrintDocuments(printerSettings, pageSettings, stream1, stream2, stream3);
}

[VisualBasic]
Using stream1 As Stream = File.OpenRead(dataDir & "PrintDocument.pdf"),
      stream2 As Stream = File.OpenRead(dataDir & "Print-PageRange.pdf"),
      stream3 As Stream = File.OpenRead(dataDir & "35925_1_3.xps")
    Dim printDocument As New PrintDocument()
    Dim printerSettings As New Aspose.Pdf.Printing.PrinterSettings()
    printerSettings.PrinterName = printDocument.PrinterSettings.PrinterName

    Dim pageSettings As New Aspose.Pdf.Printing.PageSettings()
    pageSettings.PaperSize = Aspose.Pdf.Printing.PaperSizes.A4
    pageSettings.Margins = New Aspose.Pdf.Devices.Margins(0, 0, 0, 0)

    Aspose.Pdf.Facades.PdfViewer.PrintDocuments(printerSettings, pageSettings, stream1, stream2, stream3)
End Using
```

### Voir aussi

* class [PrinterSettings](../../../aspose.pdf.printing/printersettings/)
* class [PageSettings](../../../aspose.pdf.printing/pagesettings/)
* class [PdfViewer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


