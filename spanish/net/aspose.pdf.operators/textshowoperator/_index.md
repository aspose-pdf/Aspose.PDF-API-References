---
title: Class TextShowOperator
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.Operators.TextShowOperator. Clase base abstracta para todos los operadores que se utilizan para mostrar texto Tj TJ, etc.
type: docs
weight: 7920
url: /es/net/aspose.pdf.operators/textshowoperator/
---
## Clase TextShowOperator

Clase base abstracta para todos los operadores que se utilizan para mostrar texto (Tj, TJ, etc).

```csharp
public class TextShowOperator : TextOperator
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [TextShowOperator](textshowoperator/#constructor)() | Inicializa TextShowOperator. |
| [TextShowOperator](textshowoperator/#constructor_1)(TextProperties) | Inicializa TextShowOperator que permite pasar TextProperties. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Index](../../aspose.pdf/operator/index/) { get; set; } | Índice del operador en la lista de operadores de la página. |
| virtual [Text](../../aspose.pdf.operators/textshowoperator/text/) { get; set; } | Obtiene el texto que el operador muestra en la página. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [Accept](../../aspose.pdf.operators/textoperator/accept/)(IOperatorSelector) | Acepta el objeto visitante para procesar el operador. |
| override [ToString](../../aspose.pdf/operator/tostring/)() | Devuelve el texto del operador y sus parámetros. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(Operator) | Compara esta instancia con el objeto dado. |

### Ver También

* clase [TextOperator](../textoperator/)
* espacio de nombres [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* ensamblaje [Aspose.PDF](../../)