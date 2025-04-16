---
title: UnifiedSaveOptions.TryMergeAdjacentSameBackgroundImages
second_title: Aspose.PDF for .NET API Reference
description: Campo UnifiedSaveOptions. Às vezes, PDFs contêm imagens de fundo de páginas ou células de tabela construídas a partir de várias imagens de fundo de azulejos iguais colocadas uma perto da outra. Nesse caso, os renderizadores dos formatos de destino, por exemplo, MsWord para o formato DOCS, às vezes geram limites visíveis entre partes das imagens de fundo, pois suas técnicas de suavização de bordas de imagem são diferentes do Acrobat Reader. Se parecer que o documento exportado contém esses limites visíveis entre partes das mesmas imagens de fundo, tente usar esta configuração para se livrar desse efeito indesejado. ATENÇÃO! Essa otimização de qualidade geralmente desacelera essencialmente a conversão, portanto, use esta opção apenas quando for realmente necessário.
type: docs
weight: 40
url: /pt/net/aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/
---
## UnifiedSaveOptions.TryMergeAdjacentSameBackgroundImages field

Às vezes, PDFs contêm imagens de fundo (de páginas ou células de tabela) construídas a partir de várias imagens de fundo de azulejos iguais colocadas uma perto da outra. Nesse caso, os renderizadores dos formatos de destino (por exemplo, MsWord para o formato DOCS) às vezes geram limites visíveis entre partes das imagens de fundo, pois suas técnicas de suavização de bordas de imagem (anti-aliasing) são diferentes do Acrobat Reader. Se parecer que o documento exportado contém esses limites visíveis entre partes das mesmas imagens de fundo, tente usar esta configuração para se livrar desse efeito indesejado. ATENÇÃO! Essa otimização de qualidade geralmente desacelera essencialmente a conversão, portanto, use esta opção apenas quando for realmente necessário.

```csharp
public bool TryMergeAdjacentSameBackgroundImages;
```

### See Also

* class [UnifiedSaveOptions](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)