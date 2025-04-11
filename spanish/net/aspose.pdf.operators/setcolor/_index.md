---
title: Class SetColor
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.Operators.SetColor. Representa la clase para el operador sc que establece el color para operaciones no de trazo
type: docs
weight: 7630
url: /es/net/aspose.pdf.operators/setcolor/
---
## Clase SetColor

Representa la clase para el operador sc (establecer color para operaciones no de trazo).

```csharp
public class SetColor : BasicSetColorOperator
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [SetColor](setcolor/#constructor)() | Inicializa el operador. |
| [SetColor](setcolor/#constructor_1)(double) | Establece el color para los operadores de trazo para los espacios de color DeviceGray, CalGray e Indexed. |
| [SetColor](setcolor/#constructor_4)(double[]) | Constructor que permite especificar los componentes de color. |
| [SetColor](setcolor/#constructor_2)(double, double, double) | Establece el color para el operador de trazo para los espacios de color DeviceRGB, CalRGB y Lab. |
| [SetColor](setcolor/#constructor_3)(double, double, double, double) | Establece el color para el operador no de trazo para el espacio de color CMYK. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [B](../../aspose.pdf.operators/setcolor/b/) { get; set; } | Obtiene o establece el componente azul. |
| [C](../../aspose.pdf.operators/setcolor/c/) { get; set; } | Obtiene o establece el componente cian. |
| virtual [Color](../../aspose.pdf.operators/basicsetcoloroperator/color/) { get; } | Obtiene el arreglo de componentes de color. |
| [G](../../aspose.pdf.operators/setcolor/g/) { get; set; } | Obtiene o establece el componente verde. |
| [Gray](../../aspose.pdf.operators/basicsetcoloroperator/gray/) { get; } | Obtiene el componente negro del color gris. |
| [Index](../../aspose.pdf/operator/index/) { get; set; } | Índice del operador en la lista de operadores de página. |
| [K](../../aspose.pdf.operators/setcolor/k/) { get; set; } | Obtiene o establece el componente negro. |
| [M](../../aspose.pdf.operators/setcolor/m/) { get; set; } | Obtiene o establece el componente magenta. |
| [R](../../aspose.pdf.operators/setcolor/r/) { get; set; } | Obtiene o establece el componente rojo. |
| [Y](../../aspose.pdf.operators/setcolor/y/) { get; set; } | Obtiene o establece el componente amarillo. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [Accept](../../aspose.pdf.operators/setcolor/accept/)(IOperatorSelector) | Acepta el objeto visitante para procesar el operador. |
| override [getColor](../../aspose.pdf.operators/setcolor/getcolor/)() | Devuelve el color especificado por el operador. |
| override [ToString](../../aspose.pdf.operators/setcolor/tostring/)() | Devuelve la representación en cadena del color. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(Operator) | Compara esta instancia con el objeto dado. |

### Véase también

* clase [BasicSetColorOperator](../basicsetcoloroperator/)
* espacio de nombres [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* ensamblaje [Aspose.PDF](../../)