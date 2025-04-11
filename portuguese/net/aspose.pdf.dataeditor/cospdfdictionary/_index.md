---
title: Class CosPdfDictionary
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.DataEditor.CosPdfDictionary. Uma classe para acessar o dicionário de objetos
type: docs
weight: 3420
url: /pt/net/aspose.pdf.dataeditor/cospdfdictionary/
---
## Classe CosPdfDictionary

Uma classe para acessar o dicionário de um objeto.

```csharp
public class CosPdfDictionary : CosPdfPrimitive, IDictionary<string, ICosPdfPrimitive>
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [CosPdfDictionary](cospdfdictionary/)(Resources) | Cria um dicionário a partir de recursos. |

## Propriedades

| Nome | Descrição |
| --- | --- |
| [AllKeys](../../aspose.pdf.dataeditor/cospdfdictionary/allkeys/) { get; } | Coleção completa de chaves. Contém chaves editáveis e não editáveis. |
| [Count](../../aspose.pdf.dataeditor/cospdfdictionary/count/) { get; } | Obtém o número de elementos contidos no `CosPdfDictionary`. |
| [IsReadOnly](../../aspose.pdf.dataeditor/cospdfdictionary/isreadonly/) { get; } | Obtém um valor que indica se o `CosPdfDictionary` é somente leitura. |
| [Item](../../aspose.pdf.dataeditor/cospdfdictionary/item/) { get; set; } | Obtém ou define o elemento com a chave especificada. |
| [Keys](../../aspose.pdf.dataeditor/cospdfdictionary/keys/) { get; } | Coleção de chaves editáveis. |
| [Values](../../aspose.pdf.dataeditor/cospdfdictionary/values/) { get; } | Obtém um ICollection contendo os valores no `CosPdfDictionary`. |

## Métodos

| Nome | Descrição |
| --- | --- |
| static [CreateEmptyDictionary](../../aspose.pdf.dataeditor/cospdfdictionary/createemptydictionary/#createemptydictionary)(Document) | Cria um dicionário vazio que será anexado ao documento. |
| static [CreateEmptyDictionary](../../aspose.pdf.dataeditor/cospdfdictionary/createemptydictionary/#createemptydictionary_1)(Page) | Cria um dicionário vazio que será anexado à página. |
| [Add](../../aspose.pdf.dataeditor/cospdfdictionary/add/#add)(KeyValuePair&lt;string, ICosPdfPrimitive&gt;) | Define [`ICosPdfPrimitive`](../icospdfprimitive/) no dicionário. |
| [Add](../../aspose.pdf.dataeditor/cospdfdictionary/add/#add_1)(string, ICosPdfPrimitive) | Define [`ICosPdfPrimitive`](../icospdfprimitive/) no dicionário. |
| [Clear](../../aspose.pdf.dataeditor/cospdfdictionary/clear/)() | Remove todos os itens do `CosPdfDictionary`. |
| [Contains](../../aspose.pdf.dataeditor/cospdfdictionary/contains/)(KeyValuePair&lt;string, ICosPdfPrimitive&gt;) | Determina se o `CosPdfDictionary` contém um valor específico. |
| [ContainsKey](../../aspose.pdf.dataeditor/cospdfdictionary/containskey/)(string) | Determina se o `CosPdfDictionary` contém um elemento com a chave especificada. |
| [CopyTo](../../aspose.pdf.dataeditor/cospdfdictionary/copyto/)(KeyValuePair&lt;string, ICosPdfPrimitive&gt;[], int) |  |
| [GetEnumerator](../../aspose.pdf.dataeditor/cospdfdictionary/getenumerator/)() | Retorna um enumerador que itera pela coleção. |
| [Remove](../../aspose.pdf.dataeditor/cospdfdictionary/remove/#remove)(KeyValuePair&lt;string, ICosPdfPrimitive&gt;) | Remove a primeira ocorrência de um objeto específico do `CosPdfDictionary`. |
| [Remove](../../aspose.pdf.dataeditor/cospdfdictionary/remove/#remove_1)(string) | Remove o elemento com a chave especificada do `CosPdfDictionary`. |
| virtual [ToCosPdfBoolean](../../aspose.pdf.dataeditor/cospdfprimitive/tocospdfboolean/)() | Tenta converter esta instância para [`CosPdfBoolean`](../cospdfboolean/). |
| override [ToCosPdfDictionary](../../aspose.pdf.dataeditor/cospdfdictionary/tocospdfdictionary/)() | Tenta converter esta instância para `CosPdfDictionary`. |
| virtual [ToCosPdfName](../../aspose.pdf.dataeditor/cospdfprimitive/tocospdfname/)() | Tenta converter esta instância para [`CosPdfName`](../cospdfname/). |
| virtual [ToCosPdfNumber](../../aspose.pdf.dataeditor/cospdfprimitive/tocospdfnumber/)() | Tenta converter esta instância para [`CosPdfNumber`](../cospdfnumber/). |
| virtual [ToCosPdfString](../../aspose.pdf.dataeditor/cospdfprimitive/tocospdfstring/)() | Tenta converter esta instância para [`CosPdfString`](../cospdfstring/). |
| [TryGetValue](../../aspose.pdf.dataeditor/cospdfdictionary/trygetvalue/)(string, out ICosPdfPrimitive) | Para acesso a tipos de dados simples como string, nome, bool, número. Retorna nulo para outros tipos. |

### Veja Também

* classe [CosPdfPrimitive](../cospdfprimitive/)
* interface [ICosPdfPrimitive](../icospdfprimitive/)
* namespace [Aspose.Pdf.DataEditor](../../aspose.pdf.dataeditor/)
* assembly [Aspose.PDF](../../)