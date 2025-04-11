---
title: Class AppearanceDictionary
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Annotations.AppearanceDictionary. Dicionário de aparência da anotação especificando como a anotação deve ser apresentada visualmente na página
type: docs
weight: 1490
url: /pt/net/aspose.pdf.annotations/appearancedictionary/
---
## Classe AppearanceDictionary

Dicionário de aparência da anotação especificando como a anotação deve ser apresentada visualmente na página.

```csharp
public sealed class AppearanceDictionary : IDictionary<string, XForm>
```

## Propriedades

| Nome | Descrição |
| --- | --- |
| [Count](../../aspose.pdf.annotations/appearancedictionary/count/) { get; } | Obtém o número de elementos contidos no dicionário. |
| [IsFixedSize](../../aspose.pdf.annotations/appearancedictionary/isfixedsize/) { get; } | Obtém um valor indicando se o dicionário tem um tamanho fixo. |
| [IsReadOnly](../../aspose.pdf.annotations/appearancedictionary/isreadonly/) { get; } | Obtém um valor indicando se o dicionário é somente leitura. |
| [IsSynchronized](../../aspose.pdf.annotations/appearancedictionary/issynchronized/) { get; } | Obtém um valor indicando se o acesso ao dicionário é sincronizado (seguro para threads). |
| [Item](../../aspose.pdf.annotations/appearancedictionary/item/) { get; set; } | Representa uma forma conveniente para obter fluxos de aparência. |
| [Keys](../../aspose.pdf.annotations/appearancedictionary/keys/) { get; } | Obtém as chaves do dicionário. Se o dicionário de aparência tiver subdicionários, então [`Keys`](./keys/) contém valores (N&#x7C;R&#x7C;D).state, onde N - aparência normal, R - aparência de rollover, D - aparência de down e state - o nome do estado (por exemplo, On, Off para caixas de seleção). |
| [SyncRoot](../../aspose.pdf.annotations/appearancedictionary/syncroot/) { get; } | Obtém um objeto que pode ser usado para sincronizar o acesso ao dicionário. |
| [Values](../../aspose.pdf.annotations/appearancedictionary/values/) { get; } | Obtém a lista dos valores do dicionário. A coleção resultante contém a lista de objetos XForm. |

## Métodos

| Nome | Descrição |
| --- | --- |
| [Add](../../aspose.pdf.annotations/appearancedictionary/add/#add)(KeyValuePair&lt;string, XForm&gt;) | Adiciona um par com chave e valor ao dicionário. |
| [Add](../../aspose.pdf.annotations/appearancedictionary/add/#add_2)(string, XForm) | Adiciona um X form para a chave especificada. |
| [Clear](../../aspose.pdf.annotations/appearancedictionary/clear/)() | Remove todos os elementos do dicionário. |
| [Contains](../../aspose.pdf.annotations/appearancedictionary/contains/)(KeyValuePair&lt;string, XForm&gt;) | Verifica se o par chave-valor especificado está contido no dicionário. |
| [ContainsKey](../../aspose.pdf.annotations/appearancedictionary/containskey/)(string) | Determina se este dicionário contém a chave especificada. |
| [CopyTo](../../aspose.pdf.annotations/appearancedictionary/copyto/#copyto_1)(KeyValuePair&lt;string, XForm&gt;[], int) |  |
| [CopyTo](../../aspose.pdf.annotations/appearancedictionary/copyto/#copyto)(XForm[], int) | Copia os elementos do dicionário para um Array, começando em um índice específico do Array. |
| [GetEnumerator](../../aspose.pdf.annotations/appearancedictionary/getenumerator/)() | Retorna um objeto IDictionaryEnumerator para o dicionário. |
| [Remove](../../aspose.pdf.annotations/appearancedictionary/remove/#remove)(KeyValuePair&lt;string, XForm&gt;) | Remove o par chave/valor da coleção. |
| [Remove](../../aspose.pdf.annotations/appearancedictionary/remove/#remove_1)(string) | Remove a chave do dicionário. |
| [TryGetValue](../../aspose.pdf.annotations/appearancedictionary/trygetvalue/)(string, out XForm) | Tenta encontrar a chave no dicionário e recupera o valor se encontrado. |

### Veja Também

* classe [XForm](../../aspose.pdf/xform/)
* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)