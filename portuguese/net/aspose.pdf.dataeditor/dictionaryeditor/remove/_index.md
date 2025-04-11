---
title: DictionaryEditor.Remove
second_title: Aspose.PDF for .NET API Reference
description: Método DictionaryEditor. Remove o elemento com a chave especificada do DictionaryEditor
type: docs
weight: 140
url: /pt/net/aspose.pdf.dataeditor/dictionaryeditor/remove/
---
## Remove(string) {#remove_1}

Remove o elemento com a chave especificada do [`DictionaryEditor`](../).

```csharp
public bool Remove(string key)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| key | String | A chave do elemento a ser removido. |

### Valor de Retorno

Verdadeiro se o elemento for removido com sucesso; caso contrário, falso. Este método também retorna falso se a chave não foi encontrada no dicionário original ou se a chave não é editável.

### Veja Também

* classe [DictionaryEditor](../)
* namespace [Aspose.Pdf.DataEditor](../../../aspose.pdf.dataeditor/)
* assembly [Aspose.PDF](../../../)

---

## Remove(KeyValuePair&lt;string, ICosPdfPrimitive&gt;) {#remove}

Remove a primeira ocorrência de um objeto específico do [`DictionaryEditor`](../).

```csharp
public bool Remove(KeyValuePair<string, ICosPdfPrimitive> item)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| item | KeyValuePair`2 | O objeto a ser removido do [`DictionaryEditor`](../). |

### Valor de Retorno

verdadeiro se o item foi removido com sucesso do [`DictionaryEditor`](../); caso contrário, falso. Este método também retorna falso se o item não for encontrado no [`DictionaryEditor`](../).

### Veja Também

* interface [ICosPdfPrimitive](../../icospdfprimitive/)
* classe [DictionaryEditor](../)
* namespace [Aspose.Pdf.DataEditor](../../../aspose.pdf.dataeditor/)
* assembly [Aspose.PDF](../../../)