---
title: Interface IFontOptions
second_title: Aspose.PDF for .NET API Reference
description: Interface Aspose.Pdf.Text.IFontOptions. Propriedades úteis para ajustar o comportamento da fonte
type: docs
weight: 10610
url: /pt/net/aspose.pdf.text/ifontoptions/
---
## Interface IFontOptions

Propriedades úteis para ajustar o comportamento da fonte

```csharp
public interface IFontOptions
```

## Propriedades

| Nome | Descrição |
| --- | --- |
| [NotifyAboutFontEmbeddingError](../../aspose.pdf.text/ifontoptions/notifyaboutfontembeddingerror/) { get; set; } | Às vezes, não é possível incorporar a fonte desejada no documento. Existem muitas razões, por exemplo, restrições de licença ou quando a fonte desejada não foi encontrada no computador de destino. Quando essa situação ocorre, não é simples detectar, porque a fonte desejada é incorporada através do conjunto de propriedades com a flag Font.IsEmbedded = true; Claro que é possível ler essa propriedade imediatamente após ser definida, mas não é uma abordagem conveniente. A flag NotifyAboutFontEmbeddingError impõe um mecanismo de exceção para os casos em que a tentativa de incorporar a fonte falhou. Se essa flag estiver definida, uma exceção do tipo [`FontEmbeddingException`](../../aspose.pdf/fontembeddingexception/) será lançada. Por padrão, falso. |

### Veja Também

* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)