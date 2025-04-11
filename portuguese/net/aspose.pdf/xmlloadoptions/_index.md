---
title: Class XmlLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.XmlLoadOptions. Representa opções para carregar/importar arquivo XML em documento pdf
type: docs
weight: 11390
url: /pt/net/aspose.pdf/xmlloadoptions/
---
## Classe XmlLoadOptions

Representa opções para carregar/importar arquivo XML em documento pdf.

```csharp
public class XmlLoadOptions : LoadOptions
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [XmlLoadOptions](xmlloadoptions/#constructor)() | Cria objeto `XmlLoadOptions` sem dados xsl. |
| [XmlLoadOptions](xmlloadoptions/#constructor_1)(Stream) | Cria objeto `XmlLoadOptions` com dados xsl. |
| [XmlLoadOptions](xmlloadoptions/#constructor_2)(string) | Cria objeto `XmlLoadOptions` com dados xsl. |

## Propriedades

| Nome | Descrição |
| --- | --- |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Obtém ou define a flag para desabilitar quaisquer restrições de licença para todas as fontes ao carregar o arquivo. Quando `true`, permite executar operações com fontes que são proibidas por uma licença dessa fonte, por exemplo, permite incorporar uma fonte em um documento PDF mesmo que as regras de licença desabilitem a incorporação para essa fonte. Por padrão `false`. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Representa o formato do arquivo que [`LoadOptions`](../loadoptions/) descreve. |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Callback para lidar com quaisquer avisos gerados. O WarningHandler retorna um item do enum ReturnAction especificando Continue ou Abort. Continue é a ação padrão e a operação de Load continua, no entanto, o usuário também pode retornar Abort, caso em que a operação de Load deve cessar. |
| [XslStream](../../aspose.pdf/xmlloadoptions/xslstream/) { get; } | Obtém dados xsl para converter xml em documento pdf. |

## Exemplos

O seguinte exemplo mostra como converter um arquivo XML em um arquivo PDF

```csharp
[C#]
	// The path to the documents directory.
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// The path to your XML File.
	string xmlFile = Path.Combine(dataDir, "XML-to-PDF.xml");

	// The path to output PDF File.
	string pdfFile = Path.Combine(dataDir, "XML-to-PDF.pdf");

	// Initialize XmlLoadOptions	
	XmlLoadOptions xmlLoadOptions = new XmlLoadOptions();
		
	using (Document pdfDocument = new Document(xmlFile, xmlLoadOptions))
	{
	 
		// Save XML file
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

### Veja Também

* classe [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)