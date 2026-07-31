---
title: "Classe XmlLoadOptions"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "classe Aspose.Pdf.XmlLoadOptions. Rappresenta le opzioni per il caricamento/importazione del file XML in un documento pdf"
type: docs
weight: 11580
url: /it/net/aspose.pdf/xmlloadoptions/
---
## XmlLoadOptions class

Rappresenta le opzioni per il caricamento/importazione di file XML in un documento pdf.

```csharp
public class XmlLoadOptions : LoadOptions
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [XmlLoadOptions](xmlloadoptions/#constructor)() | Crea l'oggetto `XmlLoadOptions` senza dati xsl. |
| [XmlLoadOptions](xmlloadoptions/#constructor_1)(Stream) | Crea l'oggetto `XmlLoadOptions` con dati xsl. |
| [XmlLoadOptions](xmlloadoptions/#constructor_2)(string) | Crea l'oggetto `XmlLoadOptions` con dati xsl. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Ottiene o imposta il flag per disabilitare qualsiasi restrizione di licenza per tutti i font durante il caricamento del file. Quando `true`, consente di eseguire operazioni con font proibiti da una licenza di quel font, ad esempio consente di incorporare un font in un documento PDF anche se le regole di licenza disabilitano l'incorporamento per quel font. Per impostazione predefinita `false`. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Rappresenta il formato file descritto da [`LoadOptions`](../loadoptions/). |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Callback per gestire eventuali avvisi generati. Il WarningHandler restituisce l'elemento enum ReturnAction che specifica Continue o Abort. Continue è l'azione predefinita e l'operazione Load continua, tuttavia l'utente può anche restituire Abort, nel qual caso l'operazione Load deve cessare. |
| [XslStream](../../aspose.pdf/xmlloadoptions/xslstream/) { get; } | Ottiene i dati xsl per convertire xml in un documento pdf. |

## Esempi

Il seguente esempio mostra come convertire un file XML in un file PDF

```csharp
[C#]
	// Il percorso della directory dei documenti.
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// Il percorso al tuo file XML.
	string xmlFile = Path.Combine(dataDir, "XML-to-PDF.xml");

	// Il percorso del file PDF di output.
	string pdfFile = Path.Combine(dataDir, "XML-to-PDF.pdf");

	// Inizializza XmlLoadOptions	
	XmlLoadOptions xmlLoadOptions = new XmlLoadOptions();
		
	using (Document pdfDocument = new Document(xmlFile, xmlLoadOptions))
	{
	 
		// Salva il file XML
		pdfDocument.Save(pdfFile);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your XML File.
    Dim xmlFile = Path.Combine(dataDir, "XML-to-PDF.xml")

    ' The path to output PDF File.
    Dim pdfFile = Path.Combine(dataDir, "XML-to-PDF.pdf")
 
    ' Initialize XmlLoadOptions
    Dim xmlLoadOptions As XmlLoadOptions = New XmlLoadOptions()
 
    Using pdfDocument As Document = New Document(xmlFile, xmlLoadOptions)
 
        ' Save PDF file
        pdfDocument.Save(pdfFile)
    End Using
```

### Vedi anche

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


