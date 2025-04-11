---
title: Page.Rect
second_title: Aspose.PDF for .NET API Reference
description: Propriedade da página. Obtém ou define o retângulo da página. Para obter, a caixa de recorte da página é retornada se especificada, caso contrário, a caixa de mídia da página é retornada. Para definir, a caixa de mídia da página é sempre definida. Por favor, note que esta propriedade não considera a rotação da página. Para obter o retângulo da página considerando a rotação, por favor, use ActualRect.
type: docs
weight: 230
url: /pt/net/aspose.pdf/page/rect/
---
## Propriedade Page.Rect

Obtém ou define o retângulo da página. Para obter: a caixa de recorte da página é retornada se especificada, caso contrário, a caixa de mídia da página é retornada. Para definir: a caixa de mídia da página é sempre definida. Por favor, note que esta propriedade não considera a rotação da página. Para obter o retângulo da página considerando a rotação, por favor, use ActualRect.

```csharp
public Rectangle Rect { get; set; }
```

## Exemplos

O exemplo demonstra como obter o retângulo da página:

```csharp
Document document = new Document("sample.pdf");
Page page = document.Pages[1];
Rectangle pageRect = page.Rect;
```

### Veja Também

* classe [Rectangle](../../rectangle/)
* classe [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)