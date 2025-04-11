---
title: Class VectorStoreFileBatchFileListQueryParameters
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.AI.VectorStoreFileBatchFileListQueryParameters. Objeto de parâmetros de consulta para listar arquivos de lote do armazenamento vetorial
type: docs
weight: 1290
url: /pt/net/aspose.pdf.ai/vectorstorefilebatchfilelistqueryparameters/
---
## Classe VectorStoreFileBatchFileListQueryParameters

Objeto de parâmetros de consulta para listar arquivos de lote do armazenamento vetorial.

```csharp
public class VectorStoreFileBatchFileListQueryParameters : BaseListQueryParameters, IQueryParameters
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [VectorStoreFileBatchFileListQueryParameters](vectorstorefilebatchfilelistqueryparameters/)() | O construtor padrão. |

## Propriedades

| Nome | Descrição |
| --- | --- |
| [After](../../aspose.pdf.ai/baselistqueryparameters/after/) { get; set; } | Obtém ou define um cursor para uso na paginação. after é um ID de objeto que define sua posição na lista. Por exemplo, se você fizer uma solicitação de lista e receber 100 objetos, terminando com obj_foo, sua chamada subsequente pode incluir after=obj_foo para buscar a próxima página da lista. |
| [Before](../../aspose.pdf.ai/baselistqueryparameters/before/) { get; set; } | Obtém ou define um cursor para uso na paginação. before é um ID de objeto que define sua posição na lista. Por exemplo, se você fizer uma solicitação de lista e receber 100 objetos, terminando com obj_foo, sua chamada subsequente pode incluir before=obj_foo para buscar a página anterior da lista. |
| [Filter](../../aspose.pdf.ai/vectorstorefilebatchfilelistqueryparameters/filter/) { get; set; } | Obtém ou define um filtro pelo status do arquivo. Um dos in_progress, completed, failed, cancelled. |
| [Limit](../../aspose.pdf.ai/baselistqueryparameters/limit/) { get; set; } | Obtém ou define um limite no número de objetos a serem retornados. O limite pode variar entre 1 e 100, e o padrão é 20. |
| [Order](../../aspose.pdf.ai/baselistqueryparameters/order/) { get; set; } | Obtém ou define a ordem de classificação pelo timestamp created_at dos objetos. asc para ordem crescente e desc para ordem decrescente. |

## Métodos

| Nome | Descrição |
| --- | --- |
| [GetQueryParameters](../../aspose.pdf.ai/vectorstorefilebatchfilelistqueryparameters/getqueryparameters/)() | Obtém os parâmetros de consulta para listar arquivos de lote do armazenamento. |

### Veja Também

* classe [BaseListQueryParameters](../baselistqueryparameters/)
* interface [IQueryParameters](../iqueryparameters/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)