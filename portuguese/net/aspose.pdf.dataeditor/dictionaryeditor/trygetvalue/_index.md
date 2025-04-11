---
title: DictionaryEditor.TryGetValue
second_title: Aspose.PDF for .NET API Reference
description: Método DictionaryEditor. Para acesso a tipos de dados simples como string, nome, bool, número. Retorna nulo para outros tipos
type: docs
weight: 150
url: /pt/net/aspose.pdf.dataeditor/dictionaryeditor/trygetvalue/
---
## Método DictionaryEditor.TryGetValue

Para acesso a tipos de dados simples como string, nome, bool, número. Retorna nulo para outros tipos.

```csharp
public bool TryGetValue(string key, out ICosPdfPrimitive value)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| key | String | Valor da chave |
| value | ICosPdfPrimitive& | retorna [`ICosPdfPrimitive`](../../icospdfprimitive/) para a chave ou nulo. |

### Valor de Retorno

Retorna verdadeiro se [`ICosPdfPrimitive`](../../icospdfprimitive/) for como string, nome, bool, número. Retorna falso para todos os outros tipos.

### Veja Também

* interface [ICosPdfPrimitive](../../icospdfprimitive/)
* classe [DictionaryEditor](../)
* namespace [Aspose.Pdf.DataEditor](../../../aspose.pdf.dataeditor/)
* assembly [Aspose.PDF](../../../)