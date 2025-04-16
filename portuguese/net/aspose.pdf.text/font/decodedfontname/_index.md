---
title: Font.DecodedFontName
second_title: Aspose.PDF for .NET API Reference
description: Propriedade da fonte. Às vezes, fontes PDF podem ter um nome de fonte específico. Este nome é o valor da propriedade da fonte PDF BaseFont e, às vezes, essa propriedade pode ser representada em forma hexadecimal. Se lermos esse nome diretamente, ele pode ser representado em uma forma não legível. Para obter uma forma legível, é necessário decodificar o nome da fonte de acordo com regras específicas para essa fonte. Esta propriedade retorna o nome da fonte decodificado, então use-a para casos em que você se depara com um [`FontName`](../fontname/) não legível. Se a propriedade [`FontName`](../fontname/) tiver uma forma legível, esta propriedade será a mesma que [`FontName`](../fontname/), então você pode usar esta propriedade para qualquer caso em que precise obter o nome da fonte em uma forma legível.
type: docs
weight: 20
url: /pt/net/aspose.pdf.text/font/decodedfontname/
---
## Propriedade Font.DecodedFontName

Às vezes, fontes PDF (geralmente fontes chinesas/japonesas/coreanas) podem ter um nome de fonte específico. Este nome é o valor da propriedade da fonte PDF "BaseFont" e, às vezes, essa propriedade pode ser representada em forma hexadecimal. Se lermos esse nome diretamente, ele pode ser representado em uma forma não legível. Para obter uma forma legível, é necessário decodificar o nome da fonte de acordo com regras específicas para essa fonte. Esta propriedade retorna o nome da fonte decodificado, então use-a para casos em que você se depara com um [`FontName`](../fontname/) não legível. Se a propriedade [`FontName`](../fontname/) tiver uma forma legível, esta propriedade será a mesma que [`FontName`](../fontname/), então você pode usar esta propriedade para qualquer caso em que precise obter o nome da fonte em uma forma legível.

```csharp
public string DecodedFontName { get; }
```

### Veja Também

* classe [Font](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)