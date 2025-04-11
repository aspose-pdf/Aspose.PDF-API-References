---
title: Class SetColorStroke
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.Operators.SetColorStroke. Clase que representa el operador SC para establecer el color de los operadores de color de trazo
type: docs
weight: 7680
url: /es/net/aspose.pdf.operators/setcolorstroke/
---
## Clase SetColorStroke

Clase que representa el operador SC para establecer el color de los operadores de color de trazo.

```csharp
public class SetColorStroke : BasicSetColorOperator
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [SetColorStroke](setcolorstroke/#constructor)() | Inicializa el operador. |
| [SetColorStroke](setcolorstroke/#constructor_1)(double) | Establece el color para los operadores de trazo para los espacios de color DeviceGray, CalGray e Indexed. |
| [SetColorStroke](setcolorstroke/#constructor_4)(double[]) | Constructor que permite establecer los componentes de color. |
| [SetColorStroke](setcolorstroke/#constructor_2)(double, double, double) | Establece el color para el operador de trazo para los espacios de color DeviceRGB, CalRGB y Lab. |
| [SetColorStroke](setcolorstroke/#constructor_3)(double, double, double, double) | Establece el color para el operador de trazo para el espacio de color CMYK. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [B](../../aspose.pdf.operators/setcolorstroke/b/) { get; set; } | Obtiene o establece el componente azul. |
| [C](../../aspose.pdf.operators/setcolorstroke/c/) { get; set; } | Obtiene o establece el componente cian. |
| virtual [Color](../../aspose.pdf.operators/basicsetcoloroperator/color/) { get; } | Obtiene el arreglo de componentes de color. |
| [G](../../aspose.pdf.operators/setcolorstroke/g/) { get; set; } | Obtiene o establece el componente verde. |
| [Gray](../../aspose.pdf.operators/basicsetcoloroperator/gray/) { get; } | Obtiene el componente negro del color gris. |
| [Index](../../aspose.pdf/operator/index/) { get; set; } | Índice del operador en la lista de operadores de la página. |
| [K](../../aspose.pdf.operators/setcolorstroke/k/) { get; set; } | Obtiene o establece el componente negro. |
| [M](../../aspose.pdf.operators/setcolorstroke/m/) { get; set; } | Obtiene o establece el componente magenta. |
| [R](../../aspose.pdf.operators/setcolorstroke/r/) { get; set; } | Obtiene o establece el componente rojo. |
| [Y](../../aspose.pdf.operators/setcolorstroke/y/) { get; set; } | Obtiene o establece el componente amarillo. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [Accept](../../aspose.pdf.operators/setcolorstroke/accept/)(IOperatorSelector) | Acepta el objeto visitante para procesar el operador. |
| override [getColor](../../aspose.pdf.operators/setcolorstroke/getcolor/)() | Devuelve el color especificado por el operador. |
| override [ToString](../../aspose.pdf/operator/tostring/)() | Devuelve el texto del operador y sus parámetros. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(Operator) | Compara esta instancia con el objeto dado. |

### Ver También

* clase [BasicSetColorOperator](../basicsetcoloroperator/)
* espacio de nombres [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* ensamblaje [Aspose.PDF](../../)