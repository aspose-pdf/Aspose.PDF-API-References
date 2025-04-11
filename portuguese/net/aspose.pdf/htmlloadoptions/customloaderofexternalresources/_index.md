---
title: HtmlLoadOptions.CustomLoaderOfExternalResources
second_title: Aspose.PDF for .NET API Reference
description: Campo HtmlLoadOptions. Às vezes, é necessário evitar o uso do carregador interno de recursos externos, como imagens ou CSS, e fornecer um método personalizado que obterá os recursos solicitados de algum lugar. Por exemplo, durante o uso do Aspose.PDF na nuvem, o acesso direto aos arquivos referenciados é impossível; nesse caso, algum código personalizado colocado em um método especial deve ser usado, e o delegado que se refere a esse método deve ser atribuído a este atributo.
type: docs
weight: 100
url: /pt/net/aspose.pdf/htmlloadoptions/customloaderofexternalresources/
---
## Campo HtmlLoadOptions.CustomLoaderOfExternalResources

Às vezes, é necessário evitar o uso do carregador interno de recursos externos (como imagens ou CSS) e fornecer um método personalizado que obterá os recursos solicitados de algum lugar. Por exemplo, durante o uso do Aspose.PDF na nuvem, o acesso direto aos arquivos referenciados é impossível: nesse caso, algum código personalizado colocado em um método especial deve ser usado, e o delegado que se refere a esse método deve ser atribuído a este atributo.

```csharp
public ResourceLoadingStrategy CustomLoaderOfExternalResources;
```

### Veja Também

* delegado [ResourceLoadingStrategy](../../loadoptions.resourceloadingstrategy/)
* classe [HtmlLoadOptions](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)