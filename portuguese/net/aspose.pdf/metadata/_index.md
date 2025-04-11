---
title: Class Metadata
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Metadata. Fornece acesso ao fluxo de metadados XMP
type: docs
weight: 6950
url: /pt/net/aspose.pdf/metadata/
---
## Classe Metadata

Fornece acesso ao fluxo de metadados XMP.

```csharp
public sealed class Metadata : IDictionary<string, XmpValue>
```

## Propriedades

| Nome | Descrição |
| --- | --- |
| [Count](../../aspose.pdf/metadata/count/) { get; } | Obtém a contagem de elementos na coleção. |
| [ExtensionFields](../../aspose.pdf/metadata/extensionfields/) { get; } | Obtém o dicionário de campos de extensão. |
| [IsFixedSize](../../aspose.pdf/metadata/isfixedsize/) { get; } | Verifica se a coleção tem tamanho fixo. |
| [IsReadOnly](../../aspose.pdf/metadata/isreadonly/) { get; } | Verifica se a coleção é somente leitura. |
| [IsSynchronized](../../aspose.pdf/metadata/issynchronized/) { get; } | Verifica se a coleção está sincronizada. |
| [Item](../../aspose.pdf/metadata/item/) { get; set; } | Obtém ou define dados dos metadados. |
| [Keys](../../aspose.pdf/metadata/keys/) { get; } | Obtém a coleção de chaves de metadados. |
| [NamespaceManager](../../aspose.pdf/metadata/namespacemanager/) { get; } | Obtém o gerenciador de namespace. |
| [SyncRoot](../../aspose.pdf/metadata/syncroot/) { get; } | Obtém o objeto de sincronização da coleção. |
| [Values](../../aspose.pdf/metadata/values/) { get; } | Obtém os valores nos metadados. |

## Métodos

| Nome | Descrição |
| --- | --- |
| [Add](../../aspose.pdf/metadata/add/#add)(KeyValuePair&lt;string, XmpValue&gt;) | Adiciona um par com chave e valor ao dicionário. |
| [Add](../../aspose.pdf/metadata/add/#add_3)(string, object) | Adiciona valor aos metadados. |
| [Add](../../aspose.pdf/metadata/add/#add_1)(string, XmpPdfAExtensionObject) | Adiciona extensão pdf aos metadados. |
| [Add](../../aspose.pdf/metadata/add/#add_2)(string, XmpValue) | Adiciona valor aos metadados. |
| [Clear](../../aspose.pdf/metadata/clear/)() | Limpa os metadados. |
| [Contains](../../aspose.pdf/metadata/contains/#contains)(KeyValuePair&lt;string, XmpValue&gt;) | Verifica se o par chave-valor especificado está contido no dicionário. |
| [Contains](../../aspose.pdf/metadata/contains/#contains_1)(string) | Verifica se a chave está contida nos metadados. |
| [ContainsKey](../../aspose.pdf/metadata/containskey/)(string) | Determina se este dicionário contém a chave especificada. |
| [CopyTo](../../aspose.pdf/metadata/copyto/)(KeyValuePair&lt;string, XmpValue&gt;[], int) |  |
| [GetEnumerator](../../aspose.pdf/metadata/getenumerator/)() | Retorna o enumerador do dicionário. |
| [GetNamespaceUriByPrefix](../../aspose.pdf/metadata/getnamespaceuribyprefix/)(string) | Retorna o URI do namespace pelo prefixo. |
| [GetPrefixByNamespaceUri](../../aspose.pdf/metadata/getprefixbynamespaceuri/)(string) | Retorna o prefixo pelo URI do namespace. |
| [RegisterNamespaceUri](../../aspose.pdf/metadata/registernamespaceuri/#registernamespaceuri)(string, string) | Registra o URI do namespace. |
| [RegisterNamespaceUri](../../aspose.pdf/metadata/registernamespaceuri/#registernamespaceuri_1)(string, string, string) | Registra o URI do namespace. |
| [Remove](../../aspose.pdf/metadata/remove/#remove)(KeyValuePair&lt;string, XmpValue&gt;) | Remove o par chave/valor da coleção. |
| [Remove](../../aspose.pdf/metadata/remove/#remove_1)(string) | Remove a entrada dos metadados. |
| [TryGetValue](../../aspose.pdf/metadata/trygetvalue/)(string, out XmpValue) | Tenta encontrar a chave no dicionário e recupera o valor se encontrado. |

### Veja Também

* classe [XmpValue](../xmpvalue/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)