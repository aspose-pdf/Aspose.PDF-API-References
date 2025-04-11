---
title: IFontOptions.NotifyAboutFontEmbeddingError
second_title: Aspose.PDF for .NET API Reference
description: Propriedade IFontOptions. Às vezes, não é possível incorporar a fonte desejada no documento. Existem muitas razões, por exemplo, restrições de licença ou quando a fonte desejada não foi encontrada no computador de destino. Quando essa situação ocorre, não é simples detectar, porque a fonte desejada é incorporada através do conjunto de propriedade flag Font.IsEmbedded = true; Claro que é possível ler essa propriedade imediatamente após ser definida, mas não é uma abordagem conveniente. A flag NotifyAboutFontEmbeddingError impõe um mecanismo de exceção para casos em que a tentativa de incorporar a fonte falhou. Se essa flag estiver definida, uma exceção do tipo [`FontEmbeddingException`](../../../aspose.pdf/fontembeddingexception/) será lançada. Por padrão, falso.
type: docs
weight: 10
url: /pt/net/aspose.pdf.text/ifontoptions/notifyaboutfontembeddingerror/
---
## Propriedade IFontOptions.NotifyAboutFontEmbeddingError

Às vezes, não é possível incorporar a fonte desejada no documento. Existem muitas razões, por exemplo, restrições de licença ou quando a fonte desejada não foi encontrada no computador de destino. Quando essa situação ocorre, não é simples detectar, porque a fonte desejada é incorporada através do conjunto de propriedade flag Font.IsEmbedded = true; Claro que é possível ler essa propriedade imediatamente após ser definida, mas não é uma abordagem conveniente. A flag NotifyAboutFontEmbeddingError impõe um mecanismo de exceção para casos em que a tentativa de incorporar a fonte falhou. Se essa flag estiver definida, uma exceção do tipo [`FontEmbeddingException`](../../../aspose.pdf/fontembeddingexception/) será lançada. Por padrão, falso.

```csharp
public bool NotifyAboutFontEmbeddingError { get; set; }
```

### Veja Também

* interface [IFontOptions](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)