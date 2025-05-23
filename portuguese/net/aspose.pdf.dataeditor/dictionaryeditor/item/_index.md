---
title: DictionaryEditor.Item
second_title: Aspose.PDF for .NET API Reference
description: Propriedade DictionaryEditor. Obtém ou define o elemento com a chave especificada
type: docs
weight: 50
url: /pt/net/aspose.pdf.dataeditor/dictionaryeditor/item/
---
## Indexador DictionaryEditor

Obtém ou define o elemento com a chave especificada.

```csharp
public ICosPdfPrimitive this[string key] { get; set; }
```

| Parâmetro | Descrição |
| --- | --- |
| key | A chave do elemento a ser obtido ou definido. |

### Valor de Retorno

O elemento com a chave especificada.

### Exceções

| exceção | condição |
| --- | --- |
| ArgumentNullException | A chave é nula. |
| KeyNotFoundException | A propriedade é recuperada e a chave não é encontrada. |
| ArgumentException | Lança exceção se a chave não puder ser editada/definida. |

### Veja Também

* interface [ICosPdfPrimitive](../../icospdfprimitive/)
* class [DictionaryEditor](../)
* namespace [Aspose.Pdf.DataEditor](../../../aspose.pdf.dataeditor/)
* assembly [Aspose.PDF](../../../)