---
title: Class Operator
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Operator. Classe abstrata representando operador
type: docs
weight: 7070
url: /pt/net/aspose.pdf/operator/
---
## Classe Operador

Classe abstrata representando operador.

```csharp
public abstract class Operator
```

## Propriedades

| Nome | Descrição |
| --- | --- |
| [Index](../../aspose.pdf/operator/index/) { get; set; } | Índice do operador na lista de operadores da página. |

## Métodos

| Nome | Descrição |
| --- | --- |
| abstract [Accept](../../aspose.pdf/operator/accept/)(IOperatorSelector) | Aceita o visitante IOperatorSelector que fornece o processamento de operadores. |
| override [ToString](../../aspose.pdf/operator/tostring/)() | Retorna o texto do operador e seus parâmetros. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(Operator) | Compara esta instância com o objeto dado. |
| static [IsTextShowOperator](../../aspose.pdf/operator/istextshowoperator/)(Operator) | Determina se o operador é o responsável pela saída de texto (Tj, TJ, etc) |

### Veja Também

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)