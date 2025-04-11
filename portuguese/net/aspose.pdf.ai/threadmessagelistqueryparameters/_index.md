---
title: Class ThreadMessageListQueryParameters
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.ThreadMessageListQueryParameters class. Objeto de parâmetros de consulta para listar mensagens de thread
type: docs
weight: 1130
url: /pt/net/aspose.pdf.ai/threadmessagelistqueryparameters/
---
## ThreadMessageListQueryParameters class

Objeto de parâmetros de consulta para listar mensagens de thread.

```csharp
public class ThreadMessageListQueryParameters : BaseListQueryParameters, IQueryParameters
```

## Constructors

| Name | Description |
| --- | --- |
| [ThreadMessageListQueryParameters](threadmessagelistqueryparameters/)() | O construtor padrão. |

## Properties

| Name | Description |
| --- | --- |
| [After](../../aspose.pdf.ai/baselistqueryparameters/after/) { get; set; } | Obtém ou define um cursor para uso na paginação. after é um ID de objeto que define sua posição na lista. Por exemplo, se você fizer uma solicitação de lista e receber 100 objetos, terminando com obj_foo, sua chamada subsequente pode incluir after=obj_foo para buscar a próxima página da lista. |
| [Before](../../aspose.pdf.ai/baselistqueryparameters/before/) { get; set; } | Obtém ou define um cursor para uso na paginação. before é um ID de objeto que define sua posição na lista. Por exemplo, se você fizer uma solicitação de lista e receber 100 objetos, terminando com obj_foo, sua chamada subsequente pode incluir before=obj_foo para buscar a página anterior da lista. |
| [Limit](../../aspose.pdf.ai/baselistqueryparameters/limit/) { get; set; } | Obtém ou define um limite no número de objetos a serem retornados. Limit pode variar entre 1 e 100, e o padrão é 20. |
| [Order](../../aspose.pdf.ai/baselistqueryparameters/order/) { get; set; } | Obtém ou define a ordem de classificação pelo timestamp created_at dos objetos. asc para ordem crescente e desc para ordem decrescente. |
| [RunId](../../aspose.pdf.ai/threadmessagelistqueryparameters/runid/) { get; set; } | Filtra mensagens pelo ID da execução que as gerou. |

## Methods

| Name | Description |
| --- | --- |
| [GetQueryParameters](../../aspose.pdf.ai/threadmessagelistqueryparameters/getqueryparameters/)() | Obtém os parâmetros de consulta para listar mensagens de thread. |

### See Also

* class [BaseListQueryParameters](../baselistqueryparameters/)
* interface [IQueryParameters](../iqueryparameters/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)