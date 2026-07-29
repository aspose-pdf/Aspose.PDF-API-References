---
title: "HtmlSaveOptions.HtmlPageMarkupSavingStrategy"
linktitle: "HtmlSaveOptions.HtmlPageMarkupSavingStrategy"
second_title: "Referência da API Aspose.PDF para Java"
description: "O resultado da conversão pode conter uma ou várias páginas HTML (que também podem referenciar arquivos externos como imagens ou fontes). Você pode atribuir a esta propriedade um delegate criado a partir de."
type: docs
weight: 2110
url: /pt/java/com.aspose.pdf/htmlsaveoptions.htmlpagemarkupsavingstrategy/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Delegate com.aspose.ms.System.MulticastDelegate com.aspose.pdf.HtmlSaveOptions.HtmlPageMarkupSavingStrategy, com.aspose.ms.System.Delegate, com.aspose.ms.System.MulticastDelegate com.aspose.pdf.HtmlSaveOptions.HtmlPageMarkupSavingStrategy, com.aspose.ms.System.MulticastDelegate, com.aspose.pdf.HtmlSaveOptions.HtmlPageMarkupSavingStrategy

```
public abstract static class HtmlSaveOptions.HtmlPageMarkupSavingStrategy extends com.aspose.ms.System.MulticastDelegate
```

O resultado da conversão pode conter uma ou várias páginas HTML (que também podem referenciar arquivos externos como imagens ou fontes). Você pode atribuir a esta propriedade um delegate criado a partir de um método personalizado que implemente o processamento da página HTML obtida (HTML em si) que foi criada durante a conversão. Nesse caso, o processamento (como salvar em fluxo ou disco) pode ser feito nesse código personalizado. Nesse caso, todas as ações necessárias para salvar a marcação da página HTML devem ser realizadas no código do método fornecido, pois a gravação do resultado no código do conversor não será utilizada. Se o processamento para este ou aquele caso, por algum motivo, precisar ser feito pelo próprio código do conversor, e não no código personalizado, defina no código personalizado a bandeira 'CustomProcessingCancelled' da variável do parâmetro 'htmlSavingInfo': isso sinaliza ao conversor que todas as etapas necessárias para o processamento desse recurso devem ser realizadas no próprio conversor, da mesma forma como se não houvesse nenhum código de salvamento personalizado externo.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [HtmlPageMarkupSavingStrategy](#HtmlPageMarkupSavingStrategy--) |  |

## Métodos

| Método | Descrição |
| --- | --- |
| [beginInvoke](#beginInvoke-com.aspose.pdf.HtmlSaveOptions.HtmlPageMarkupSavingInfo-com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Método interno beginInvoke |
| [endInvoke](#endInvoke-com.aspose.ms.System.IAsyncResult-) | Método interno endInvoke |
| [invoke](#invoke-com.aspose.pdf.HtmlSaveOptions.HtmlPageMarkupSavingInfo-) | Método invocado |

### HtmlPageMarkupSavingStrategy {#HtmlPageMarkupSavingStrategy--}
```
public HtmlPageMarkupSavingStrategy()
```



### beginInvoke {#beginInvoke-com.aspose.pdf.HtmlSaveOptions.HtmlPageMarkupSavingInfo-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
Método interno beginInvoke

### endInvoke {#endInvoke-com.aspose.ms.System.IAsyncResult-}
Método interno endInvoke

### invoke {#invoke-com.aspose.pdf.HtmlSaveOptions.HtmlPageMarkupSavingInfo-}
Método invocado
