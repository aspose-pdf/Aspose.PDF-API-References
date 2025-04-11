---
title: Enum EpubSaveOptions.RecognitionMode
second_title: Aspose.PDF for .NET API Reference
description: Enum Aspose.Pdf.EpubSaveOptionsRecognitionMode. Quando um arquivo PDF que geralmente tem layout fixo está sendo convertido, o mecanismo de conversão tenta realizar agrupamento e análise multilevel para restaurar a intenção original do autor do documento e produzir o resultado em layout fluido. Esta propriedade ajusta essa conversão para este ou aquele método desejável de reconhecimento de conteúdo.
type: docs
weight: 4070
url: /pt/net/aspose.pdf/epubsaveoptions.recognitionmode/
---
## Enumeração EpubSaveOptions.RecognitionMode

Quando um arquivo PDF (que geralmente tem layout fixo) está sendo convertido, o mecanismo de conversão tenta realizar agrupamento e análise multilevel para restaurar a intenção original do autor do documento e produzir o resultado em layout fluido. Esta propriedade ajusta essa conversão para este ou aquele método desejável de reconhecimento de conteúdo.

```csharp
public enum RecognitionMode
```

### Valores

| Nome | Valor | Descrição |
| --- | --- | --- |
| Flow | `0` | Modo de reconhecimento completo, o mecanismo tenta realizar agrupamento e análise multilevel para restaurar a intenção original do autor do documento e produzir xhtml em layout fluido. |
| PdfFlow | `1` | A ideia principal desta conversão é baseada em salvar a ordem "natural" de renderização do conteúdo que é formada durante o processamento de documentos pdf. Nos casos gerais, os documentos pdf mantêm a ordem de renderização de cima para baixo, da esquerda para a direita (veja as direções em directions.png). Esta suposição permite criar um algoritmo de caminho único que transformará elementos Aps que têm posições (layout fixo) em formatos fluídos como HTML, EPUB, DOC. Este modo será especialmente útil para converter de PDF(APS) para EPUB, porque o formato EPUB foi desenvolvido para e-readers como o Kindle ou smartphones. O tamanho da tela desses dispositivos geralmente é menor do que o tamanho da tela de um PC comum. Portanto, o conteúdo dos documentos EPUB é melhor salvo no formato fluido, para renderização correta em telas de diferentes tamanhos. Neste modo, cada coluna será adicionada ao final da coluna anterior, permitindo manter a estrutura lógica do documento transformado durante a "paginação" em leitores EPUB. Essa conquista permite renderizar corretamente artigos científicos ou de revistas. |
| Fixed | `2` | Este modo é rápido e bom para preservar ao máximo a aparência original das páginas, mas, infelizmente, muitos leitores EPUB não suportam xhtml com layout fixo |

### Veja Também

* classe [EpubSaveOptions](../epubsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)