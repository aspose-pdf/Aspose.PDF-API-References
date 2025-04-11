---
title: Class RunListQueryParameters
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.AI.RunListQueryParameters. Objeto de parâmetros de consulta para listar execuções
type: docs
weight: 990
url: /pt/net/aspose.pdf.ai/runlistqueryparameters/
---
## Classe RunListQueryParameters

Objeto de parâmetros de consulta para listar execuções.

```csharp
public class RunListQueryParameters : BaseListQueryParameters, IQueryParameters
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [RunListQueryParameters](runlistqueryparameters/)() | O construtor padrão. |

## Propriedades

| Nome | Descrição |
| --- | --- |
| [After](../../aspose.pdf.ai/baselistqueryparameters/after/) { get; set; } | Obtém ou define um cursor para uso na paginação. after é um ID de objeto que define seu lugar na lista. Por exemplo, se você fizer uma solicitação de lista e receber 100 objetos, terminando com obj_foo, sua chamada subsequente pode incluir after=obj_foo para buscar a próxima página da lista. |
| [Before](../../aspose.pdf.ai/baselistqueryparameters/before/) { get; set; } | Obtém ou define um cursor para uso na paginação. before é um ID de objeto que define seu lugar na lista. Por exemplo, se você fizer uma solicitação de lista e receber 100 objetos, terminando com obj_foo, sua chamada subsequente pode incluir before=obj_foo para buscar a página anterior da lista. |
| [Limit](../../aspose.pdf.ai/baselistqueryparameters/limit/) { get; set; } | Obtém ou define um limite no número de objetos a serem retornados. Limit pode variar entre 1 e 100, e o padrão é 20. |
| [Order](../../aspose.pdf.ai/baselistqueryparameters/order/) { get; set; } | Obtém ou define a ordem de classificação pelo timestamp created_at dos objetos. asc para ordem crescente e desc para ordem decrescente. |

## Métodos

| Nome | Descrição |
| --- | --- |
| [GetQueryParameters](../../aspose.pdf.ai/runlistqueryparameters/getqueryparameters/)() | Obtém os parâmetros de consulta para listar execuções. |

### Veja Também

* classe [BaseListQueryParameters](../baselistqueryparameters/)
* interface [IQueryParameters](../iqueryparameters/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)