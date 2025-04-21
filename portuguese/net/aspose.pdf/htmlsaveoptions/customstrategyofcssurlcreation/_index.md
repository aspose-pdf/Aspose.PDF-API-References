---
title: HtmlSaveOptions.CustomStrategyOfCssUrlCreation
second_title: Aspose.PDF for .NET API Reference
description: Campo HtmlSaveOptions. Este campo pode conter um método personalizado que retorna URL ou modelo de URL se a geração de várias páginas estiver ativada - veja os detalhes abaixo do assunto CSS como deve ser colocado no HTML gerado. Por exemplo, se você quiser que o conversor coloque uma URL específica em vez do nome padrão do arquivo CSS no CSS gerado, então você deve apenas criar e colocar neste método de propriedade que gera a URL desejada. Se a flag 'SplitCssIntoPages' estiver definida, então esta estratégia personalizada deve retornar não a URL exata do CSS, mas sim uma string de modelo que pode ser resolvida em URL para a URL do CSS desta ou daquela página.
type: docs
weight: 300
url: /pt/net/aspose.pdf/htmlsaveoptions/customstrategyofcssurlcreation/
---
## Campo HtmlSaveOptions.CustomStrategyOfCssUrlCreation

Este campo pode conter um método personalizado que retorna URL (ou modelo de URL se a geração de várias páginas estiver ativada - veja os detalhes abaixo) do CSS como deve ser colocado no HTML gerado. Por exemplo, se você quiser que o conversor coloque uma URL específica em vez do nome padrão do arquivo CSS no CSS gerado, então você deve apenas criar e colocar neste método de propriedade que gera a URL desejada. Se a flag 'SplitCssIntoPages' estiver definida, então esta estratégia personalizada (se houver) deve retornar não a URL exata do CSS, mas sim uma string de modelo que (após a substituição do espaço reservado pelo número da página com a função string.Format() dentro do conversor) pode ser resolvida em URL para a URL do CSS desta ou daquela página. Exemplos de string de retorno esperada nesse caso são: 'SomeTargetLocation-page_{0}.css','../PartHandlers/GetCss.aspx?DocumentId=45654&amp;CssPage={0}'

```csharp
public CssUrlMakingStrategy CustomStrategyOfCssUrlCreation;
```

### Veja Também

* delegate [CssUrlMakingStrategy](../../htmlsaveoptions.cssurlmakingstrategy/)
* class [HtmlSaveOptions](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)