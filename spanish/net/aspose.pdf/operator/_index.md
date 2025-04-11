---
title: Class Operator
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.Operator. Clase abstracta que representa un operador
type: docs
weight: 7070
url: /es/net/aspose.pdf/operator/
---
## Clase Operador

Clase abstracta que representa un operador.

```csharp
public abstract class Operator
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Index](../../aspose.pdf/operator/index/) { get; set; } | Índice del operador en la lista de operadores de la página. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| abstract [Accept](../../aspose.pdf/operator/accept/)(IOperatorSelector) | Acepta el visitante IOperatorSelector que proporciona el procesamiento de operadores. |
| override [ToString](../../aspose.pdf/operator/tostring/)() | Devuelve el texto del operador y sus parámetros. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(Operator) | Compara esta instancia con el objeto dado. |
| static [IsTextShowOperator](../../aspose.pdf/operator/istextshowoperator/)(Operator) | Determina si el operador es el responsable de la salida de texto (Tj, TJ, etc) |

### Véase También

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)