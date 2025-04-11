---
title: Class TextStateOperator
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.Operators.TextStateOperator. Clase base abstracta para operadores que cambian el estado de texto actual Tc Tf TL etc
type: docs
weight: 7930
url: /es/net/aspose.pdf.operators/textstateoperator/
---
## Clase TextStateOperator

Clase base abstracta para operadores que cambian el estado de texto actual (Tc, Tf, TL, etc).

```csharp
public class TextStateOperator : TextOperator
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [TextStateOperator](textstateoperator/#constructor)() | Inicializa TextStateOperator. |
| [TextStateOperator](textstateoperator/#constructor_1)(TextProperties) | Inicializa TextStateOperator que permite pasar TextProperties. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Index](../../aspose.pdf/operator/index/) { get; set; } | Índice del operador en la lista de operadores de la página. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [Accept](../../aspose.pdf.operators/textoperator/accept/)(IOperatorSelector) | Acepta el objeto visitante para procesar el operador. |
| override [ToString](../../aspose.pdf/operator/tostring/)() | Devuelve el texto del operador y sus parámetros. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(Operator) | Compara esta instancia con el objeto dado. |

### Véase también

* clase [TextOperator](../textoperator/)
* espacio de nombres [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* ensamblaje [Aspose.PDF](../../)