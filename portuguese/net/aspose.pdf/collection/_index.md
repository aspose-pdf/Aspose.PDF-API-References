---
title: Class Collection
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Collection. Representa a classe para Coleções12.3.5
type: docs
weight: 3020
url: /pt/net/aspose.pdf/collection/
---
## Classe Coleção

Representa a classe para Coleção(12.3.5 Coleções).

```csharp
public class Collection : EmbeddedFileCollection
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [Collection](collection/)() | Inicializa um novo objeto Collection. |

## Propriedades

| Nome | Descrição |
| --- | --- |
| [Count](../../aspose.pdf/embeddedfilecollection/count/) { get; } | Obtém o número de arquivos incorporados na coleção. |
| [DefaultEntry](../../aspose.pdf/collection/defaultentry/) { get; } | Nome do arquivo incorporado padrão. |
| [IsSynchronized](../../aspose.pdf/embeddedfilecollection/issynchronized/) { get; } | Obtém um valor que indica se o acesso a esta coleção está sincronizado (seguro para threads). |
| [Item](../../aspose.pdf/embeddedfilecollection/item/) { get; } | Obtém o arquivo incorporado pelo seu índice. (2 indexadores) |
| [Keys](../../aspose.pdf/embeddedfilecollection/keys/) { get; } | Retorna a lista de chaves de anexos de arquivos. |
| [Schema](../../aspose.pdf/collection/schema/) { get; } | Obtém um "Esquema" de uma coleção de documentos. |
| [SyncRoot](../../aspose.pdf/embeddedfilecollection/syncroot/) { get; } | Obtém um objeto que pode ser usado para sincronizar o acesso a esta coleção. |

## Métodos

| Nome | Descrição |
| --- | --- |
| [Add](../../aspose.pdf/embeddedfilecollection/add/)(FileSpecification) | Adiciona a especificação de arquivo incorporado à coleção. |
| [Add](../../aspose.pdf/embeddedfilecollection/add/)(string, FileSpecification) | Adiciona arquivo aos arquivos incorporados com a chave especificada. |
| [CopyTo](../../aspose.pdf/embeddedfilecollection/copyto/)(FileSpecification[], int) | Copia o array de objetos FileSpecification para a coleção. |
| [Delete](../../aspose.pdf/embeddedfilecollection/delete/)() | Remove todos os arquivos incorporados do documento. |
| [Delete](../../aspose.pdf/embeddedfilecollection/delete/)(string) | Deleta o arquivo incorporado pelo nome. |
| [DeleteByKey](../../aspose.pdf/embeddedfilecollection/deletebykey/)(string) | Deleta o arquivo da coleção pela sua chave na coleção. |
| [FindByName](../../aspose.pdf/embeddedfilecollection/findbyname/)(string) | Retorna o arquivo incorporado pelo seu nome. |
| [GetEnumerator](../../aspose.pdf/embeddedfilecollection/getenumerator/)() | Retorna o enumerador da coleção. |
| [GetSortedCollection](../../aspose.pdf/collection/getsortedcollection/)() | Obtém uma coleção de arquivos ordenados de acordo com a especificação. |

### Veja Também

* classe [EmbeddedFileCollection](../embeddedfilecollection/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)