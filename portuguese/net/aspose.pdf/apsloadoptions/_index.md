---
title: Class ApsLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.ApsLoadOptions. A classe descreve opções de carregamento aps
type: docs
weight: 2750
url: /pt/net/aspose.pdf/apsloadoptions/
---
## Classe ApsLoadOptions

A classe descreve opções de carregamento aps.

```csharp
public class ApsLoadOptions : LoadOptions
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [ApsLoadOptions](apsloadoptions/)() | O construtor padrão. |

## Propriedades

| Nome | Descrição |
| --- | --- |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Obtém ou define a flag para desabilitar quaisquer restrições de licença para todas as fontes ao carregar o arquivo. Quando `true`, permite executar operações com fontes que são proibidas por uma licença dessa fonte, por exemplo, permite incorporar uma fonte em um documento PDF mesmo que as regras de licença desabilitem a incorporação para essa fonte. Por padrão `false`. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Representa o formato de arquivo que [`LoadOptions`](../loadoptions/) descreve. |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Callback para lidar com quaisquer avisos gerados. O WarningHandler retorna um item do enum ReturnAction especificando Continue ou Abort. Continue é a ação padrão e a operação de carregamento continua, no entanto, o usuário também pode retornar Abort, caso em que a operação de carregamento deve cessar. |

## Exemplos

O seguinte exemplo mostra como converter um arquivo APS para um arquivo PDF

```csharp
[C#]
	// The path to the documents directory.
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// The path to your APS File.
	string apsFile = Path.Combine(dataDir, "APS-to-PDF.aps");

	// The path to output PDF File.
	string pdfFile = Path.Combine(dataDir, "APS-to-PDF.pdf");

	// Initialize ApsLoadOptions  	
	ApsLoadOptions apsLoadOptions = new ApsLoadOptions();

	// Initialize Document wiht ApsLoadOptions     
	using (Document pdfDocument = new Document(apsFile, apsLoadOptions))
	{
	 
		// Save PDF file
		pdfDocument.Save(pdfFile);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"
	
    ' The path to your APS File.
    Dim apsFile = Path.Combine(dataDir, "APS-to-PDF.aps")
	
    ' The path to output PDF File.
    Dim pdfFile = Path.Combine(dataDir, "APS-to-PDF.pdf")
 
    ' Initialize ApsLoadOptions    
    Dim apsLoadOptions As ApsLoadOptions = New ApsLoadOptions()
 
	' Initialize Document wiht ApsLoadOptions
    Using pdfDocument As Document = New Document(apsFile, apsLoadOptions)
 
        ' Save PDF file
        pdfDocument.Save(pdfFile)
    End Using
```

### Veja Também

* classe [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)