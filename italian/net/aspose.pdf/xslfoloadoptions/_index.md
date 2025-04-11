---
title: Class XslFoLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.XslFoLoadOptions class. Rappresenta le opzioni per il caricamento/importo del file XSLFO in un documento PDF.
type: docs
weight: 11530
url: /it/net/aspose.pdf/xslfoloadoptions/
---
## Classe XslFoLoadOptions

Rappresenta le opzioni per il caricamento/importazione di un file XSL-FO in un documento pdf.

```csharp
public sealed class XslFoLoadOptions : XmlLoadOptions
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [XslFoLoadOptions](xslfoloadoptions/#constructor)() | Crea un oggetto `XslFoLoadOptions` senza dati xsl. |
| [XslFoLoadOptions](xslfoloadoptions/#constructor_1)(Stream) | Crea un oggetto `XslFoLoadOptions` con dati xsl. |
| [XslFoLoadOptions](xslfoloadoptions/#constructor_2)(string) | Crea un oggetto `XslFoLoadOptions` con dati xsl. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [BasePath](../../aspose.pdf/xslfoloadoptions/basepath/) { get; set; } | Il percorso/url di base da cui vengono cercati i percorsi relativi alle risorse esterne (se presenti) referenziate nel file SVG caricato. |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Ottiene o imposta un flag per disabilitare eventuali restrizioni di licenza per tutti i caratteri durante il caricamento del file. Quando `true`, consente di eseguire operazioni con caratteri che sono vietate da una licenza di questo carattere, ad esempio consente di incorporare un carattere in un documento PDF anche se le regole di licenza disabilitano l'incorporamento per questo carattere. Per impostazione predefinita `false`. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Rappresenta il formato del file che descrive [`LoadOptions`](../loadoptions/). |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Callback per gestire eventuali avvisi generati. Il WarningHandler restituisce un elemento dell'enumerazione ReturnAction che specifica se Continuare o Abortire. Continuare è l'azione predefinita e l'operazione di caricamento continua, tuttavia l'utente può anche restituire Abortire, nel qual caso l'operazione di caricamento dovrebbe cessare. |
| [XslStream](../../aspose.pdf/xmlloadoptions/xslstream/) { get; } | Ottiene i dati xsl per convertire xml in documento pdf. |
| [XsltArgumentList](../../aspose.pdf/xslfoloadoptions/xsltargumentlist/) { get; set; } | XsltArgumentList per inserire valori nei parametri xls esistenti. Il file XLS ha il parametro 'animal' senza valore: XsltArgumentList args = new XsltArgumentList(); args.AddParam("animal", "", "cat"); ora il convertitore presume che ci sia un parametro 'animal' con il valore 'cat' nel file XLS. |

## Campi

| Nome | Descrizione |
| --- | --- |
| [ParsingErrorsHandlingType](../../aspose.pdf/xslfoloadoptions/parsingerrorshandlingtype/) | Il documento XSLFO sorgente può contenere errori di formattazione. Questa enumerazione enumera le possibili strategie di gestione di tali errori. |

## Esempi

Il seguente esempio mostra come convertire un file XSL-FO in un file PDF

```csharp
[C#]
// The path to the documents directory.
string dataDir = @"YOUR_DATA_DIRECTORY";

// The path to your XSL-FO File.
string xslFoFile = Path.Combine(dataDir, "XSLFO-to-PDF.xslfo");

// The path to output PDF File.
string pdfFile = Path.Combine(dataDir, "XSLFO-to-PDF.pdf");

// Initialize XslFoLoadOptions	
XslFoLoadOptions xslFoLoadOptions = new XslFoLoadOptions();
    
using (Document pdfDocument = new Document(xslFoFile, xslFoLoadOptions))
{
 
    // Save PDF file
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

### Vedi Anche

* classe [XmlLoadOptions](../xmlloadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)