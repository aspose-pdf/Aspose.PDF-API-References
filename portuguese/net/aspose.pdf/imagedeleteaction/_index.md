---
title: Enum ImageDeleteAction
second_title: Aspose.PDF for .NET API Reference
description: Enum Aspose.Pdf.ImageDeleteAction. Ação que é realizada com o objeto de imagem quando a imagem é removida da coleção. Se o objeto de imagem for removido
type: docs
weight: 5870
url: /pt/net/aspose.pdf/imagedeleteaction/
---
## Enumeração ImageDeleteAction

Ação que é realizada com o objeto de imagem quando a imagem é removida da coleção. Se o objeto de imagem for removido

```csharp
public enum ImageDeleteAction
```

### Valores

| Nome | Valor | Descrição |
| --- | --- | --- |
| KeepContents | `0` | A imagem será removida da coleção. Se o conteúdo da página contiver referências à imagem, elas não serão removidas. O documento pode se tornar inválido. |
| None | `1` | A imagem será removida da coleção e do conteúdo da página, mas o objeto de imagem não será excluído. O tamanho do arquivo não será reduzido. |
| ForceDelete | `2` | A imagem será removida da coleção e o objeto de imagem será removido do documento. Se outras referências ao mesmo objeto existirem, o documento pode ser corrompido. |
| Check | `3` | A imagem será removida da coleção e o objeto de imagem será removido apenas se não houver outras referências à imagem de outras páginas. Isso pode exigir mais tempo em comparação com a opção ForceDelete. |

### Veja Também

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)