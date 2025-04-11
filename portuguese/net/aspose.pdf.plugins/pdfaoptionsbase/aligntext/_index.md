---
title: PdfAOptionsBase.AlignText
second_title: Aspose.PDF for .NET API Reference
description: Propriedade PdfAOptionsBase. Obtém ou define um valor que indica se meios adicionais são necessários para preservar o alinhamento do texto durante o processo de conversão para PDF/A
type: docs
weight: 10
url: /pt/net/aspose.pdf.plugins/pdfaoptionsbase/aligntext/
---
## Propriedade PdfAOptionsBase.AlignText

Obtém ou define um valor que indica se meios adicionais são necessários para preservar o alinhamento do texto durante o processo de conversão para PDF/A.

```csharp
public bool AlignText { get; set; }
```

### Valor da Propriedade

`true` se o alinhamento do texto for alterado e ações adicionais forem necessárias para restaurá-lo; caso contrário, `false`.

## Observações

Quando definido como `true`, o processo de conversão tentará restaurar os limites do segmento de texto original. Para a maioria dos documentos, não há necessidade de alterar esta propriedade do valor padrão `false`, pois o alinhamento do texto não muda durante o processo de conversão padrão.

### Veja Também

* classe [PdfAOptionsBase](../)
* namespace [Aspose.Pdf.Plugins](../../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../../)