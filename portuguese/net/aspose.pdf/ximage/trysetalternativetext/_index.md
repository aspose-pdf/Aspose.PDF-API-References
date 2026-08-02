---
title: "XImage.TrySetAlternativeText"
second_title: "Referência da API Aspose.PDF para .NET"
description: "Método XImage. Define o texto alternativo para um XImage na página"
type: docs
weight: 180
url: /pt/net/aspose.pdf/ximage/trysetalternativetext/
---
## XImage.TrySetAlternativeText method

Define o texto alternativo para um XImage na página.

```csharp
public bool TrySetAlternativeText(string alternativeText, Page page)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| alternativeText | String | O texto alternativo a ser especificado. |
| página | Página | Página onde o XImage está localizado. |

### Valor de retorno

Verdadeiro se alternativeText para XImage estiver definido. Falso se alternativeText para XImage não estiver definido.

## Observações

O método retorna falso nos seguintes casos: - O XImage não foi encontrado na página especificada. - O XImage aparece várias vezes na página com diferentes elementos estruturais, tornando ambíguo qual instância deve receber o texto alternativo.

### Veja Também

* class [Page](../../page/)
* class [XImage](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


