---
title: Enum DocSaveOptions.RecognitionMode
second_title: Aspose.PDF for .NET API Reference
description: Enumeração Aspose.Pdf.DocSaveOptionsRecognitionMode. Permite controlar como um documento PDF é convertido em um documento de processamento de texto
type: docs
weight: 3770
url: /pt/net/aspose.pdf/docsaveoptions.recognitionmode/
---
## Enumeração DocSaveOptions.RecognitionMode

Permite controlar como um documento PDF é convertido em um documento de processamento de texto.

```csharp
public enum RecognitionMode
```

### Valores

| Nome | Valor | Descrição |
| --- | --- | --- |
| Textbox | `0` | Este modo é rápido e bom para preservar ao máximo a aparência original do arquivo PDF, mas a editabilidade do documento resultante pode ser limitada. |
| Flow | `1` | Modo de reconhecimento completo, o mecanismo realiza agrupamento e análise em múltiplos níveis para restaurar a intenção original do autor do documento e produzir um documento maximamente editável. A desvantagem é que o documento de saída pode parecer diferente do arquivo PDF original. |
| EnhancedFlow | `2` | Um modo Flow alternativo que suporta o reconhecimento de tabelas. |

## Observações

Use o modo Textbox quando o documento resultante não for ser editado pesadamente posteriormente. Caixas de texto são fáceis de modificar quando não há muito a fazer.

Use o modo Flow quando o documento de saída precisar de mais edição. Parágrafos e linhas de texto no modo flow permitem fácil modificação do texto, mas objetos de formatação não suportados parecerão piores do que no modo Textbox.

### Veja Também

* classe [DocSaveOptions](../docsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)