---
title: Delegate LoadOptions.ResourceLoadingStrategy
second_title: Aspose.PDF for .NET API Reference
description: Às vezes, é necessário evitar o uso do carregador interno de recursos externos, como imagens ou CSS, e fornecer um método personalizado que obterá os recursos solicitados de algum lugar. Por exemplo, durante o uso do Aspose.Pdf na nuvem, o acesso direto aos arquivos referenciados é impossível, e algum código personalizado colocado em um método especial deve ser usado. Este delegate define a assinatura de tal método personalizado.
type: docs
weight: 6160
url: /pt/net/aspose.pdf/loadoptions.resourceloadingstrategy/
---
## Delegate LoadOptions.ResourceLoadingStrategy

Às vezes, é necessário evitar o uso do carregador interno de recursos externos (como imagens ou CSS) e fornecer um método personalizado que obterá os recursos solicitados de algum lugar. Por exemplo, durante o uso do Aspose.Pdf na nuvem, o acesso direto aos arquivos referenciados é impossível, e algum código personalizado colocado em um método especial deve ser usado. Este delegate define a assinatura de tal método personalizado.

```csharp
public delegate ResourceLoadingResult ResourceLoadingStrategy(string resourceURI);
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| resourceURI | String | URI do recurso. |

### Valor de Retorno

Objeto ResourceLoadingResult.

### Veja Também

* classe [ResourceLoadingResult](../loadoptions.resourceloadingresult/)
* classe [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)