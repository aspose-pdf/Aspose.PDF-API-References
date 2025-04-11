---
title: Font.DecodedFontName
second_title: Aspose.PDF for .NET API Reference
description: Propriété de police. Parfois, les polices PDF (généralement les polices chinoises/japonaises/coréennes) peuvent avoir un nom de police spécifique. Ce nom est la valeur de la propriété de police PDF BaseFont et parfois cette propriété peut être représentée sous forme hexadécimale. Si vous lisez ce nom directement, il peut être représenté sous une forme illisible. Pour obtenir une forme lisible, il est nécessaire de décoder le nom de la police selon des règles spécifiques à cette police. Cette propriété renvoie le nom de police décodé, donc utilisez-la dans les cas où vous rencontrez un [`FontName`](../fontname/) illisible. Si la propriété [`FontName`](../fontname/) a une forme lisible, cette propriété sera la même que [`FontName`](../fontname/), donc vous pouvez utiliser cette propriété dans tous les cas où vous devez obtenir le nom de la police sous une forme lisible.
type: docs
weight: 20
url: /fr/net/aspose.pdf.text/font/decodedfontname/
---
## Propriété Font.DecodedFontName

Parfois, les polices PDF (généralement les polices chinoises/japonaises/coréennes) peuvent avoir un nom de police spécifique. Ce nom est la valeur de la propriété de police PDF "BaseFont" et parfois cette propriété peut être représentée sous forme hexadécimale. Si vous lisez ce nom directement, il peut être représenté sous une forme illisible. Pour obtenir une forme lisible, il est nécessaire de décoder le nom de la police selon des règles spécifiques à cette police. Cette propriété renvoie le nom de police décodé, donc utilisez-la dans les cas où vous rencontrez un [`FontName`](../fontname/) illisible. Si la propriété [`FontName`](../fontname/) a une forme lisible, cette propriété sera la même que [`FontName`](../fontname/), donc vous pouvez utiliser cette propriété dans tous les cas où vous devez obtenir le nom de la police sous une forme lisible.

```csharp
public string DecodedFontName { get; }
```

### Voir aussi

* classe [Font](../)
* espace de noms [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)