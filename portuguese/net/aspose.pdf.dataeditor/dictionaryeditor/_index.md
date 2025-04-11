---
title: Class DictionaryEditor
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.DataEditor.DictionaryEditor. Uma classe para acessar o dicionário da árvore de um documento (dicionário do documento, dicionário da página, dicionário de recursos).
type: docs
weight: 3470
url: /pt/net/aspose.pdf.dataeditor/dictionaryeditor/
---
## Classe DictionaryEditor

Uma classe para acessar o dicionário da árvore de um documento (dicionário do documento, dicionário da página, dicionário de recursos).

```csharp
public class DictionaryEditor : IDictionary<string, ICosPdfPrimitive>
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [DictionaryEditor](dictionaryeditor/#constructor)(Document) |  |
| [DictionaryEditor](dictionaryeditor/#constructor_1)(Page) |  |
| [DictionaryEditor](dictionaryeditor/#constructor_2)(Resources) |  |

## Propriedades

| Nome | Descrição |
| --- | --- |
| [AllKeys](../../aspose.pdf.dataeditor/dictionaryeditor/allkeys/) { get; } | Coleção completa de chaves. Contém chaves editáveis e não editáveis. |
| [Count](../../aspose.pdf.dataeditor/dictionaryeditor/count/) { get; } | Obtém o número de elementos contidos no `DictionaryEditor`. |
| [IsReadOnly](../../aspose.pdf.dataeditor/dictionaryeditor/isreadonly/) { get; } | Obtém um valor indicando se o `DictionaryEditor` é somente leitura. |
| [Item](../../aspose.pdf.dataeditor/dictionaryeditor/item/) { get; set; } | Obtém ou define o elemento com a chave especificada. |
| [Keys](../../aspose.pdf.dataeditor/dictionaryeditor/keys/) { get; } | Coleção de chaves editáveis. |
| [Values](../../aspose.pdf.dataeditor/dictionaryeditor/values/) { get; } | Obtém um ICollection contendo os valores no `DictionaryEditor`. |

## Métodos

| Nome | Descrição |
| --- | --- |
| [Add](../../aspose.pdf.dataeditor/dictionaryeditor/add/#add)(KeyValuePair&lt;string, ICosPdfPrimitive&gt;) | Define [`ICosPdfPrimitive`](../icospdfprimitive/) no dicionário. |
| [Add](../../aspose.pdf.dataeditor/dictionaryeditor/add/#add_1)(string, ICosPdfPrimitive) | Define [`ICosPdfPrimitive`](../icospdfprimitive/) no dicionário. |
| [Clear](../../aspose.pdf.dataeditor/dictionaryeditor/clear/)() | Remove todos os itens do `DictionaryEditor`. |
| [Contains](../../aspose.pdf.dataeditor/dictionaryeditor/contains/)(KeyValuePair&lt;string, ICosPdfPrimitive&gt;) | Determina se o `DictionaryEditor` contém um valor específico. |
| [ContainsKey](../../aspose.pdf.dataeditor/dictionaryeditor/containskey/)(string) | Determina se o `DictionaryEditor` contém um elemento com a chave especificada. |
| [CopyTo](../../aspose.pdf.dataeditor/dictionaryeditor/copyto/)(KeyValuePair&lt;string, ICosPdfPrimitive&gt;[], int) |  |
| [GetEnumerator](../../aspose.pdf.dataeditor/dictionaryeditor/getenumerator/)() | Retorna um enumerador que itera pela coleção. |
| [Remove](../../aspose.pdf.dataeditor/dictionaryeditor/remove/#remove)(KeyValuePair&lt;string, ICosPdfPrimitive&gt;) | Remove a primeira ocorrência de um objeto específico do `DictionaryEditor`. |
| [Remove](../../aspose.pdf.dataeditor/dictionaryeditor/remove/#remove_1)(string) | Remove o elemento com a chave especificada do `DictionaryEditor`. |
| [TryGetValue](../../aspose.pdf.dataeditor/dictionaryeditor/trygetvalue/)(string, out ICosPdfPrimitive) | Para acesso a tipos de dados simples como string, nome, bool, número. Retorna nulo para outros tipos. |

### Veja Também

* interface [ICosPdfPrimitive](../icospdfprimitive/)
* namespace [Aspose.Pdf.DataEditor](../../aspose.pdf.dataeditor/)
* assembly [Aspose.PDF](../../)