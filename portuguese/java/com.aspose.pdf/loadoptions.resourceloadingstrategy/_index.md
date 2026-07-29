---
title: "LoadOptions.ResourceLoadingStrategy"
linktitle: "LoadOptions.ResourceLoadingStrategy"
second_title: "Referência da API Aspose.PDF para Java"
description: "Às vezes é necessário evitar o uso do carregador interno de recursos externos (como imagens ou CSS) e fornecer um método personalizado, que obterá os recursos solicitados de algum lugar."
type: docs
weight: 2830
url: /pt/java/com.aspose.pdf/loadoptions.resourceloadingstrategy/
---
```
public static interface LoadOptions.ResourceLoadingStrategy
```

Às vezes é necessário evitar o uso do carregador interno de recursos externos (como imagens ou CSS) e fornecer um método personalizado, que obterá os recursos solicitados de algum lugar. Por exemplo, durante o uso do Aspose.PDf na nuvem, o acesso direto aos arquivos referenciados é impossível, e algum código personalizado colocado em um método especial deve ser usado. Este delegate define a assinatura de tal método personalizado.

## Métodos

| Método | Descrição |
| --- | --- |
| [invoke](#invoke-java.lang.String-) |  |

### invoke {#invoke-java.lang.String-}
