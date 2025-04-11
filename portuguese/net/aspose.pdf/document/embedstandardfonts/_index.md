---
title: Document.EmbedStandardFonts
second_title: Aspose.PDF for .NET API Reference
description: Propriedade do documento. Propriedade que declara que o documento deve incorporar todas as fontes padrão Type1 que têm a flag IsEmbedded definida como verdadeira. Todas as fontes PDF podem ser incorporadas ao documento simplesmente definindo a flag IsEmbedded como verdadeira, mas as fontes padrão Type1 do PDF são uma exceção a essa regra. A incorporação de fontes padrão Type1 requer muito tempo, então, para incorporar essas fontes, é necessário não apenas definir a flag IsEmbedded como verdadeira para a fonte especificada, mas também definir uma flag adicional no nível do documento - EmbedStandardFonts = true; Esta propriedade pode ser definida apenas uma vez para todas as fontes. Por padrão, falso.
type: docs
weight: 150
url: /pt/net/aspose.pdf/document/embedstandardfonts/
---
## Propriedade Document.EmbedStandardFonts

Propriedade que declara que o documento deve incorporar todas as fontes padrão Type1 que têm a flag IsEmbedded definida como verdadeira. Todas as fontes PDF podem ser incorporadas ao documento simplesmente definindo a flag IsEmbedded como verdadeira, mas as fontes padrão Type1 do PDF são uma exceção a essa regra. A incorporação de fontes padrão Type1 requer muito tempo, então, para incorporar essas fontes, é necessário não apenas definir a flag IsEmbedded como verdadeira para a fonte especificada, mas também definir uma flag adicional no nível do documento - EmbedStandardFonts = true; Esta propriedade pode ser definida apenas uma vez para todas as fontes. Por padrão, falso.

```csharp
public bool EmbedStandardFonts { get; set; }
```

### Veja Também

* classe [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)