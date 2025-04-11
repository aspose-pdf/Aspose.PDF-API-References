---
title: Class PdfSaveOptions
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.PdfSaveOptions. Opções de salvamento para exportação para o formato Pdf
type: docs
weight: 8430
url: /pt/net/aspose.pdf/pdfsaveoptions/
---
## Classe PdfSaveOptions

Opções de salvamento para exportação para o formato Pdf

```csharp
public class PdfSaveOptions : SaveOptions
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [PdfSaveOptions](pdfsaveoptions/)() | O construtor padrão. |

## Propriedades

| Nome | Descrição |
| --- | --- |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | Obtém ou define um valor booleano que indica se os glifos da fonte serão armazenados em cache enquanto as páginas aps estão sendo preparadas. Melhora o desempenho da conversão de pdf para outros formatos, mas aumenta o consumo de memória. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | Obtém ou define um valor booleano que indica se o objeto Response será fechado após o documento ser salvo na resposta. |
| [DefaultFontName](../../aspose.pdf/pdfsaveoptions/defaultfontname/) { get; set; } | Nome da fonte usado por padrão para fontes que estão ausentes no computador. Quando o documento PDF que está sendo salvo contém fontes que não estão disponíveis no próprio documento e no dispositivo, a API substitui essas fontes pela fonte padrão (se uma fonte com [`DefaultFontName`](./defaultfontname/) for encontrada no dispositivo) |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | Formato de salvamento dos dados. |
| [TempPath](../../aspose.pdf/pdfsaveoptions/temppath/) { get; set; } | Caminho para arquivos temporários. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | Callback para lidar com quaisquer avisos gerados. O WarningHandler retorna um item do enum ReturnAction especificando Continue ou Abort. Continue é a ação padrão e a operação de salvamento continua, no entanto, o usuário também pode retornar Abort, caso em que a operação de salvamento deve cessar. |

## Exemplos

O seguinte exemplo mostra como definir o nome da fonte padrão ao salvar PDF

```csharp
[C#]
	// The path to the documents directory.
	string dataDir = "YOUR_DATA_DIRECTORY";

	// Load an existing PDF document with missing font
	string documentName = dataDir + "input.pdf";
	string fontName = "Arial";
	using (System.IO.FileStream fs = new System.IO.FileStream(documentName, System.IO.FileMode.Open))
	using (Document document = new Document(fs))
	{
		PdfSaveOptions pdfSaveOptions = new PdfSaveOptions();

		// Specify Default Font Name
		pdfSaveOptions.DefaultFontName = fontName;
		document.Save(dataDir + "output_out.pdf", pdfSaveOptions);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' Load an existing PDF document with missing font
    Dim documentName = dataDir & "input.pdf"
    Dim fontName = "Arial"
 
    Using fs As FileStream = New FileStream(documentName, FileMode.Open)
 
        Using document As Document = New Document(fs)
            Dim pdfSaveOptions As PdfSaveOptions = New PdfSaveOptions()

            ' Specify Default Font Name
            pdfSaveOptions.DefaultFontName = fontName
            document.Save(dataDir & "output_out.pdf", pdfSaveOptions)
        End Using
    End Using
```

### Veja Também

* classe [SaveOptions](../saveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)