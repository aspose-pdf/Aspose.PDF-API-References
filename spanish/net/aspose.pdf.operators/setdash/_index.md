---
title: Class SetDash
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.Operators.SetDash. Clase que representa el operador d para establecer el patrón de guiones de línea
type: docs
weight: 7690
url: /es/net/aspose.pdf.operators/setdash/
---
## Clase SetDash

Clase que representa el operador d (establecer patrón de guiones de línea).

```csharp
public class SetDash : Operator
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [SetDash](setdash/)(int[], int) | Crea el operador de patrón de guiones establecido. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Index](../../aspose.pdf/operator/index/) { get; set; } | Índice del operador en la lista de operadores de la página. |
| [Pattern](../../aspose.pdf.operators/setdash/pattern/) { get; set; } | Patrón de guiones. Los elementos del arreglo deben ser números que especifican las longitudes de los guiones alternos y los espacios. En el caso de un arreglo de un elemento, las longitudes de los guiones y los espacios son iguales. |
| [Phase](../../aspose.pdf.operators/setdash/phase/) { get; set; } | Fase del guion. Antes de comenzar a trazar un camino, el arreglo de guiones debe ser cíclico, sumando las longitudes de los guiones y los espacios. Cuando la longitud acumulada es igual al valor especificado por la fase del guion, comenzará el trazado del camino, y el arreglo de guiones se utilizará cíclicamente a partir de ese momento. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [Accept](../../aspose.pdf.operators/setdash/accept/)(IOperatorSelector) | Acepta un objeto visitante para procesar el operador. |
| override [ToString](../../aspose.pdf.operators/setdash/tostring/)() | Obtiene la representación en cadena del operador. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(Operator) | Compara esta instancia con el objeto dado. |

### Véase también

* clase [Operator](../../aspose.pdf/operator/)
* espacio de nombres [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* ensamblaje [Aspose.PDF](../../)