---
title: Class XslFoLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.XslFoLoadOptions. Representa opções para carregar/importar arquivo XSLFO em documento pdf
type: docs
weight: 11530
url: /pt/net/aspose.pdf/xslfoloadoptions/
---
## Classe XslFoLoadOptions

Representa opções para carregar/importar arquivo XSL-FO em documento pdf.

```csharp
public sealed class XslFoLoadOptions : XmlLoadOptions
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [XslFoLoadOptions](xslfoloadoptions/#constructor)() | Cria objeto `XslFoLoadOptions` sem dados xsl. |
| [XslFoLoadOptions](xslfoloadoptions/#constructor_1)(Stream) | Cria objeto `XslFoLoadOptions` com dados xsl. |
| [XslFoLoadOptions](xslfoloadoptions/#constructor_2)(string) | Cria objeto `XslFoLoadOptions` com dados xsl. |

## Propriedades

| Nome | Descrição |
| --- | --- |
| [BasePath](../../aspose.pdf/xslfoloadoptions/basepath/) { get; set; } | O caminho/url base a partir do qual são pesquisados caminhos relativos para recursos externos (se houver) referenciados no arquivo SVG carregado. |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Obtém ou define a flag para desabilitar quaisquer restrições de licença para todas as fontes ao carregar o arquivo. Quando `true`, permite executar operações com fontes que são proibidas por uma licença dessa fonte, por exemplo, permite incorporar uma fonte em um documento PDF mesmo que as regras de licença desabilitem a incorporação para essa fonte. Por padrão `false`. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Representa o formato de arquivo que [`LoadOptions`](../loadoptions/) descreve. |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Callback para lidar com quaisquer avisos gerados. O WarningHandler retorna um item do enum ReturnAction especificando Continue ou Abort. Continue é a ação padrão e a operação de carregamento continua, no entanto, o usuário também pode retornar Abort, caso em que a operação de carregamento deve cessar. |
| [XslStream](../../aspose.pdf/xmlloadoptions/xslstream/) { get; } | Obtém dados xsl para converter xml em documento pdf. |
| [XsltArgumentList](../../aspose.pdf/xslfoloadoptions/xsltargumentlist/) { get; set; } | XsltArgumentList para inserir valores em parâmetros xls existentes. O arquivo XLS tem o parâmetro 'animal' sem valor: XsltArgumentList args = new XsltArgumentList(); args.AddParam("animal", "", "cat"); agora o conversor assume que há um parâmetro 'animal' com o valor 'cat' no arquivo XLS. |

## Campos

| Nome | Descrição |
| --- | --- |
| [ParsingErrorsHandlingType](../../aspose.pdf/xslfoloadoptions/parsingerrorshandlingtype/) | O documento XSLFO de origem pode conter erros de formatação. Este enum enumera as possíveis estratégias de tratamento desses erros. |

## Exemplos

O seguinte exemplo mostra como converter um arquivo XSL-FO em um arquivo PDF.

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

### Veja Também

* classe [XmlLoadOptions](../xmlloadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)