---
title: "Classe TextRecognitionResult"
second_title: "Referência da API Aspose.PDF para .NET"
description: "Classe Aspose.Pdf.AI.TextRecognitionResult. Representa os resultados agregados de OCR para um único Document de origem"
type: docs
weight: 1180
url: /pt/net/aspose.pdf.ai/textrecognitionresult/
---
## TextRecognitionResult class

Representa os resultados agregados de OCR para um único Document de origem.

```csharp
public class TextRecognitionResult
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [TextRecognitionResult](textrecognitionresult/)() | O construtor padrão. |

## Propriedades

| Nome | Descrição |
| --- | --- |
| [OcrDetails](../../aspose.pdf.ai/textrecognitionresult/ocrdetails/) { get; set; } | Uma lista contendo os resultados detalhados de OCR para cada Page do Document. Para arquivos de imagem única, essa lista normalmente conterá uma entrada OcrDetail com PageNumber = 1. |
| [OverallSuccess](../../aspose.pdf.ai/textrecognitionresult/overallsuccess/) { get; set; } | Indica se o OCR foi bem-sucedido para TODAS as Pages dentro deste Document. Falso se algum OcrDetail em OcrDetails tiver Success = false. |
| [SourceIdentifier](../../aspose.pdf.ai/textrecognitionresult/sourceidentifier/) { get; set; } | Identificador para o arquivo de origem (por exemplo, o caminho completo ou um nome único). |
| [SummaryErrorMessage](../../aspose.pdf.ai/textrecognitionresult/summaryerrormessage/) { get; set; } | Uma mensagem de erro consolidada se OverallSuccess for false, ou um resumo se alguma página falhar. Nulo se OverallSuccess for true. |
| [TotalUsage](../../aspose.pdf.ai/textrecognitionresult/totalusage/) { get; set; } | Obtém ou define as estatísticas totais de uso para o processamento deste Document (todas as Pages). |

### Veja Também

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


