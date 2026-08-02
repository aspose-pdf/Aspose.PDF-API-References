---
title: "Classe OcrDetail"
second_title: "Referência da API Aspose.PDF para .NET"
description: "classe Aspose.Pdf.AI.OcrDetail. Representa o resultado OCR para uma única page de um document ou um único arquivo de imagem"
type: docs
weight: 860
url: /pt/net/aspose.pdf.ai/ocrdetail/
---
## OcrDetail class

Representa o resultado OCR para uma única page de um document ou um único arquivo de imagem.

```csharp
public class OcrDetail : IComparable<OcrDetail>
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [OcrDetail](ocrdetail/)() | O construtor padrão. |

## Propriedades

| Nome | Descrição |
| --- | --- |
| [ErrorMessage](../../aspose.pdf.ai/ocrdetail/errormessage/) { get; set; } | Uma mensagem de erro descrevendo por que o OCR falhou nesta page, se Success for false. Null caso contrário. |
| [ExtractedText](../../aspose.pdf.ai/ocrdetail/extractedtext/) { get; set; } | O conteúdo de texto extraído da page. Null se Success for false ou nenhum texto for encontrado. |
| [PageNumber](../../aspose.pdf.ai/ocrdetail/pagenumber/) { get; set; } | O número da página baseado em 1 dentro do documento de origem. Para imagens de página única, isso será sempre 1. |
| [Success](../../aspose.pdf.ai/ocrdetail/success/) { get; set; } | Indica se a extração de OCR para esta página específica foi bem-sucedida. |
| [Usage](../../aspose.pdf.ai/ocrdetail/usage/) { get; set; } | Obtém ou define as estatísticas de uso. |

## Métodos

| Nome | Descrição |
| --- | --- |
| [CompareTo](../../aspose.pdf.ai/ocrdetail/compareto/)(OcrDetail) | Compara a instância atual de OcrDetail com outro objeto OcrDetail com base na propriedade PageNumber deles. |

### Veja Também

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


