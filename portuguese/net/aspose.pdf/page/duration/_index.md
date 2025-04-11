---
title: Page.Duration
second_title: Aspose.PDF for .NET API Reference
description: Propriedade da página. Obtém ou define a duração de exibição da página. Este é o tempo em segundos que a página deve ser exibida durante a apresentação. Retorna 1 se a duração não estiver definida
type: docs
weight: 110
url: /pt/net/aspose.pdf/page/duration/
---
## Propriedade Page.Duration

Obtém ou define a duração de exibição da página. Este é o tempo em segundos que a página deve ser exibida durante a apresentação. Retorna -1 se a duração não estiver definida.

```csharp
public double Duration { get; set; }
```

## Exemplos

O exemplo demonstra como obter a duração da página

```csharp
Document document = new Document("sample.pdf");
Page page = document.Pages[1];
int pageRect = page.Duration;
```

### Veja Também

* classe [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)