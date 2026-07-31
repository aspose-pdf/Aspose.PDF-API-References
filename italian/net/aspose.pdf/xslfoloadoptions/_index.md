---
title: "Classe XslFoLoadOptions"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Classe Aspose.Pdf.XslFoLoadOptions. Rappresenta le opzioni per il caricamento/importazione di un file XSLFO in un documento PDF."
type: docs
weight: 11720
url: /it/net/aspose.pdf/xslfoloadoptions/
---
## XslFoLoadOptions class

Rappresenta le opzioni per il caricamento/importazione di file XSL-FO in un documento pdf.

```csharp
public sealed class XslFoLoadOptions : XmlLoadOptions
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [XslFoLoadOptions](xslfoloadoptions/#constructor)() | Crea l'oggetto `XslFoLoadOptions` senza dati xsl. |
| [XslFoLoadOptions](xslfoloadoptions/#constructor_1)(Stream) | Crea l'oggetto `XslFoLoadOptions` con dati xsl. |
| [XslFoLoadOptions](xslfoloadoptions/#constructor_2)(string) | Crea l'oggetto `XslFoLoadOptions` con dati xsl. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [BasePath](../../aspose.pdf/xslfoloadoptions/basepath/) { get; set; } | Il percorso/base URL da cui vengono cercati i percorsi relativi alle risorse esterne (se presenti) referenziate nel file SVG caricato. |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Ottiene o imposta il flag per disabilitare qualsiasi restrizione di licenza per tutti i font durante il caricamento del file. Quando `true`, consente di eseguire operazioni con font proibiti da una licenza di quel font, ad esempio consente di incorporare un font in un documento PDF anche se le regole di licenza disabilitano l'incorporamento per quel font. Per impostazione predefinita `false`. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Rappresenta il formato file descritto da [`LoadOptions`](../loadoptions/). |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Callback per gestire eventuali avvisi generati. Il WarningHandler restituisce l'elemento enum ReturnAction che specifica Continue o Abort. Continue è l'azione predefinita e l'operazione Load continua, tuttavia l'utente può anche restituire Abort, nel qual caso l'operazione Load deve cessare. |
| [XslStream](../../aspose.pdf/xmlloadoptions/xslstream/) { get; } | Ottiene i dati xsl per convertire xml in un documento pdf. |
| [XsltArgumentList](../../aspose.pdf/xslfoloadoptions/xsltargumentlist/) { get; set; } | XsltArgumentList per inserire valori nei parametri xls esistenti  Il file XLS ha il parametro 'animal' senza valore: XsltArgumentList args = new XsltArgumentList(); args.AddParam("animal", "", "cat"); ora il convertitore assume che esista un parametro 'animal' con valore 'cat' nel file XLS. |

## Campi

| Nome | Descrizione |
| --- | --- |
| [ParsingErrorsHandlingType](../../aspose.pdf/xslfoloadoptions/parsingerrorshandlingtype/) | Il documento XSLFO di origine può contenere errori di formattazione. Questo enum elenca le possibili strategie di gestione di tali errori. |

## Esempi

Il seguente esempio mostra come convertire un file XSL-FO in un file PDF.

```csharp
[C#]
// Il percorso della directory dei documenti.
string dataDir = @"YOUR_DATA_DIRECTORY";

// Il percorso al tuo file XSL-FO.
string xslFoFile = Path.Combine(dataDir, "XSLFO-to-PDF.xslfo");

// Il percorso del file PDF di output.
string pdfFile = Path.Combine(dataDir, "XSLFO-to-PDF.pdf");

// Inizializza XslFoLoadOptions	
XslFoLoadOptions xslFoLoadOptions = new XslFoLoadOptions();
    
using (Document pdfDocument = new Document(xslFoFile, xslFoLoadOptions))
{
 
    // Salva file PDF
    pdfDocument.Save(pdfFile);
}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your XSL-FO File.
    Dim xslFoFile = Path.Combine(dataDir, "XSLFO-to-PDF.xslfo")

    ' The path to output PDF File.
    Dim pdfFile = Path.Combine(dataDir, "XSLFO-to-PDF.pdf")
 
    ' Initialize XslFoLoadOptions  
    Dim xslFoLoadOptions As XslFoLoadOptions = New XslFoLoadOptions()
 
    Using pdfDocument As Document = New Document(xslFoFile, xslFoLoadOptions)
 
        ' Save PDF file
        pdfDocument.Save(pdfFile)
    End Using
```

### Vedi anche

* class [XmlLoadOptions](../xmlloadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


